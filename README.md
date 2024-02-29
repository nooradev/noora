# Noora

<img alt="GitHub License" src="https://img.shields.io/github/license/nooradev/noora">
<img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues/nooradev/noora">
<img alt="GitHub Issues or Pull Requests" src="https://img.shields.io/github/issues-pr/nooradev/noora">
<img alt="GitHub Downloads (all assets, all releases)" src="https://img.shields.io/github/downloads/nooradev/noora/total">
<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/nooradev/noora">
<img alt="Discord" src="https://img.shields.io/discord/1210935766985867274">
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/nooradev/noora">

Noora is a UI compiler for the web.
It's platform and language agnostic, and it's designed to be used with any web framework.
It builds on modern paradigms and concepts such as Web Components, scoped CSS, and state-driven UI.
Think of it as [Svelte](https://svelte.dev/), but dropping the JavaScript dependency in development.

> [!IMPORTANT]  
> The project is being worked on and is not ready for production use.

## Development

This repository is a monorepo that contains all the [packages](./packages) that make up Noora. The core of the project is a Rust-powered compiler and a CLI, upon which bindings for different languages and platforms are built. Bindings are key in making integrating Noora with different frameworks and platforms as seamless as possible.

### Set up

1. Clone the repository: `https://github.com/nooradev/noora.git`
2. Install and activate system dependencies through [Mise](https://mise.jdx.dev/): `mise install`
3. Set up your environment to work with the project: `mise run up`.
4. You are ready to work on any of the projects under [`/packages`](./packages)

> [!IMPORTANT]  
> Using [Mise](https://mise.jdx.dev/) to activate versions is a strict requirement to ensure all environments are consistent and reproducible. Not using it might lead to wasted time and effort.