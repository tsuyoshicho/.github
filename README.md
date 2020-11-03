# .github

GitHub global config for:

- CODE_OF_CONTRUCT

see: https://docs.github.com/ja/free-pro-team@latest/github/building-a-strong-community/creating-a-default-community-health-file

## template

Use all repogitory, at create base.
[tsuyoshicho/all-repository-base-template](https://github.com/tsuyoshicho/all-repository-base-template)

include below:

- `.gitattributes` / `.gitignore` (genereate from https://www.toptal.com/developers/gitignore/)
- application config in `.github`
- release workflow in `.github/workflows`
- semver update workflow in `.github/workflows`

## renovate

Default config include.
and see: [tsuyoshicho/renovate-config](https://github.com/tsuyoshicho/renovate-config)

- label renovate - renovate update / #313cb7

All repogitories are disabled, select enabled.

## Weekly Digest

Default config include.
and see: [GitHub Apps - Weekly Digest](https://github.com/apps/weekly-digest)

- label weekly-digest - (none) / #9C27B0

All repogitories are disabled, select enabled.

## auto-assign-issues

Default config include.
and see: [GitHub Apps - auto-assign-issues](https://github.com/apps/auto-assign-issues)

All repogitories are enabled.

## GitHub Action : bump

Using release / semver update.

auto-gen PR and vesion bump up label
see: [haya14busa/action-bumpr](https://github.com/haya14busa/action-bumpr)

- label bump:major - Bump up major version / #ff0000
- label bump:minor - Bump up minor version / #AA3300
- label bump:patch - Bump up patch version / #53d1a5
