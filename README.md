SpreeEpaydk
===========

Adds support for epay.dk paymentgateway through the ActiveMerchant gem.

Installation
------------

Add spree_epaydk to your Gemfile:

```ruby
gem 'spree_epaydk'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_epaydk:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

Copyright (c) 2014 Traels, released under the New BSD License
