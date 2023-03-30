FROM rust:alpine3.17

RUN rustup toolchain install nightly
RUN rustup default nightly
RUN rustup target add wasm32-unknown-unknown
RUN cargo install cargo-leptos 
