# gctlctx

![Latest GitHub release](https://img.shields.io/github/release/KeisukeYamashita/gclctx.svg)
![Proudly written in Bash](https://img.shields.io/badge/written%20in-bash-ff69b4.svg)

> Fast gcloud account switcher

## Installation

```console
# It depends on fzf
$ brew install fzf

$ brew install KeisukeYamashita/tap/gclctx
```

## Tips

Add this alias!

```bash
alias gx="gctlctx"
```

## Usage

### Select an account and switch

```console
$ gctlctx
```

### Switch to an account

```console
$ gctlctx my-account-2
```

### Switch back to the latest acocunt

```console
$ gctlctx -
```

## License

Copyright 2022 ~ KeisukeYamashita, Inc.

Licensed under the MIT License.
