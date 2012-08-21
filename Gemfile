source "http://rubygems.org"

gemspec

group :test do
  gem "rake"
  gem "sinatra"
  gem "rspec"
  gem "ci_reporter"
  gem "simplecov"
  gem "simplecov-rcov"
  gem 'eventmachine', '>= 1.0.0.rc.4'
  gem 'vcap_common', :require => ['vcap/common', 'vcap/component'], :git => 'git://github.com/IronFoundry/vcap-common.git', :branch => 'ironfoundry'
  gem 'vcap_logging', :require => ['vcap/logging'], :git => 'git://github.com/IronFoundry/common.git', :branch => 'ironfoundry'
  gem 'warden-client', :require => ['warden/client'], :git => 'git://github.com/cloudfoundry/warden.git', :ref => '21f9a32ab50'
  gem 'warden-protocol', :require => ['warden/protocol'], :git => 'git://github.com/cloudfoundry/warden.git', :ref => '21f9a32ab50'
end
