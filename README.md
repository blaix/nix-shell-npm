# Nix Shell Template for NPM Projects

This is a template for an isolated [nix shell](https://nixos.wiki/wiki/Development_environment_with_nix-shell)
that automatically loads with [direnv](https://direnv.net/)
with npm available.

## Requirements

* [nix](https://nix.dev/install-nix.html)
* [direnv](https://direnv.net/)
* Optional but highly recommended: [nix-direnv](https://github.com/nix-community/nix-direnv)

## Usage

1. Copy this repo. E.g. with [degit](https://github.com/Rich-Harris/degit):
  `degit blaix/nix-shell-npm my-npm-project`
2. `cd my-npm-project`
3. `direnv allow`
4. `npx whatever` 🎉
