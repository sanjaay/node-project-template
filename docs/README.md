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

### Changelog

A changelog should match the following form.
See [keepachangelog.com].

**When do I add something to the changelog?**
Every commit which contains changes must contain an addition to the changelog.

**When do I change the version?**
The questions is more: When is the code marked as released?
A version is released when a release tag in git is created.

**Note:** Keep the version in your `package.json` aligned.

**Types of changes**

- **Added** for new features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Removed** for now removed features.
- **Fixed** for any bug fixes.
- **Security** in case of vulnerabilities

For reference see: [keepachangelog.com]

Example for a changelog:

```md
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Fixing typos

## [0.0.4] - 2014-08-09

### Added

- Better explanation of the difference between the file ("CHANGELOG")
  and its function "the change log".

### Changed

- Refer to a "change log" instead of a "CHANGELOG" throughout the site
  to differentiate between the file and the purpose of the file — the
  logging of changes.

### Removed

- Remove empty sections from CHANGELOG, they occupy too much space and
  create too much noise in the file. People will have to assume that the
  missing sections were intentionally left out because they contained no
  notable changes.

## [0.0.3] - 2014-08-09

### Added

- "Why should I care?" section mentioning The Changelog podcast.

## [0.0.2] - 2014-07-10

### Added

- Explanation of the recommended reverse chronological release ordering.

## [0.0.1] - 2014-05-31

### Added

- This CHANGELOG file to hopefully serve as an evolving example of a
  standardized open source project CHANGELOG.
- CNAME file to enable GitHub Pages custom domain
- README now contains answers to common questions about CHANGELOGs
- Good examples and basic guidelines, including proper date formatting.
- Counter-examples: "What makes unicorns cry?"
```

[keepachangelog.com]: https://keepachangelog.com/en/1.0.0/
