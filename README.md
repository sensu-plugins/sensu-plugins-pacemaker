## Sensu-Plugins-pacemaker

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-pacemaker.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-pacemaker)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-pacemaker.svg)](http://badge.fury.io/rb/sensu-plugins-pacemaker)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-pacemaker/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-pacemaker)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-pacemaker/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-pacemaker)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-pacemaker.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-pacemaker)

## Functionality

## Files
 * bin/check-cluster-health

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-pacemaker -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-pacemaker`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-pacemaker' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-pacemaker' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
