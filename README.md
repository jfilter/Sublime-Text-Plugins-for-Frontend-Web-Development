
<div align="center">
  <img src="preview.gif" alt="Previews Sublime in use with some of the used plugins.">
</div>

# Sublime Text 3 Plugins for Frontend Web Development

Sublime is great and for many still the best text editor available. But out of the box, it lacks some features that modern competitors have already built-in. Plugins help to stay ahead but it's a hassle to keep up with all of them. In order to help you, I compiled a list of plugins I use for my daily frontend web development. 

If you know plugins that should be on this list, just open an issue. 😉

**What other people said about this list:**

"Useful." – [Smashing Magazine](https://twitter.com/smashingmag/status/857784722373701632)

"✅" – [Umar Hansa](https://twitter.com/umaar/status/855385340105904128)


### Table of Contents

1. [Administrative](#administrative)
2. [General](#general)
3. [Javascript](#javascript)
4. [HTML & CSS](#htmlcss)
5. [Linter](#linter)
6. [Other](#other)
7. [Settings](#settings)

## Plugins

<a name="administrative"/>

### 🗃 Administrative 
These plugins are kind of 'meta' because they are not concerned with writing code.

* [Package Control](https://packagecontrol.io/packages/Package%20Control): This package enables you to install other packages. Since build 3124, you can install it within Sublime via <em>Tools</em> ➡ <em>Install Package Control</em>.
* [AdvancedNewFile](https://packagecontrol.io/packages/AdvancedNewFile): A better way to create new files. For instance, it automatically creates a folder when needed.
* [SideBarEnhacements](https://packagecontrol.io/packages/SideBarEnhancements): Adds features such as renaming to the sidebar.
* [A File Icon](https://packagecontrol.io/packages/A%20File%20Icon): Add icons to the files in the sidebar.
* [ProjectManager](https://packagecontrol.io/packages/ProjectManager): Organizing project files by putting them in a central location.
* [TodoReview](https://packagecontrol.io/packages/TodoReview): Scans files for `TODO`s and more.
* [FindKeyConflicts](https://packagecontrol.io/packages/FindKeyConflicts): Key conflicts are inevitable when you use a lot of plugins.
* [Editor Config](https://packagecontrol.io/packages/EditorConfig): Maintain consistent coding styles between different editors.
* [Sync Settings](https://packagecontrol.io/packages/Sync%20Settings): Keep Sublime settings in sync via Github-Gist.
* [Package Syncing](https://packagecontrol.io/packages/Package%20Syncing): Keep all you settings, packages etc in sync via Dropbox and co
* [SFTP](https://packagecontrol.io/packages/SFTP): Transfer files to a server via FTPS and SFTP. The plugin is like Sublime [Nagware](https://en.wikipedia.org/wiki/Shareware#Nagware). You can use it for free but get a reminder to buy a licence.


<a name="general"/>

### ⌨️ General 
Useful for all languages.

* [All Autocomplete](https://packagecontrol.io/packages/All%20Autocomplete): Indexes all open files for auto-completion.
* [BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter): Improves the already built-in highlighting.
* [Terminal](https://packagecontrol.io/packages/Terminal): Open Terminal with current working directory set to the directory of the open file on a hot key.
* [AlignTab](https://packagecontrol.io/packages/AlignTab): Align your code by `:`, `=`, `=>`, `%`, ` `, `|` or your own RegEx.
* [GitGutter](https://packagecontrol.io/packages/GitGutter): Displays modified lines in the gutter (left to the line numbers).
* [Git](https://packagecontrol.io/packages/Git): Includes some git commands.
* [GitSavvy](https://packagecontrol.io/packages/GitSavvy): Full git and GitHub integration.
* [Gitignore](https://packagecontrol.io/packages/Gitignore): Fetches templates for the .gitignore provided by [Github](https://github.com/github/gitignore).
* [Local History](https://packagecontrol.io/packages/Local%20History): Keep a local history of your files.
* [DashDoc](https://packagecontrol.io/packages/DashDoc): Open current selection in [Dash](https://kapeli.com/dash) on a hot key.
* [Text Pastry](https://packagecontrol.io/packages/Text%20Pastry): Extend the power of multiple selections in Sublime Text 2/3. Modify selections, insert numeric sequences, incremental numbers, generate uuids, date ranges, insert continuously from a word list and more.
* [Super Calculator](https://packagecontrol.io/packages/Super%20Calculator): Sublime Text plugin for performing quick inline calculations with a simple keypress (Alt+C).
* [Open-Include](https://github.com/titoBouzout/Open-Include): Will open file paths found under the cursor with ALT+D.

<a name="javascript"/>

### ☕️ Javascript
* [Tern for Sublime](https://packagecontrol.io/packages/tern_for_sublime): Static Javascript code analyzer with auto-completion, function argument hints, 'go to definition' and more. The installation and configuration can be a little bit tricky but it's worth it. Choose Tern over [SublimeCodeIntel](https://packagecontrol.io/packages/SublimeCodeIntel) (unmaintained) and [JavaScript Completions](https://packagecontrol.io/packages/JavaScript%20Completions) (buggy). 
* [JavaScript & NodeJS Snippets](https://packagecontrol.io/packages/JavaScript%20%26%20NodeJS%20Snippets)
* [JsPrettier](https://packagecontrol.io/packages/JsPrettier): Integration of [Prettier](https://github.com/prettier/prettier), the opinionated JavaScript formatter.
* [Console Wrap](https://packagecontrol.io/packages/Console%20Wrap): Fast way to log to console.
* [Babel](https://packagecontrol.io/packages/Babel): Syntax definitions for ES6 JavaScript with React JSX extensions.
* [TypeScript](https://packagecontrol.io/packages/TypeScript)
* [Elm Language Support](https://packagecontrol.io/packages/Elm%20Language%20Support)
* [Console Wrap](https://packagecontrol.io/packages/Console%20Wrap): This plugin helps you to work easily with log statements, For example hide/remove all the console logs.

<a name="htmlcss"/>

### 🎨 HTML & CSS 
* [Sass](https://packagecontrol.io/packages/Sass): Sass is a preprocessor extending CSS and this plugins adds the language support.
* [SassSolutions](https://packagecontrol.io/packages/SassSolution): Auto-complete for variables and mixins from your 'settings.scss' file.
* [CSS3](https://packagecontrol.io/packages/CSS3): Replaces the built-in CSS support with a more up-to-date one. Includes [cssnext](http://cssnext.io) support. Follow the instructions to make it work properly.
* [Emmet](https://packagecontrol.io/packages/Emmet): Allows you to write HTML very fast. You have to learn their way though.
* [Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter)

<a name="linter"/>

### 🔥 Linter 
Linters help you to spot mistakes in your code early on. In order to make them work properly, check the instructions in the packages. For some, you have to install additional tools.

* [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)
* [SublimeLinter-HTML-tidy](https://packagecontrol.io/packages/SublimeLinter-html-tidy)
* [SublimeLinter-contrib-stylelint](https://packagecontrol.io/packages/SublimeLinter-contrib-stylelint): For CSS. Choose stylelint over [SublimeLinter-CSSlint](https://packagecontrol.io/packages/SublimeLinter-csslint).
* [SublimeLinter-contrib-SCSS-lint](https://packagecontrol.io/packages/SublimeLinter-contrib-scss-lint)
* [SublimeLinter-contrib-ESLint](https://packagecontrol.io/packages/SublimeLinter-contrib-eslint)
* [SublimeLinter-flow](https://packagecontrol.io/packages/SublimeLinter-flow)
* [SublimeLinter-contrib-elm-make](https://packagecontrol.io/packages/SublimeLinter-contrib-elm-make)
* [SublimeLinter-JSON](https://packagecontrol.io/packages/SublimeLinter-json)

<a name="other"/>

### 👥 Other
* [Markdown Preview](https://packagecontrol.io/packages/Markdown%20Preview)
* [Advanced CSV](https://packagecontrol.io/packages/Advanced%20CSV)
* [Solarized Color Scheme](https://packagecontrol.io/packages/Solarized%20Color%20Scheme): The built-in Solarized Theme does not support recent syntax such as ES2015. This one does but it's not the only one. Find a color scheme you please. 😉
* [InstaGoogling](https://packagecontrol.io/packages/InstaGoogling): Instagoogling is the fastest and most efficient way to Google from Sublime Text.

<a name="settings"/>

## Settings
```
{
    // Disallows approving auto-complete suggestions with 'enter' to prevent ambiguous situations.
    // You have to get used to it but also Sublime strongly recommends it.
    "auto_complete_commit_on_tab": true,
    "auto_complete_delay": 0,
    // Allow auto-complete suggestion within snippets.
    "auto_complete_with_fields": true,
    "color_scheme": "Packages/Solarized Color Scheme/Solarized (light).tmTheme",
    "create_window_at_startup": false,
    "draw_white_space": "all",
    "ensure_newline_at_eof_on_save": true,
    "font_face": "Input Sans Narrow",
    "font_size": 15,
    "highlight_line": true,
    "ignored_packages":
    [
        "CSS",
        "Vintage"
    ],
    // Highlights the indentation of the current scope.
    "indent_guide_options":
    [
        "draw_normal",
        "draw_active"
    ],
    "indent_to_bracket": true,
    "rulers":
    [
        80
    ],
    "tab_size": 2,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": true
}

```

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

