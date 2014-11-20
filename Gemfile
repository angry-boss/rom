source 'https://rubygems.org'

gemspec

group :test do
  gem 'mutant'
  gem 'mutant-rspec'
  gem 'rubysl-bigdecimal', platforms: :rbx
  gem 'guard'
  gem 'guard-rspec'
  gem 'codeclimate-test-reporter', require: false
end

group :sql do
  gem 'rom-sql', git: 'https://github.com/rom-rb/rom-sql.git', branch: 'master'
  gem 'jdbc-sqlite3', platforms: :jruby
  gem 'sqlite3', platforms: [:mri, :rbx]
end

group :benchmarks do
  gem 'activerecord'
  gem 'benchmark-ips'
end
