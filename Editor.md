# 我的编辑器首选项配置

## Sublime

- Commend Link
> ln -s /Applications/Sublime Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl

- Extensions
  - Bable
  - BeautifyRuby
  - Color Highlighter
  - CTags
  - Emmet
  - HTML Snippets
  - Javascript Complitions
  - JsFormat
  - LESS
  - Markdown Preview
  - Package Control
  - PyV8
  - React ES6 Snippets
  - ReactJS
  - Sass
  - SCSS
  - SQLTools
  - SublimeLinter-jsxhint

- User settings

```json
{
  "auto_complete": true,
  "auto_find_in_selection": true,
  "auto_match_enabled": true,
  "bold_folder_labels": true,
  "caret_extra_bottom": 2,
  "caret_extra_top": 2,
  "caret_extra_width": 3,
  "caret_style": "phase",
  "color_scheme": "Packages/Color Scheme - Default/Monokai.tmTheme",
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "ignored_packages": ["Markdown", "Vintage"],
  "indent_guide_options": ["draw_normal", "draw_active"],
  "line_padding_bottom": 1,
  "line_padding_top": 1,
  "margin": 2,
  "match_brackets_angle": true,
  "open_files_in_new_window": false,
  "preview_on_click": true,
  "scroll_speed": 1.2,
  "show_encoding": true,
  "show_full_path": true,
  "show_line_endings": true,
  "tab_size": 2,
  "theme": "Default.sublime-theme",
  "translate_tabs_to_spaces": true,
  "use_simple_full_screen": true
}
```

## VSCode

- Commend Link
> ln -s /Applications/Visual Studio Code.app/Contents/Resources/app/bin/code /usr/local/bin/code

- Extensions
  - Babel JavaScript
  - Beautify
  - ESLint
  - GitLens
  - Guides
  - JavaScript(ES6) code snippets
  - Markdown All in One
  - markdownlint
  - Prettier
  - Reactjs code snippets
  - Ruby
  - Ruby on Rails
  - Ruby Solargraph
  - ruby-rubocop
  - Sublime Babel
  - Sublime Text Keymap and Settings Importer
  - VSCode Great Icons

- User settings

```json
{
  "workbench.colorTheme": "Solarized Dark",
  "editor.tabSize": 2,
  "editor.fontSize": 14,
  // execution path of rubocop.
  "ruby.rubocop.executePath": "/Users/mac/.rvm/gems/ruby-2.3.1/bin/",
  // Set individual ruby linters to use
  "ruby.lint": {
    "rubocop": true,
    "ruby": true
  },
  "workbench.iconTheme": "vscode-great-icons",
  "[markdown]": {
    "editor.wordWrap": "on",
    "editor.quickSuggestions": true
  },
  "gitlens.advanced.messages": {
    "suppressFileNotUnderSourceControlWarning": true,
    "suppressShowKeyBindingsNotice": true
  },
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "vue-html": "html",
    "plaintext": "jade"
  },
  "emmet.showExpandedAbbreviation": "inMarkupAndStylesheetFilesOnly",
  "ruby.intellisense": "rubyLocate",
  "editor.find.autoFindInSelection": true,
  "window.openFilesInNewWindow": "off",
  "workbench.editor.enablePreview": true,
  "editor.mouseWheelScrollSensitivity": 1.2,
  "window.title": "${activeEditorFull}${separator}${rootName}",
  "editor.formatOnPaste": true,
  // "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.renderIndentGuides": false
}
```
