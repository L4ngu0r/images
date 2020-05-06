FROM rust:1.43-slim

RUN apt-get update && apt-get install -y \
  perl \
  pkg-config \
  libssl-dev

RUN rustup target add wasm32-unknown-unknown

RUN cargo install cargo-generate

WORKDIR /tmp
