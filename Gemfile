source 'https://rubygems.org'

gemspec

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem "vagrant", :git => "https://github.com/mitchellh/vagrant.git", :tag => "v1.2.2"
end

group :test do
  gem "vagrant-aws", "~> 0.2.2"
  gem "vagrant-rackspace", "~> 0.1.1"
end

group :docs do
  gem "yard", "~> 0.8.5"
  gem "redcarpet", "~> 2.2.2"
  gem "github-markup", "~> 0.7.5"
end
