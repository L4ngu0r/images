This image use `rust-slim` base image and add :

- wasm target
- cargo-generate

## Build

```
docker build -t rust-wasm .
```

## Run

```
docker run --rm -it rust-wasm <your command>
```