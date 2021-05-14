FROM ubuntu:20.04

RUN mkdir /src

# add-apt-repositoryをインストールしてteam-gcc-arm-embeddedを追加
RUN apt-get -y update && \
apt install -y gcc-arm-none-eabi make