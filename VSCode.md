# VSCode

## 1. extensions list

code --install-extension Hridoy.rails-snippets
code --install-extension aeschli.vscode-css-formatter
code --install-extension AlanWalk.markdown-toc
code --install-extension castwide.solargraph
code --install-extension DavidAnson.vscode-markdownlint
code --install-extension dbaeumer.vscode-eslint
code --install-extension donjayamanne.githistory
code --install-extension eamodio.gitlens
code --install-extension emmanuelbeziat.vscode-great-icons
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.code-runner
code --install-extension HookyQR.beautify
code --install-extension infeng.vscode-react-typescript
code --install-extension joffreykern.markdown-toc
code --install-extension joshpeng.sublime-babel-vscode
code --install-extension lonefy.vscode-JS-CSS-HTML-formatter
code --install-extension marp-team.marp-vscode
code --install-extension mgmcdermott.vscode-language-babel
code --install-extension misogi.ruby-rubocop
code --install-extension mrmlnc.vscode-autoprefixer
code --install-extension MS-CEINTL.vscode-language-pack-zh-hans
code --install-extension ms-vscode.sublime-keybindings
code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension rebornix.ruby
code --install-extension redhat.java
code --install-extension sainoba.px-to-rem
code --install-extension shinnn.stylelint
code --install-extension sporiley.css-auto-prefix
code --install-extension spywhere.guides
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension vmsynkov.colonize
code --install-extension vscjava.vscode-java-debug
code --install-extension vscjava.vscode-java-dependency
code --install-extension vscjava.vscode-java-pack
code --install-extension vscjava.vscode-java-test
code --install-extension vscjava.vscode-maven
code --install-extension wibblemonkey.markdown-auto-toc
code --install-extension xabikos.JavaScriptSnippets
code --install-extension xabikos.ReactSnippets

## 2. Settings

```json
{
    "workbench.colorTheme": "Solarized Dark",
    "editor.tabSize": 2,
    "editor.fontSize": 14,
    "editor.rulers": [
        80
    ],
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
    "editor.find.autoFindInSelection": true,
    "window.openFilesInNewWindow": "off",
    "workbench.editor.enablePreview": true,
    "editor.mouseWheelScrollSensitivity": 1.2,
    "window.title": "${activeEditorMedium}${separator}${rootName}",
    "editor.formatOnPaste": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.renderIndentGuides": false,
    "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?",
    "editor.renderWhitespace": "all",
    "diffEditor.ignoreTrimWhitespace": false,
    "autoprefixer.formatOnSave": false,
    "autoprefixer.findExternalAutoprefixer": false,
    "autoprefixer.browsers": [
        "Safari >= 8",
        "Firefox >= 21",
        "Chrome >= 23",
        "IE >= 9",
        "Opera >= 15",
        "last 2 versions"
    ],
    "window.zoomLevel": 0,
    "git.autofetch": true,
    "gitlens.views.fileHistory.enabled": true,
    "gitlens.views.lineHistory.enabled": true,
    "workbench.editor.highlightModifiedTabs": true,
    "px-to-rem.px-per-rem": 75,
    "files.trimTrailingWhitespace": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "tslint.configFile": "./tslint.json",
    "tslint.jsEnable": true,
    "prettier.tslintIntegration": true,
    "prettier.arrowParens": "always",
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "typescript.updateImportsOnFileMove.enabled": "never",
    "ruby.format": "standard",
    "markdown.extension.showExplorer": true,
    "markdown.extension.toc.githubCompatibility": true,
    "files.eol": "\n",
    "markdown-toc.depthFrom": 2,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "prettier.trailingComma": "all",
    "markdown.marp.exportType": "pptx"
}
```
