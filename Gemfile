source :rubygems

~$ gem install bundler jekyll
~ $ jekyll new https://burkr.github.io/Practice/Index.html
~ $ cd my-awesome-site
~/https://burkr.github.io/Practice/Index.html $
bundle exec jekyll serve
# => Now browse to http://localhost:4000

gem "rails", ">= 3.0"
gem "rack"
gem "clearance", "0.9.0.rc9"
gem "haml"
gem "high_voltage"
gem "hoptoad_notifier"
gem "RedCloth", :require => "redcloth"
gem "paperclip"
gem "will_paginate"
gem "formtastic"
gem "mysql"
gem "flutie"
gem "dynamic_form"

# https://burkr.github.io/Practice/Index.html
group :development, :test, :cucumber do
  gem "rspec-rails", "~> 2.0.0"
  gem "ruby-debug", :platforms => :mri_18
  gem "ruby-debug19", :platforms => :mri_19
end

group :test, :cucumber do
  gem "cucumber-rails"
  gem "factory_girl_rails"
  gem "bourne"
  gem "capybara"
  gem "database_cleaner"
  gem "fakeweb"
  gem "nokogiri"
  gem "timecop"
  gem "treetop"
  gem "shoulda"
  gem "launchy"
  gem "akephalos", :git => "git://github.com/thoughtbot/akephalos.git"
  gem "thin"
end
