FROM mysql:8.0.28
# m1チップの場合
# FROM --platform=linux/x86_64 mysql:8.0.28

RUN apt-get update && apt-get install -y locales
RUN sed -i -E 's/# (ja_JP.UTF-8)/\1/' /etc/locale.gen && locale-gen
ENV LANG ja_JP.UTF-8

WORKDIR /playground

