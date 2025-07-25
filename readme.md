[![](./assets/editor-awesome.png)](https://editorjs.io/)

# Awesome Editor.js [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome Editor.js tools, libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by contributing!

## Contents

* [Tools](#tools)
  * [Block Tools](#block-tools)
    * [Text and typography](#text-and-typography)
    * [Lists](#lists)
    * [Media & Embed](#media--embed)
    * [Table](#table)
    * [Code](#code)
    * [Button](#button)
    * [Layout](#layout)
  * [Inline Tools](#inline-tools)
  * [Block Tune Tools](#block-tune-tools)
  * [Plugins](#plugins)
* [Libraries](#libraries)
  * [JavaScript](#javascript)
    * [Vue.js](#vuejs)
    * [React](#react)
    * [React Native](#react-native)
    * [Angular](#angular)
    * [Svelte](#svelte)
  * [PHP](#php)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Go](#go)
  * [Swift](#swift)
  * [Kotlin](#kotlin)
  * [Plugins for CMS](#plugins-for-cms)
* [Tutorials and sources](#tutorials-and-sources)
* [Projects Using Editor.js](#projects-using-editorjs)
  * [Open source projects](#open-source-projects)
<!-- * [Apps / Websites](#apps-websites) -->
<!-- * [Commercial Products](#commercial-products) -->



## Ask AI

[Awesome-Editorjs](https://codeparrot.ai/oracle?owner=editor-js&repo=awesome-editorjs) AI will help you understand this repository better. 

## Tools

### Block Tools

#### Text and typography

* [@editorjs/paragraph](https://github.com/editor-js/paragraph) — text block base tool 
* [@editorjs/header](https://github.com/editor-js/header) — header block
* [@editorjs/quote](https://github.com/editor-js/quote) — tool for quotes
* [@editorjs/warning](https://github.com/editor-js/warning) — warning tool can be used as editorials notifications or appeals
* [@editorjs/delimiter](https://github.com/editor-js/delimiter) — delimiter tool
* [@coolbytes/editorjs-delimiter](https://github.com/CoolBytesIN/editorjs-delimiter) — Improved delimiter block tool (Includes more styles - `dash` and `line`)
* [editorjs-alert](https://github.com/vishaltelangre/editorjs-alert) - tool for adding colorful alert messages
* [header-with-alignment](https://github.com/wandersonsousa/header-with-alignment) - header block base tool with alignment control
* [paragraph-with-alignment](https://github.com/kaaaaaaaaaaai/paragraph-with-alignment) - text block base tool with alignment control. FYI [editorjs-alignment-blocktune](https://github.com/kaaaaaaaaaaai/editorjs-alignment-blocktune)
* [header-with-anchor](https://github.com/Aleksst95/header-with-anchor) - header block with the ability to set an anchor text
* [editorjs-toggle-block](https://github.com/kommitters/editorjs-toggle-block) - tool for nesting blocks in a toggleable element
* [editorjs-aitext](https://github.com/etozhealkhipce/editorjs-aitext) - ai suggestions tool based on paragraph tool and openai node lib
* [title-editorjs](https://github.com/EmersonMatias/title-editorjs) - Provides Title (headings) Blocks for the Editor.js with various settings like H1...H6, colors (red, pink, purple...) and text-align. It is compatible with react and typescript, without causing typing errors.
* [editorjs-color-picker](https://github.com/Matergi/editorjs-color-picker) - Color Picker Tool
* [@cychann/editorjs-quote](https://github.com/cychann/editorjs-quote) - Improved Quote Block Tool (Includes more quote styles)

#### Lists

* [@editorjs/list](https://github.com/editor-js/list) — ordered or unordered (bulleted) lists
* [@editorjs/nested-list](https://github.com/editor-js/nested-list) — Multi-leveled lists
* [@editorjs/checklist](https://github.com/editor-js/checklist) — checklists for your texts
* [@calumk/editorjs-nested-checklist](https://github.com/calumk/editorjs-nested-checklist) — Nested Checklists for your texts

#### Media & Embed

* [@editorjs/image](https://github.com/editor-js/image) — image block
* [@editorjs/simple-image](https://github.com/editor-js/simple-image) — add images to article by pasting image URLs. no server-side uploader required
* [@editorjs/link](https://github.com/editor-js/link) — link with preview
* [@editorjs/attaches](https://github.com/editor-js/attaches) — attach files to your article
* [@editorjs/embed](https://github.com/editor-js/embed) — pasted patterns handling and inserts iframe with embedded content
* [simple-image-editorjs](https://github.com/PaulKinlan/simple-image) — fork of the SimpleImage repository. It adds in extra functionality such as a toolbar to add images (rather than just drag and drop) and uses blob URL's to improve memory usage
* [editorjs-inline-image](https://github.com/kommitters/editorjs-inline-image) — embed images from image files, URLs or Unsplash
* [mr8bit/carousel-editorjs](https://github.com/mr8bit/carousel-editorjs) — Carousel/Gallery Block for the Editor.js
* [mdgaziur/EditorJS-LaTeX](https://github.com/mdgaziur/EditorJS-LaTeX) — LaTeX block support for EditorJS
* [rodrigoodhin/editorjs-image-gallery](https://gitlab.com/rodrigoodhin/editorjs-image-gallery) — image gallery block
* [naduma/editorjs-mermaid](https://github.com/naduma/editorjs-mermaid) — Mermaid Block for Editor.js
* [VolgaIgor/editorjs-gallery](https://github.com/VolgaIgor/editorjs-gallery) — Gallery Block with multiloading and sorting
* [AnatoliyKozlov/editorjs-telegram-post](https://github.com/AnatoliyKozlov/editorjs-telegram-post) — Telegram Post widget
* [renanrider/editorjs-audio-player](https://github.com/renanrider/editorjs-audio-player) - Simple Audio Tool, works only with pasted URLs with audio src and requires no server-side uploader.
* [Furison-Tech/editorjs-audio](https://github.com/Furison-Tech/editorjs-audio) - HTML audio block with uploader (requires server-side uploader), based on the official editorjs image tool.
* [sureshHARDIYA/flipboxplus](https://github.com/sureshHARDIYA/flipboxplus) - Configurable carousel that allows to add, edit, delete slides. Slides are configured to display as flipbox. 
* [image-with-link](https://github.com/kaaaaaaaaaaai/image-with-link) - upload image with link. forked by official image plugin
* [editorjs-drawing-tool](https://github.com/blade47/editorjs-drawing-tool) - Drawing Tool for Editor.js

#### Table

* [@editorjs/table](https://github.com/editor-js/table) — table constructor tool
* [editorjs-table](https://github.com/4rw44z/editorjs-table) - Table contructor tool with great editing row/column options.

#### Code

* [@editorjs/code](https://github.com/editor-js/code) — tools for code examples
* [@editorjs/raw](https://github.com/editor-js/raw) — include raw HTML code to your article
* [editor-js-code](https://github.com/paraswaykole/editor-js-code) — a fork of Code Tool for the Editor.js that allows to include code examples along with language codes that are supported by PrismJs in your articles
* [editorjs-codemirror](https://github.com/alexiej/editorjs-codemirror) — Code Mirror for the Editor.js allows to include code examples in your articles.
* [@bomdi/codebox](https://github.com/BomdiZane/codebox) — code syntax highlighting tool for Editor.js
* [@calumk/editorjs-codeflask](https://github.com/calumk/editorjs-codeflask) — Beautiful code highlighting, with linenumbers, and language support. Powered by Codeflask + PrismJs
* [ace-code-editorjs](https://github.com/hsnfirdaus/ace-code-editorjs) — Ace Code Editor block for the Editor.js with language selection.
* [@rxpm/editor-js-code](https://github.com/rajatxs/editor-js-code) - Custom Code Plugin adds code examples to articles with a language dropdown.

#### Button

* [editorjs-button](https://github.com/kaaaaaaaaaaai/editorjs-button) — Create a button with a link and text.

#### Layout

* [editorjs-layout](https://github.com/hata6502/editorjs-layout) — Layout block tool for Editor.js.
* [@calumk/editorjs-columns](https://github.com/calumk/editorjs-columns) — Multi-Column Layout tool, using nested editorJs Instances

### Inline Tools

* [@editorjs/marker](https://github.com/editor-js/marker) — tool for highlighting text-fragments
* [@editorjs/inline-code](https://github.com/editor-js/inline-code) — tool for marking monospace code-fragments
* [@editorjs/underline](https://github.com/editor-js/underline) — underlining text fragments
* [@editorjs/link-autocomplete](https://github.com/editor-js/link-autocomplete) — an upgraded version of base inline link tool with your server's search
* [editorjs-hyperlink](https://github.com/trinhtam/editorjs-hyperlink) — a tool link with target & rel attribute for Editor.js
* [editorjs-inline-spoiler-tool](https://www.npmjs.com/package/editorjs-inline-spoiler-tool) — inline text spoiler
* [editorjs-inline-tool](https://github.com/natterstefan/editorjs-inline-tool) — create an inline tool for (editorjs.io) with text formatting tags (eg. bold, strong, em, u, ...)
* [editorjs-inline](https://github.com/hata6502/editorjs-inline) — Inline-Editor.js Tool for Editor.js
* [editorjs-inline-template](https://github.com/hata6502/editorjs-inline-template) — Inline-template Tool for Editor.js
* [editorjs-style](https://github.com/hata6502/editorjs-style) — Inline-style Tool for Editor.js
* [editorjs-change-case](https://github.com/maziyank/editorjs-change-case) — change case Tool for the Editor.js
* [editorjs-tooltip](https://github.com/kommitters/editorjs-tooltip) — Tool for adding tooltips in EditorJS
* [@sotaproject/strikethrough](https://www.npmjs.com/package/@sotaproject/strikethrough) - tool for strikethrough text
* [editorjs-text-color-plugin](https://www.npmjs.com/package/editorjs-text-color-plugin) - Inline tool for coloring/marking selected text with customized colors
* [VolgaIgor/editorjs-annotation](https://github.com/VolgaIgor/editorjs-annotation) — Tool for adding an extended annotation to any text in EditorJS blocks
* [editorjs-comment](https://github.com/osain-az/editorjs-comment) - Tool that allows you to add comment to editorjs
* [editorjs-inline-hotkey](https://github.com/Stuhl/editorjs-inline-hotkey) - Inline Tool that marks text as Hotkey
* [editor-js-tg-spoiler](https://github.com/izotikov/editor-js-tg-spoiler) - Inline tool for adding spoilers to text fragments for Editor.js, supporting export to telegram.

### Block Tune Tools

* [@editorjs/text-variant-tune](https://github.com/editor-js/text-variant-tune) — Block Tune for text variants: Call-out, Citation, Details
* [editorjs-alignment-blocktune](https://github.com/kaaaaaaaaaaai/editorjs-alignment-blocktune) — Add text alignment to any Block Tools.
* [VolgaIgor/editorjs-anchor](https://github.com/VolgaIgor/editorjs-anchor) — Add anchor field to any Block Tools
* [VolgaIgor/editorjs-notice](https://github.com/VolgaIgor/editorjs-notice) — Highlight or hide with caption any Editor.js block
* [editorjs-indent-tune](https://www.npmjs.com/package/editorjs-indent-tune) - Block Tune for indenting any type of block
* [@coolbytes/editorjs-anchor](https://github.com/CoolBytesIN/editorjs-anchor) — Block Tune to toggle Anchor for any block type
* [editor-js-alignment-tune](https://github.com/Diesnei/editor-js-alignment-tune) — Block Tune to add cutomizable text alignment to any Block Tool
  
### Plugins

* [editorjs-drag-drop](https://github.com/kommitters/editorjs-drag-drop) — Drag/Drop feature for Editor.js
* [editorjs-undo](https://github.com/kommitters/editorjs-undo) — Undo/Redo feature for Editor.js
* [editorjs-markdown-parser](https://github.com/stejul/editorjs-markdown-parser) - Two plugins which allow you to export/import Markdown file
* [editorjs-multiblock-selection-plugin](https://www.npmjs.com/package/editorjs-multiblock-selection-plugin) - Plugin to extend your inline tools to work in multiblock selection

## Libraries

### JavaScript

* [editorjs-parser](https://github.com/MichaelMikeJones/editorjs-parser) — a library to parse Editorjs clean data to HTML in Node and Browser
* [editorjs-html](https://github.com/pavittarx/editorjs-html) — a utility to parse editorjs clean data to HTML
* [editorjs-to-html](https://github.com/vorjyga/editorjs-to-html) — editorjs format parser to html with saving editorjs markup format
* [editor-js-component](https://github.com/WebJeffery/editor-js-component) - an editorjs library that can use Vue and React frameworks

#### Vue.js

* [Editorjs.vue](https://gist.github.com/bettysteger/d7f2b1a52bb1c23a0c24f3a9ff5832d9) - Vue 3 SFC for Editor.js using v-model with custom Vue component using Video.js
* [vue-editor-js](https://github.com/ChangJoo-Park/vue-editor-js) — editor.js for Vue users

#### React

* [react-editor-js](https://github.com/Jungwoo-An/react-editor-js) — the unofficial editor-js component for React
* [@stfy/react-editor.js](https://github.com/stfy/react-editor.js) — React wrapper component for Editor.js
* [editorjs-blocks-react-renderer](https://github.com/moveyourdigital/editorjs-blocks-react-renderer) - React component to render blocks to semantic HTML5 tags
* [editorjs-react](https://github.com/etozhealkhipce/editorjs-react) — Editor.js React parser to parse Editor.js data to JSX components
* [editorjs-react-parser](https://github.com/cevinw/editorjs-react-parser) - Parse Editor.js data to semantic html tags with syntax highlighting and [@calumk/editorjs-columns](https://github.com/calumk/editorjs-columns) support
* [editorjs-antd-renderer](https://github.com/gosvoh/editorjs-antd-renderer) — Render Editor.js data to React [Ant Design](https://github.com/ant-design/ant-design) components

#### React Native

* [editorjs-viewer-native](https://github.com/Hidekih/editorjs-viewer-native) — A React Native solution to parse outputData generated by Editor.Js
* [editorjs-renderer-react-native](https://www.npmjs.com/package/@biblebytes/editorjs-renderer-react-native) — A React Native renderer for EditorJS JSON

#### Angular

* [@tinynodes/ngx-editorjs](https://www.npmjs.com/package/@tinynodes/ngx-editorjs) — This library provides Angular support for EditorJS.

#### Svelte

* [sveditorjs](https://github.com/pouchcms/sveditorjs) — This library provides svelte support for EditorJS.

### PHP

* [editorjs-php](https://github.com/editor-js/editorjs-php) — server-side data validation, HTML sanitization and convertation output JSON to the Block objects
* [orchid-editorjs-field](https://github.com/AlexSabur/orchid-editorjs-field)
* [yii2-editorjs-widget](https://github.com/zakurdaev/yii2-editorjs-widget) — Editor.js widget for Yii 2
* [EditorjsBundle](https://github.com/tbmatuka/EditorjsBundle) — Symfony bundle for Editor.js
* [nova-editor-js](https://github.com/advoor/nova-editor-js) — Editor JS field for Laravel Nova
* [codex-to-html](https://github.com/Archakov06/codex-to-html) — Converter EditorJS JSON to HTML
* [magento2-editorjs](https://github.com/Wamoco/magento2-editorjs) — Editor.js module for Magento 2
* [editorjs-symfony-parser-bundle](https://github.com/SyntaxPhoenix/editorjs-symfony-parser-bundle) — Editor.js-Bundle for Symfony to parse blocks created with Editor.js
* [rahmanramsi/filament-editorjs](https://filamentphp.com/plugins/msuhels-editorjs) - Editor JS for [filamentphp](https://filamentphp.com)
* [bumpcore/editor.php](https://github.com/bumpcore/editor.php) - An advanced library for parsing and manipulating Editor.js output using either vanilla PHP or Laravel.
* [editorjs-simple-html-parser](https://github.com/Edd-G/editorjs-simple-html-parser) - 2 way parser for Editor.js: JSON to HTML & HTML to JSON
* [UX Editor](https://github.com/pentiminax/ux-editor) - Editor.js integration for Symfony

### Python

* [django-editorjs-fields](https://github.com/2ik/django-editorjs-fields) — Editor.js integration for Django
* [pyEditorJS](https://github.com/SKevo18/pyEditorJS) - A very simple Editor.js parser written in pure Python

### Ruby

* [editor_js](https://rubygems.org/gems/editor_js) — it validates, parses, and renders content from editorjs
* [render_editorjs](https://github.com/ceritium/render_editorjs) — A modular and customizable Ruby renderer for Editor.js

### Go

* [micheleriva/editorjs-go](https://github.com/micheleriva/editorjs-go) — Fast markdown/HTML generator for Editor.js
* [davidscottmills/goeditorjs](https://github.com/davidscottmills/goeditorjs) - An extensible HTML/markdown generator for editorjs.
* [rodrigoodhin/go-editorjs-parser](https://gitlab.com/rodrigoodhin/go-editorjs-parser) — A Golang library which converts Editor.js JSON output to pure Markdown or HTML.

### Swift

* [editor.js-kit-ios](https://github.com/Upstarts/editor.js-kit-ios) - iOS framework for parsing and rendering blocks

### Kotlin

* [editor.js-kit-android](https://github.com/Upstarts/editor.js-kit-android) - Android framework for parsing and rendering blocks

### Plugins for CMS

* [Front Editor](https://wpfronteditor.com/) - Front Editor plugin for [WordPress](https://wordpress.com)
* [EditorJS](https://octobercms.com/plugin/reazzon-editor) - Backend formwidget for [OctoberCMS](https://octobercms.com)
* [Strapi-EditorJS](https://github.com/melishev/strapi-plugin-react-editorjs) - Replace [Strapi](https://strapi.io) default WYSIWYG editor with Editor.js.
* [Admin Block Editor](https://pushword.piedweb.com/extension/admin-block-editor) - Admin plugin for [Pushword CMS](https://pushword.piedweb.com) (based on symfony)
* [Editor.js - Directus Extension](https://github.com/dimitrov-adrian/directus-extension-editorjs-interface) - Add an Editor.js interface to [Directus](https://github.com/directus/directus)
* [Cotonti CMF Editor.js plugin](https://github.com/Edd-G/cot-editorjs) - Content editor plugin for [Cotonti CMF](https://www.cotonti.com)

## Tutorials and sources

* [editorjs.io](https://editorjs.io) — offical docs
* [Tutorial: Integrating Editor.js into your react application](https://www.walkthrough.so/pblc/snKICMzxzedr/codelab-integrating-editor-js-into-your-react-application)
* [Tutorial: Creating a custom editorjs block tool with React](https://www.walkthrough.so/pblc/QCawSCKwOQLn/creating-a-custom-editorjs-block-tool-with-react)
* [editorjs-examples](https://github.com/hata6502/editorjs-examples) — Examples of using Editor.js

## Projects Using Editor.js

👉 [Add your project!](https://github.com/editor-js/awesome-editorjs/edit/master/readme.md)

* [Newsletter.page](https://newsletter.page) -  A platform for sending email newsletters
* [IrenSystem](https://irensystem.ru) -  System for business - allows you to work with clients, managers, contractors and suppliers
* [beemy](https://www.writebeemy.com/) - Dedicated blog builder to better manage content
* [Notice.studio](https://notice.studio) - CMS & component editor that blends in your website
* [Poda](https://poda.io) — Project planning and roadmaping
* [Slid](https://slid.cc) - Video note-taking tool for online learners.
* [Unicorn Platform](https://unicornplatform.com/) - Create landing pages and write blogs.
* [MarsX](https://www.marsx.dev/) - AI/NoCode/ProCode builder.
* [Walkthrough](http://walkthrough.so/) - Write great codelab style tutorials.
* [Drafts](https://drafts.surge.sh/) - Web based text editor for writing quick drafts
* [Cai](https://cai.so) - AI Writer, Content Generator & Writing Assistant
* [Chronopin](https://chronopin.com) - Track the release dates of your favorite games and interests. Also share, review, and comment on your posts with a like-minded community.
* [Contractify](https://contractify.io) - Contract management software for e-signing, managing and automating all your contracts online
* [Tulsk](https://tulsk.io) - AI-powered project management tool designed to simplify your workflow.
* [WebResearcherJS](https://github.com/kvgc/WebResearcherJS-extension) -  Firefox extension which allows users to take notes on webpages
* [The Work Docs](https://www.theworkdocs.com/) -  AI PDF Reader - allows you to read, write, research long PDF file

### Open source projects

* [frappeframework.com](https://frappeframework.com/docs/v14/user/en/desk/workspace/customization#customizing-workspace-page) - A meta data based framework which has workspace feature which uses Editor.js 
* [automad.org](https://automad.org) — a flat-file content management system and template engine
* [CodeX Docs](https://github.com/codex-team/codex.docs) — documentation engine
* [CodeX Media](https://github.com/codex-team/codex.media) — platform for building modern website for educational or media organizations
* [CodeX Notes](https://github.com/codex-team/codex.notes) — crossplatform desktop notes application based on Electron and Editor.js
* [Noter](https://noter.sambitsahoo.com) - A State of the Art realtime and collaborative note taking platform
* [enassi](https://github.com/enassi/enassi) - Encryption assistant that encrypts and stores your notes and files.
* [EvaNotebook](https://notebook.sanchezcarlosjr.com/) - A collaborative peer-to-peer notebook for Web Technologies

<!--
### Apps/Websites
-->

[Back to top](#contents)
