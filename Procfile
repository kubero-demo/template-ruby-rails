build: export GEM_HOME=/app/bundle; bundle install --jobs=4 --retry=3 --path=/app/bundle --without development test; bundle clean; 
web: bundle exec puma -C config/puma.rb