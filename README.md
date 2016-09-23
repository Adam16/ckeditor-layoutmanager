# CKEditor layout manager plugin

## The Official Documentation Site
http://docs.ckeditor.com/#!/guide/plugin_sdk_intro

## Code samples for the official CKEditor documentation
https://github.com/ckeditor/ckeditor-docs-samples

### Configuration

    config.extraPlugins = "layoutmanager"
    config.layoutmanager_loadbootstrap = true/false (false by default - embedded bootstrap.css is not loaded)
    config.layoutmanager_allowedContent (all tags are allowed by default)
    config.layoutmanager_buttonboxWidth = 58 (the width of each layout-preview button in the dialog)

Name for adding into the toolbar : "LayoutManager"

### Events

    layoutmanager:layout-inserted - fired when layout is inserted

### Dependencies
https://jquery.com/
