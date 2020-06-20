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

## Setup .gitignore

### New

Use [gitignore.io](http://gitignore.io/) to generate your new `.gitignore` file.

### Edit

Use the edit URL from the `.gitignore` file to edit `.gitignore` settings.

## Setup .gitattributes

Check [gitHub Common.gitattributes](https://github.com/alexkaratarakis/gitattributes/blob/master/Common.gitattributes) when you start you project.

Note: Enforcing Unix newlines with the `.gitattributes` is usually done by a linter and can be added for safety purposes.

## Setup .dockerignore

If you use docker check if you actually require this `.dockerignore`.

Check: [Common examples on gitHub](https://github.com/garygitton/dockerignore)

## Linting

### Prettier-standard

The project [prettier-standard] uses JavaScript [JavaScript Standard Style](standardJS).

[prettier-standard](https://www.npmjs.com/package/prettier-standard)
[JavaScript Standard Style](https://standardjs.com)

### Editors

Every Editor as e.g. VS Code, WebStorm or IntelliJ have plugins.

[WebStorm](https://prettier.io/docs/en/webstorm.html)
[VS Code Plugin](https://marketplace.visualstudio.com/items?itemName=numso.prettier-standard-vscode)
