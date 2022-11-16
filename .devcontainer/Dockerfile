FROM mcr.microsoft.com/vscode/devcontainers/rust:buster
ENV PATH "~/.cargo/bin:$PATH"
RUN cargo install --git https://github.com/move-language/move move-cli --branch main
RUN cargo install --git https://github.com/move-language/move move-analyzer --branch main
