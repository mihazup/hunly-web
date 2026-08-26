# hunly-web

This repository is a **build-artifact mirror** of [`github.com/mihazup/Hunly`](https://github.com/mihazup/Hunly).

It exists solely because `Hunly` is a private repository, and GitHub Pages requires a public
repository on GitHub Free. This repo contains nothing but the compiled output of
`flutter build web --release --base-href /hunly-web/`, published automatically by a GitHub
Actions workflow in `Hunly` on every push to its `main` branch.

The `main` branch here is served directly by GitHub Pages at
[https://mihazup.github.io/hunly-web/](https://mihazup.github.io/hunly-web/).

**Do not send pull requests here.** There is no source code in this repository, and its history
is not preserved between deploys — each deploy replaces the previous commit. All development
happens in the private `Hunly` repository; file issues and PRs there instead.
