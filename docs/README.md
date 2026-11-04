# Documentation

This directory contains the source of the RuyiSBI documentation site.
It is built with mdBook 0.5.2.

From the repository root, build the site or serve a local preview:

```sh
mdbook build docs
mdbook serve docs
```

The generated site is written to `docs/build/`. GitHub Actions builds and
publishes the site to GitHub Pages when `main` changes.
