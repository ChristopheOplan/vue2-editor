# Vue2Editor Notes

> Things To Remember And Add To Other Notes file

## Importing Quill's styles

``` scss
@import '~quill/dist/quill.core.css';
@import '~quill/dist/quill.bubble.css';
@import '~quill/dist/quill.snow.css';
```

**Both of these work**

``` js
import "vue2-editor/dist/css/vue2-editor.css";
import "quill/dist/quill.snow.css";
```

``` html
<style src="quill/dist/quill.snow.css"></style>
<!-- OR -->
<style>
@import "~quill/dist/quill.snow.css";

body {
  background: lightgrey !important;
}
.quillWrapper {
  padding: 1em;
  background: white;
}

.ql-editor {
  min-height: 300px;
}
</style>
```

## Releases

If a version has been published within the past 72 hours it can be removed if needed.
As follows:

``` bash
npm unpublish vue2-editor@version
```