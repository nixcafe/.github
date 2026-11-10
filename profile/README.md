<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nixcafe/nixcafe-docs/main/apps/landing/public/logo-dark.svg">
    <img alt="nixcafe" src="https://raw.githubusercontent.com/nixcafe/nixcafe-docs/main/apps/landing/public/logo.svg" width="120">
  </picture>
</p>

<h1 align="center">nixcafe</h1>

<p align="center">
  Nix tooling: a flake framework, project templates, and NixOS modules.
</p>

<p align="center">
  <a href="https://nixcafe.org"><img src="https://img.shields.io/badge/nixcafe.org-888888?style=flat-square" alt="Website"></a>
  <a href="https://github.com/nixcafe"><img src="https://img.shields.io/badge/github-@nixcafe-888888?style=flat-square&logo=github" alt="GitHub"></a>
</p>

---

### Projects

| Project | Description | Docs |
| --- | --- | --- |
| **[purr](https://github.com/nixcafe/purr)** | Nix flake framework that builds outputs from the project directory layout | [purr.nixcafe.org](https://purr.nixcafe.org) |
| **[develop-templates](https://github.com/nixcafe/develop-templates)** | Nix flake templates for development environments, for example `nix flake init -t beans#node` | [templates.nixcafe.org](https://templates.nixcafe.org) |
| **[cattery](https://github.com/nixcafe/cattery-modules)** | Nix modules for NixOS, nix-darwin, and home-manager, grouped into rooms | [cattery.nixcafe.org](https://cattery.nixcafe.org) |
| **[nixcafe-docs](https://github.com/nixcafe/nixcafe-docs)** | Documentation monorepo for nixcafe.org and the project documentation sites | [nixcafe.org](https://nixcafe.org) |

### How the projects relate

purr reads a project directory and creates flake outputs from it, such as modules, packages, shells, and systems. The develop-templates repository uses purr to build its own flake, and its templates set up a development shell for a language or a NixOS configuration.

cattery provides NixOS, nix-darwin, and home-manager modules. Rooms group several modules so that one option can enable a larger set of defaults.

nixcafe-docs contains the source for nixcafe.org and the documentation sites linked above. It is a Bun workspace built with Vocs.

---

<p align="center">
  <sub>Built with Nix · Project repositories use CC0-1.0 · <a href="https://nixcafe.org">nixcafe.org</a></sub>
</p>
