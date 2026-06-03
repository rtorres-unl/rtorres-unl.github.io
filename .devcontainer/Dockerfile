FROM ruby:3.3

RUN apt-get update && apt-get install -y git build-essential && \
    gem install jekyll bundler && \
    useradd -m -s /bin/bash vscode
    