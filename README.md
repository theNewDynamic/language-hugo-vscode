# language-hugo README

Syntax highlighting and snippets for [Hugo](https://gohugo.io/) websites.

## Features

Makes Hugo templating fit in with the rest of your HTML.

Includes completion snippets for Hugo functions like `range`, `if`, `with` as well as `variable` and the list will grow.

Includes snippets for Hugo Shortcodes in Markdown and TOML files.

## Known Issues

For Hugo Shortcode snippets to work in your Markdown files, enable `quickSuggestions` in your User Settings

```json
"[markdown]": {
  "editor.quickSuggestions": true
}
```

## Release Notes

See the [Changelog](https://github.com/budparr/language-hugo-vscode/blob/master/CHANGELOG.md)

## Roadmap

- Add Hugo logo to VSCode Marketplace (waiting for copyright holder approval)
- More Snippets/Completions
- Add syntax highlighting for shortcodes in markdown files.
- Add support for Hugo syntax highlighting in JSON files

## Ackknowledgments

Thank you to [Matt Stratton](https://github.com/mattstratton/) for creating the [Atom Language-hugo](https://github.com/mattstratton/language-hugo) plugin, from which this borrows heavily.

Thank you to [Steve Francia](https://github.com/spf13/), [Bjørn Erik](https://github.com/bep) and the [Hugo](https://gohugo.io/) community of contributors and users.