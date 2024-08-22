FROM fedora:40
RUN dnf update -y \
    && dnf install git cargo rustup rustfmt rust-analyzer -y
ENV PATH="$PATH:/root/.cargo/bin"