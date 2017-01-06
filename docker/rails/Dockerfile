FROM ruby:2.3.1
RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs qt4-default qt4-qmake xvfb zip unzip gstreamer1.0-plugins-base gstreamer1.0-tools gstreamer1.0-x
RUN mkdir -p /data/app

WORKDIR /data/app
