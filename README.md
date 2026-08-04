# homebrew-hourglass

A Homebrew tap for **hourglass** — working-hours, absence and Swiss
public-holiday tracking for one person employed in the city of Zürich.

```sh
brew install swissonid/hourglass/hourglass
```

Or tap first, if you prefer:

```sh
brew tap swissonid/hourglass
brew install hourglass
```

Upgrading is `brew upgrade hourglass`, as usual.

## What is here, and what is not

This repository holds **the formula and the binaries, and nothing else**. The
source lives in a private repository; the releases here carry the compiled
artefacts for macOS (Apple silicon and Intel) and Linux x86-64, built by that
repository's release workflow.

`Formula/hourglass.rb` is generated. A hand-edit is overwritten by the next
release — change the workflow that writes it instead.

## Licence

The binaries are distributed under the [Business Source Licence
1.1](https://mariadb.com/bsl11/): usable and modifiable, but only the Licensor
may sell it or offer it as a service. It converts to Apache-2.0 on the change
date named in the `LICENSE` file shipped inside each archive.
