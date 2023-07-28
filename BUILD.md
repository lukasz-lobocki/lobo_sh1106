# lobo_sh1106

## Typical build workflow

```bash
git add --update
```

```bash
git commit -m "fix: change"
```

```bash
poetry run semantic-release version
```

:no_entry: There is **no need** for separate `git push`. It is done by `semantic-release`.

## Cookiecutter initiation

```bash
cookiecutter \
  ssh://git@github.com/lukasz-lobocki/py-pkgs-cookiecutter.git \
  package_name="lobo_sh1106"
```

### was run with following variables

- package_name: **`lobo_sh1106`**;
package_short_description: `Driver for the SH1106 display.`

- package_version: `0.2.2`; python_version: `3.10`

- author_name: `Lukasz Lobocki`;
open_source_license: `CC0 v1.0 Universal`

- __package_slug: `lobo_sh1106`; include_github_actions: `no`

### on

`2023-07-28 11:50:17 +0200`
