FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0.200.0-14@sha256:7ebe524be928e81fa95f5c17f8f343dfa7cf458772c4c27f2fb3d24e32cb49e4

# see https://mcr.microsoft.com/v2/vscode/devcontainers/typescript-node/tags/list for tags
# Add missing Renovate dev tools
RUN DEBIAN_FRONTEND=noninteractive apt-get update \
   && apt-get -y install --no-install-recommends --no-upgrade build-essential \
   && rm -rf /var/lib/apt/lists/*
