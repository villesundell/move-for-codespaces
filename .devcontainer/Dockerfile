FROM mcr.microsoft.com/vscode/devcontainers/rust:buster
RUN cargo install --git https://github.com/move-language/move move-cli --branch main
RUN cargo install --git https://github.com/move-language/move move-analyzer --branch main
#RUN cargo install --locked --git https://github.com/MystenLabs/sui.git --branch devnet sui