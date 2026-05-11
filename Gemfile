source "https://rubygems.org"

gemspec

group(:development, optional: true) do
  gem 'rake'
  gem 'rspec'

  unless RUBY_PLATFORM =~ /java/
    gem 'simplecov'
    gem 'cane'
    gem 'yard'
    gem 'redcarpet'
  end
end
