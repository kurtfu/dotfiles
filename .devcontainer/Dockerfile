FROM debian:bookworm-slim

RUN set -eux; \
        apt update; \
        apt install -y --no-install-recommends \
            build-essential \
            ca-certificates \
            clang \
            clang-format \
            clang-tidy \
            cmake \
            git \
            libboost-all-dev \
            python-is-python3 \
            valgrind \
        ; \
        rm -rf /var/lib/apt/lists/*

WORKDIR /home
