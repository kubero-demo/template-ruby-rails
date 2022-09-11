build: export GEM_HOME=/app/bundle; bundle install --jobs=4 --retry=3 --without development test; bundle clean; 
web: export GEM_HOME=/app/bundle; bundle exec puma -C config/puma.rb