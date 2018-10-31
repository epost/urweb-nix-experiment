# Ur/Web experiment

## Getting Ur/Web via Nix

Get `urweb` using https://github.com/grwlf/urweb-build:

```bash
cd ~/dev/3rdparty
git clone https://github.com/grwlf/urweb-build
export NIX_PATH="$NIX_PATH:urweb-build=/Users/erik/dev/3rdparty/urweb-build"
```

## Build the project

```bash
nix-shell -p urweb
```

From the `nix-shell` do:

```bash
urweb restaurant
./restaurant.exe
```

## Try it out

Open http://localhost:8080/Restaurant/main
