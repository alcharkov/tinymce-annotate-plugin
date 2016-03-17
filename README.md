#TinyMCE Annotate

Create annotations in your content with this TinyMCE 4 plugin.
If any issues occure, use compat3x plugin.

## Setup
Code example:
```javascript
tinymce.init({
    selector: "#textarea",
    plugins: "tma_annotate",
    toolbar1: "tma_annotate | tma_annotatedelete | tma_annotatehide"
});
``
