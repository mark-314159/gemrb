FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Install dependencies
RUN apt-get update && apt-get install -y \
    build-essential \
    cmake \
    g++ \
    clang \
    python3 \
    python3-pip \
    python3-dev \
    libsdl2-dev \
    libsdl2-mixer-dev \
    libfreetype6-dev \
    libpng-dev \
    libz-dev \
    libopenal-dev \
    libopenal1 \
    libsndfile1 \
    libvorbis-dev \
    libogg-dev \
    libglew-dev \
    && apt-get clean

# Set up workspace
WORKDIR /workspace