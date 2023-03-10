FROM ubuntu:22.04

LABEL author="Andrea" 
LABEL email="andreascorsoglio@arizona.edu"
LABEL version="v1.0"
LABEL description="Mooo"
LABEL date_created="2022-05-13"

# ARG gets sent to the container at build time (for when you need the installation to be non-interactive)
ARG DEBIAN_FRONTEND=noninteractive 

RUN apt-get update && apt-get install -y fortune cowsay lolcat

# set environment variables
ENV PATH=/usr/games:${PATH}

# set locale
ENV LC_ALL=C

# fortune | cowsay | lolcat

ENTRYPOINT /bin/bash 