# language-hugo README

Syntax highlighting and snippets for HTML files as Hugo templates. Ported and modified from Matt Stratton's excellent [Atom extension](https://github.com/mattstratton/language-hugo).

## Features
Makes Hugo templating fit in with the rest of your HTML.

Includes completion snippets for Hugo functions like `range`, `if`, `with` as well as `variable` and the list will grow. 

Includes snippets for Hugo Shortcodes in Markdown and TOML files.



## Known Issues
For Hugo Shortcode snippets to work in your Markdown files, enable `quickSuggestions` in your User Settings
```
"[markdown]": {
  "editor.quickSuggestions": true
}
```


## Release Notes

### 1.0.0

Initial release

## Roadmap

- More Snippets/Completions
- Add syntax highlighting for shortcodes in markdown files.
- Add support for Hugo syntax highlighting in JSON files
