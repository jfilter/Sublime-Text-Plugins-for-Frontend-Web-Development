# Sublime Text 3 Plugins for Frontend Web Development

Here is a collection of plugins I use for my daily frontend web development work. I am grateful for any feedback or recommendations. Just open an issue! 😉👌

## Plugins

### Administrative
These plugins are kind of 'meta' because they are not concerned with writing code.

* [Package Control](https://packagecontrol.io/packages/Package%20Control): The essential package manager.
* [AdvancedNewFile](https://packagecontrol.io/packages/AdvancedNewFile): A better way to create new files. For instance, it automatically creates a folder when needed.
* [SideBarEnhacements](https://packagecontrol.io/packages/SideBarEnhancements): Adds features such as renaming to the sidebar.
* [A File Icon](https://packagecontrol.io/packages/A%20File%20Icon): Add icons to the files in the sidebar.
* [TodoReview](https://packagecontrol.io/packages/TodoReview): Scans files for 'TODO's and more.
* [FindKeyConflicts](https://packagecontrol.io/packages/FindKeyConflicts): Key conflicts are inevitably when you use a lot of plugins.
* [Editor Config](https://packagecontrol.io/packages/EditorConfig): Maintain consistent coding styles between different editors.

### General
Usefull for all languaes.

* [All Complete](https://packagecontrol.io/packages/All%20Autocomplete): Indexes all open files for auto-completion.
* [BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter): Improves the already builtin highlighting.
* [GitGutter](https://packagecontrol.io/packages/GitGutter): Displays  changes in the gutter (left to the line numbers).
* [DashDoc](https://packagecontrol.io/packages/DashDoc): Open curent selection in [Dash](https://kapeli.com/dash) on hot key.
* [Terminal](https://packagecontrol.io/packages/Terminal):Open Terminal with current working directory set to the directory of the open file on hot key.
* [Local History](https://packagecontrol.io/packages/Local%20History): Keep a local history of your files. Even though I use git on almost every project, I still don't commit every change. It gives a better feeling to have the possibility to go back to every change.

### Linter
Linters help you to spot mistakes in your code early on. In order to make them work properly, check the instructions in the packages. For some, you have to install other tools.

* [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)
* [SublimeLinter-HTML-tidy](https://packagecontrol.io/packages/SublimeLinter-html-tidy)
* [SublimeLinter-CSSlint](https://packagecontrol.io/packages/SublimeLinter-csslint)
* [SublimeLinter-contrib-SCSS-lint](https://packagecontrol.io/packages/SublimeLinter-contrib-scss-lint)
* [SublimeLinter-contrib-ESLint](https://packagecontrol.io/packages/SublimeLinter-contrib-eslint)
* [SublimeLinter-JSON](https://packagecontrol.io/packages/SublimeLinter-json)


### Javascript
* [Tern for Sublime](https://packagecontrol.io/packages/tern_for_sublime): Static Javascript code analyzer with auto-completion, function argument hints, 'go to definition' and more. The installation and configuration can be a little bit tricky but it's worth it. Choose Tern over [SublimeCodeIntel](https://packagecontrol.io/packages/SublimeCodeIntel) (unmaintained) and [JavaScript Completions](https://packagecontrol.io/packages/JavaScript%20Completions) (buggy). 

* [JavaScript & NodeJS Snippets](https://packagecontrol.io/packages/JavaScript%20%26%20NodeJS%20Snippets)
* [Babel](https://packagecontrol.io/packages/Babel): Syntax definitions for ES6 JavaScript with React JSX extensions.
* [TypeScript](https://packagecontrol.io/packages/TypeScript)
* [Console Wrap](https://packagecontrol.io/packages/Console%20Wrap): Fast way to log to console.

### HTML & CSS
* [Sass](https://packagecontrol.io/packages/Sass): Sass is extending CSS
* [Emmet](https://packagecontrol.io/packages/Emmet): Allows you to write HTML very fast. You have to learn their way though.
* [Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter)

### Other
* [Markdown Preview](https://packagecontrol.io/packages/Markdown%20Preview)


## Remove Duplicates from Auto-completion

As you may have noticed, I make use of a lot of plugins for auto-completion. I prefer to have too many suggestions than too few. But with this setup, you sometimes get duplicates in your completion suggestions. But here is a way to fix it (thanks to [Keith Hall](http://stackoverflow.com/questions/43320798/sublime-text-3-duplicates-autocompletion)):

1. Open the folder where Sublime Text is installed
2. Find `def on_query_completions`
3. Replace `return (completions, flags)` with `return (list(set(completions)), flags)`
4. Save & restart

You have to repeat this every time you update Sublime Text.

## Settings
```
{
    "auto_complete_commit_on_tab": true,
    "auto_complete_delay": 0,
    "color_scheme": "Packages/User/SublimeLinter/Solarized (Light) (SL).tmTheme",
    "create_window_at_startup": false,
    "draw_white_space": "all",
    "ensure_newline_at_eof_on_save": true,
    "font_face": "Input Sans Narrow",
    "font_size": 15,
    "highlight_line": true,
    "ignored_packages":
    [
        "Vintage"
    ],
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
    "spell_check": true,
    "tab_size": 2,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": true
}
```



