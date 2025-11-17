FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Install full LaTeX distribution
RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y \
    texlive-full \
    latexmk \
    ghostscript \
    make \
    && apt-get clean
