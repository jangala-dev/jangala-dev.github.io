FROM ruby:bullseye

RUN apt-get update -qq && apt-get install -y build-essential ruby-dev zlib1g-dev liblzma-dev

# Optionally set up Node.js for JavaScript runtime (for Jekyll 4 and earlier)
# RUN curl -sL https://deb.nodesource.com/setup_14.x | bash -
# RUN apt-get install -y nodejs

# Create app directory
WORKDIR /app

# Copy your project into the container
COPY ./docs/. /app

# Install Jekyll and Bundler
RUN gem install jekyll bundler

# Install gems
RUN bundle install

# Expose the port server will run on
EXPOSE 4000

# Run Jekyll
CMD ["bundle", "exec", "jekyll", "serve", "--host=0.0.0.0"]