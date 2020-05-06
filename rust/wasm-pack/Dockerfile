FROM rust:1.43-slim

RUN apt-get update && apt-get install -y \
  curl

RUN curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh

ENTRYPOINT [ "wasm-pack" ]
