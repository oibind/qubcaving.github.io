FROM            jekyll/jekyll
EXPOSE          4000

COPY            Gemfile* /tmp/
WORKDIR         /tmp
RUN             bundle install

COPY            . /app
WORKDIR         /app

CMD             ["jekyll", "serve", "0.0.0.0"]
