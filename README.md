# Neat repo

This repository is a [Neat](https://github.com/olivr-com/neat) template. It is meant to be used to improve the quality of your open source repos.

> 🔥 This is the version with emojis. For the non-emoji version, check out the [master branch](https://github.com/olivr-templates/neat-repo/tree/master)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Content](#content)
- [Template usage](#template-usage)
  - [For a new repo](#for-a-new-repo)
  - [For an existing repo](#for-an-existing-repo)
  - [As your new personalized template](#as-your-new-personalized-template)
  - [Composability](#composability)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Content

- [Readme](README.tpl.md) ready to be customized and with an auto-updated table of content
- [Bugs](.github/ISSUE_TEMPLATE/Bug.md) and [Features](.github/ISSUE_TEMPLATE/Feature.md) issue templates
- [Pull request](.github/pull_request_template.md) template
- [Security policy](docs/SECURITY.md)
- [Code of conduct](docs/CODE_OF_CONDUCT.md) and [Contributing](docs/CONTRIBUTING.md) guidelines
- A default permissive [license](LICENSE) (Apache 2.0) so you never forget to include a license again
- [Support](docs/SUPPORT.md) template ready to be customized and a [direct link](.github/ISSUE_TEMPLATE/config.yml) to your support URL when opening an issue \*

_\* By default this template requests users of your repo not to create support questions in the issues tab. If you want to change this, you should edit the files [docs/SUPPORT.md](docs/SUPPORT.md) and [.github/ISSUE_TEMPLATE/config.yml](.github/ISSUE_TEMPLATE/config.yml)_

## Template usage

Install [Neat](https://github.com/olivr-com/neat) `npm i -g neat` or you can run it directly through `npx`

### For a new repo

Just add a folder at the end of the command. For example:

```sh
neat repo@emoji my-project
```

### For an existing repo

Neat will not overwrite any files in your folder unless you tell it to do so with the `--force` option

In your repo folder, run:

```sh
neat repo@emoji
```

Or if you prefer the version without emojis

```sh
neat repo
```

### As your new personalized template

Fork this template, customize it to your needs.

Then use Neat as described above and use the path to your forked repo instead.

### Composability

Neat is composable, meaning you can compose a repo from several templates by just running the neat command several times.
Check out other [neat templates](https://github.com/search?q=topic%3Aneat-template&type=Repositories).
