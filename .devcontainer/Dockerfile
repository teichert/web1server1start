FROM ruby:latest
# RUN echo "gem: --no-ri --no-rdoc" > ~/.gemrc \
  # && yes | gem update --system
RUN apt update && apt install build-essential
RUN yes | gem update --system
RUN yes | gem install \
  bundler \
  jekyll:3.8.5 \
  github-pages \
  minitest

