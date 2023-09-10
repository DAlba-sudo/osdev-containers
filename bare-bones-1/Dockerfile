FROM ubuntu:latest

WORKDIR /usr/share/osdev

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y bison flex texinfo libgmp3-dev libmpc-dev
RUN apt-get install -y git
RUN apt-get install -y curl
RUN apt-get install -y zsh

RUN mkdir /usr/share/osdev/src
RUN mkdir /usr/share/osdev/binutils
RUN mkdir /usr/share/osdev/gcc


