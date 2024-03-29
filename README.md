# CKEditor-TextSelection-Plugin
=============================

[![npm version](https://badge.fury.io/js/ckeditor-textselection-plugin.svg)](https://www.npmjs.com/package/ckeditor-textselection-plugin)
![license](https://img.shields.io/github/license/w8tcha/ckeditor-textselection-plugin)

The plugin that makes the editor keep it's text-selection when switching between WYSIWYG and Source mode, and scrolls the selection into the viewport.

Forked from https://github.com/sirtet/ckeditor-dev/tree/master/plugins/textselection

This Plugin will also work with the CodeMirror Plugin  - http://ckeditor.com/addon/codemirror

> [!NOTE]  
> The Source Dialog works only in combination with the CodeMirror Plugin

#### Demo
http://w8tcha.github.io/CKEditor-TextSelection-Plugin/

#### License

Licensed under the terms of the MIT License.

#### Installation

 1. Extract the contents of the file into the "plugins" folder of CKEditor.
 2. In the CKEditor configuration file (config.js) add the following code:

````js
config.extraPlugins = 'textselection';
````

> [!CAUTION]
> Editor Mode 'fullPage' is not supported - https://ckeditor.com/docs/ckeditor4/latest/features/fullpage.html