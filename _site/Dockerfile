FROM ruby:3.3.5

RUN apt-get update && apt-get install -y build-essential \
    && gem install jekyll bundler

WORKDIR /usr/src/app

CMD ["jekyll", "serve", "--host", "0.0.0.0"]
