# Ruby RSpec Build

BuildNinja configuration for a Ruby application with RSpec tests.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/abheekm/Ruby_App |
| **Branch** | main |
| **Stack** | Ruby with RSpec |

## About This Project

A Ruby calculator application with RSpec tests. Demonstrates the complete Ruby build and test workflow including Bundler, gem installation, and RSpec test execution.

## What This Demonstrates

- Bundler dependency management
- Gem installation (rspec, unit)
- RSpec test execution
- Multi-step Ruby builds

## Agent Requirements

- Ruby 3.0+
- Bundler
- RSpec

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `bundle install` | Install Bundler dependencies |
| 2 | `gem install rspec` | Install RSpec |
| 3 | `gem install unit` | Install Unit gem |
| 4 | `rspec ./spec/calculator_spec.rb` | Run tests |

## Artifacts

- `spec/` - Test specifications
