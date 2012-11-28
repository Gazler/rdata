# RData
[![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/samdunne/rdata)
[![Build Status](https://secure.travis-ci.org/samdunne/rdata.png?branch=master)](https://travis-ci.org/samdunne/rdata)
[![Dependency Status](https://gemnasium.com/samdunne/rdata.png)](https://gemnasium.com/samdunne/rdata)

## Installation
```ruby
gem install rdata
```

Or in a Gemfile

```ruby
gem 'rdata'
```

## Usage
```ruby
require 'rdata'
```

## Stacks

### Initialization

```ruby
@stack = RData.Stack
```

### Operations

```ruby
@stack.push(x) 		# => Returns 'x'
@stack.pop 			# => Returns 'top'
@stack.top 			# => Returns 'top'
@stack.is_empty? 	# => Returns true/false
```

### More on Stacks
[Stacks - Wiki Link](https://github.com/samdunne/rdata/wiki/Stacks)