# ARCHLINUX IMAGE
FROM archlinux/base

# BASE PACKAGE
RUN pacman -Sy && \
    pacman -S --noconfirm \
    gcc \
    cmake \
    make \
    valgrind \
    python \
    ruby \
    nano

# DEFAULT WORKING DIRECTORY
WORKDIR /code

ENTRYPOINT /bin/bash
