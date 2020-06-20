# Template Project

Use this project as example project for setup new projects (e.g. linter, .editorconfig etc.)


## Setup .editorconfig

Read more on [editorconfig.org] about the `.editorconfig`

[editorconfig.org]: https://editorconfig.org

### VS Code

Use the [VS Code Plugin]

[vs code plugin]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig

### IntelliJ

1. Got to: `Settings > Editor > Code Style`
2. Tick the checkbox Enable EditorConfig support


## Sample .editorconfig

```
# EditorConfig is awesome: https://EditorConfig.org

# top-most EditorConfig file
root = true

# Unix-style newlines with a newline ending every file
[*]
end_of_line = lf
trim_trailing_whitespace = true
insert_final_newline = true
indent_style = space
indent_size = 2
charset = utf-8

[*.md]
trim_trailing_whitespace = false
```
