# node-nix-env

Created as an example of using nix-shell for dev environments.

## Requirements

- [nix](https://nixos.org/download.html)

## Benefits

- Reproducible dev environments without having to install dependencies on your system.
- An alternative to use docker dev containers which can have reduced performance and impact battery life.

## Usage

The environment config is contained in `shell.nix`. 

To start the environment run `nix-shell`. This will build the environment and switch your shell to nix. From here you can run `npm run start` to test it is working.