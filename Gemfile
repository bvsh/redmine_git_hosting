source 'https://rubygems.org'

# Gitolite Admin repository management
gem 'gitolite-rugged', git: 'https://github.com/bvsh/gitolite-rugged', tag: '1.2.0'

# Ruby/Rack Git Smart-HTTP Server Handler
gem 'gitlab-grack', '~> 2.0.0', git: 'https://github.com/jbox-web/grack.git', require: 'grack', branch: 'fix_gemfile'
# gem 'gitlab-grack', git: 'https://github.com/bvsh/grack.git'

# HAML views
gem 'haml-rails'

# Memcached client for GitCache
gem 'dalli'

# Redis client for GitCache
gem 'redis'
gem 'hiredis'

# Markdown rendering
gem 'html-pipeline'
gem 'rouge', '~> 3.3.0'
gem 'task_list'
gem 'rinku'

# Syntaxic coloration
gem 'github-markup'
gem 'RedCloth'
gem 'org-ruby'
gem 'creole'
gem 'asciidoctor'
gem 'rdoc', '~> 4.3'

# Rack parser for Hrack
gem 'rack-parser', require: 'rack/parser'

group :development, :test do
  gem 'rspec'
  gem 'rspec-rails'

  gem 'shoulda', '~> 3.5.0'
  gem 'shoulda-matchers', '~> 2.7.0'
  gem 'shoulda-context'

  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'faker', '1.7.3'
  gem 'sshkey'
  gem 'database_cleaner'

  # Publish to CodeClimate
  gem 'codeclimate-test-reporter', require: false
end

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'quiet_assets'

  gem 'brakeman'
  gem 'bullet'
end
