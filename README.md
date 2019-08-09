# language-hugo README

Syntax highlighting and snippets for [Hugo](https://gohugo.io/) websites.

## Features

Makes Hugo templating fit in with the rest of your HTML.

Includes 24 completion snippets for Go Template, see full list below.

Includes snippets for Hugo Shortcodes in Markdown and TOML file, list to come.

## Template Snippets

Snippet | Tab Trigger | Output
--- | --- | ---
Curlies | __x__ | `{{ }}`
Dot | __xx__ | `{{ . }}`
If | __if__ | `{{ if }} {{ end }}`
If Inline | __ifi__ | `Same as above but inline`
If/Else | __ife__ | `{{ if }} {{ else }} {{ end }}`
If/Else if | __ifei__ | `{{ if }} {{ else if }} {{ end }}`
With | __with__ | `{{ with }} {{ end }}`
With/Else | __withe__ | `{{ with }} {{ else }} {{ end }}`
Range | __range__ | `{{ range  }} {{ end }}`
Partial | __partial__ | `{{ partial "" . }}`
partialCached | __partialc__ | `{{ partialCached "" . variant }}`
Naked partial | __xpartial__ | `partial "" .`
Block | __block__ | `{{ block "main" . }} {{ end }}`
Block define | __define__ | `{{ define "block" }} {{ end }}`
Scratch | __scra__ | `{{ .Scratch.Set|Get|Add|SetInMap|Delete|GetSortedMapValues }}`
String | __str__ | `{{ printf "Something about %s" . }}`
printF | __print__ | `printf "%s|%v|%d|%x" .`
Variable | __vars__ | `{{ $var := what }}`
Return | __ret__ | `{{ return $return }}`
Debug | __debug__ | `{{ printf "%#v" . }}`
Error | __error__ | `{{ errorf "%#v" . }}`
Comment | __comm__ | `{{/* */}}`

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

- More Snippets/Completions
- Add syntax highlighting for shortcodes in markdown files.
- Add support for Hugo syntax highlighting in JSON files

## Acknowledgments

Thank you to [Matt Stratton](https://github.com/mattstratton/) for creating the [Atom Language-hugo](https://github.com/mattstratton/language-hugo) plugin, from which this borrows heavily.

Thank you to [Steve Francia](https://github.com/spf13/), [Bjørn Erik](https://github.com/bep) and the [Hugo](https://gohugo.io/) community of contributors and users.
