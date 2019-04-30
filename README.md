# Why

Currently Tinymce's lang does not have cdn. So create an npm package, let lang supports cdn.

# Use

All cnd in [jsdelivr](https://www.jsdelivr.com/package/npm/tinymce-lang?path=langs)

- [zh_CN](https://cdn.jsdelivr.net/npm/tinymce-lang/langs/zh_CN.js)
- [ja](https://cdn.jsdelivr.net/npm/tinymce-lang/langs/ja.js)
- ...

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  language: 'zh_CN', // select language
  language_url: 'https://cdn.jsdelivr.net/npm/tinymce-lang/langs/zh_CN.js'  // site absolute URL
});
```
