FROM ruby:2.2-slim

MAINTAINER Matthias Nüßler <m.nuessler@web.de>

RUN gem install riemann-dash
COPY config.rb /
ENTRYPOINT ["riemann-dash", "/config.rb"]
