# compose/dify/code/plugin_daemon/Dockerfile
FROM ghcr.io/langgenius/dify-plugin-daemon:0.0.10

USER root

RUN apt-get update && apt-get install -y --no-install-recommends \
    pkg-config \
    libcairo2 libcairo2-dev \
    libpango1.0-0 libpango1.0-dev \
    libgirepository1.0-dev gir1.2-pango-1.0 \
    libgdk-pixbuf-2.0-0 \
    build-essential python3-dev \
    cmake meson ninja-build \
 && rm -rf /var/lib/apt/lists/*
