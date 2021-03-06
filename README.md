![Foreman](fogproxmox.png)

# Fog::Proxmox

[![Build Status](https://travis-ci.org/tristanrobert/fog-proxmox.svg?branch=develop)](https://travis-ci.org/tristanrobert/fog-proxmox)
[![Code Climate](https://codeclimate.com/github/tristanrobert/fog-proxmox.svg)](https://codeclimate.com/github/tristanrobert/fog-proxmox)
[![Test Coverage](https://api.codeclimate.com/v1/badges/8e40616906ff67dc51d3/test_coverage)](https://codeclimate.com/github/tristanrobert/fog-proxmox/test_coverage)
[![Dependency Status](https://beta.gemnasium.com/badges/github.com/tristanrobert/fog-proxmox.svg)](https://beta.gemnasium.com/projects/github.com/tristanrobert/fog-proxmox)

This is a [FOG](http://fog.io/) module gem to support [Proxmox VE](https://www.proxmox.com/en/proxmox-ve) (tested with 5.1)

It is intended to satisfy this [feature](https://github.com/fog/fog/issues/3644), but Proxmox provider only, and above all this [Foreman](http://www.theforeman.org) [feature](https://projects.theforeman.org/issues/2186).

It is inspired by the great [fog-openstack](https://github.com/fog/fog-openstack) module.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'fog-proxmox'
```

And then execute:

```ruby
bundle install --binstubs
```

Or install it yourself as:

```ruby
gem install fog-proxmox
```

## Usage

This is not yet a stable version. I recommend you not to use it in production.

Work is still in progress...

### Identity

See [examples/identity.rb](examples/identity.rb) or [spec/identity_spec.rb](spec/identity_spec.rb)

### Compute

See [examples/compute.rb](examples/compute.rb) or [spec/compute_spec.rb](spec/compute_spec.rb)


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bundle exec rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

You can help the [contributors](CONTRIBUTORS.md).
Bug reports and pull requests are welcome on GitHub at [Fog-Proxmox](https://github.com/tristanrobert/fog-proxmox). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

Please read [how to contribute](CONTRIBUTING.md).

## License

The gem is available as open source under the terms of the [GPL v3 License](LICENSE).
