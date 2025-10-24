FROM langgenius/dify-plugin-daemon:0.0.10

USER root

RUN apt-get update && apt-get install -y --no-install-recommends \
    pkg-config \
    libcairo2-dev \
    libpango1.0-dev \
    libglib2.0-dev \
    libgirepository1.0-dev \
    gir1.2-pango-1.0 \
    build-essential \
    python3-dev \
    cmake \
 && rm -rf /var/lib/apt/lists/*

USER root
