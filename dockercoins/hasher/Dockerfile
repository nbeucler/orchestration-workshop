FROM armhf/ruby:alpine
RUN apt-get install build-base
RUN gem install sinatra
RUN gem install thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80
