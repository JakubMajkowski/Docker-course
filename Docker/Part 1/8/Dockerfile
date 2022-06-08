FROM ubuntu:22.04

WORKDIR /usr/src/app

RUN apt update -y
RUN apt upgrade -y
RUN apt install -y curl

COPY plik.sh .
RUN chmod +x plik.sh

CMD ./plik.sh