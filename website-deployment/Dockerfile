FROM ubuntu:latest

RUN apt-get update && apt-get upgrade
RUN apt-get install -y make bash curl ssh git unzip jq npm rsync coreutils golang
RUN git config --global --add safe.directory '*'
CMD ["/bin/bash"]