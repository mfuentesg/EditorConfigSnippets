# EditorConfigSnippets

[EditorConfigSnippets](https://github.com/mfuentesg/EditorConfigSnippets) is a set of snippets for `.editorconfig` files.

## Installation

It is recommended install [EditorConfig](https://packagecontrol.io/packages/EditorConfig).

### With Package Control

To install this plugin you can use [Package Control](https://packagecontrol.io) and looks for [EditorConfigSnippets](https://packagecontrol.io/packages/EditorConfigSnippets).

### With Git

Clone this repository to Packages folder

```bash
cd /path/to/Packages
git clone https://github.com/mfuentesg/EditorConfigSnippets
```

## Snippets Available:

The snippets are independent, so each has similar properties. Each snippet works on the `.editorconfig` scope, and you can call it using the following triggers.

- **editor-base**
- **editor-bash**
- **editor-c**
- **editor-cpp**
- **editor-frontend**
- **editor-go**
- **editor-javascript**
- **editor-md**
- **editor-php**
- **editor-python**
- **editor-ruby**
- **editor-txt**

## My recommended Settings

```ini
root = true

[*]
max_line_length = 100
end_of_line = lf
indent_style = space
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[*.sh]
indent_size = 2

[*.html]
indent_size = 2

[*.{js,json}]
indent_size = 2

[*.{css,styl,scss,less,sass}]
indent_size = 2

[*.php]
indent_size = 4

[*.rb]
indent_size = 2

[*.py]
indent_size = 4

[*.txt]
indent_size = 4

[*.{c,cpp}]
indent_size = 4
trim_trailing_whitespace = false
insert_final_newline = false

[*.go]
indent_size = 2
indent_style = tab

[*.md]
trim_trailing_whitespace = false
indent_style = tab

```

## Contributions

You are welcome to generates a PR with your favorite guidelines.
