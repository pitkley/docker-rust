FROM pitkley/rust:1.29.2

RUN mkdir -p /rust/app
WORKDIR /rust/app

ONBUILD COPY . /rust/app
ONBUILD RUN cargo build --release

CMD cargo run --release
