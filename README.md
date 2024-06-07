# Elixir/Phoenix Example Project

Example project for use with [Jetify Cloud](https://www.jetify.com/cloud) Brief description of framework and language

## How to Use

* Create an account on [Jetify Cloud](https://cloud.jetify.com)
* Fork or clone this repo to your own account
* In the Jetify Dashboard, create a new project, and select the cloned repo from your account

## About this project

### Packages Installed

* Elixir 1.16.3
* Rebar3 3.23.0

### Env Variables

```env
"MIX_HOME": "$PWD/.nix-mix",
"HEX_HOME": "$PWD/.nix-hex",
"ERL_AFLAGS": "-kernel shell_history enabled",
"PORT": "8080"
```

Note that project's config/dev.exs file is configured to use the PORT environment variable.

### Scripts

Install: `cd ./hello && mix deps.get`
Build: `cd ./hello && mix compile`
Start: `cd ./hello && mix phx.server`
