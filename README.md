# Redis stores for I18n

__`redis-i18n`__ provides a Redis backend for __I18n__. See the main [redis-store readme](https://github.com/redis-store/redis-store) for general guidelines.

## Installation

```ruby
# Gemfile
gem 'redis-i18n'
```

## Usage

```ruby
I18n.backend = I18n::Backend::Redis.new
```

## Running tests

```shell
gem install bundler
git clone git://github.com/redis-store/redis-i18n.git
cd redis-i18n
bundle install
bundle exec rake
```

If you are on **Snow Leopard** you have to run `env ARCHFLAGS="-arch x86_64" bundle exec rake`

## Status

[![Gem Version](https://badge.fury.io/rb/redis-i18n.svg)](http://badge.fury.io/rb/redis-i18n) 
[![Build Status](https://secure.travis-ci.org/redis-store/redis-i18n.svg?branch=master)](http://travis-ci.org/redis-store/redis-i18n?branch=master) 
[![Code Climate](https://codeclimate.com/github/redis-store/redis-i18n.svg)](https://codeclimate.com/github/redis-store/redis-i18n)

## Copyright

2009 - 2013 Luca Guidi - [http://lucaguidi.com](http://lucaguidi.com), released under the MIT license
