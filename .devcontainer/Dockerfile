FROM mcr.microsoft.com/devcontainers/python:3.10

RUN apt-get update && apt-get install -y --no-install-recommends \
    libgl1 \
    libglx-mesa0 \
    libegl1 \
    libxrender1 \
    libxext6 \
    graphviz \
    tree \
    git-lfs \
    && rm -rf /var/lib/apt/lists/*

USER vscode

RUN pip install --no-cache-dir --upgrade pip