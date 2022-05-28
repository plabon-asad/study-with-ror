# Study with RoR
Study for self development to be a ROR developer.

# Check Rails Local Status

[Check all available version of Rails](https://rubygems.org/gems/rails/versions)

| Command | Description |
| ------ | ------ |
| `gem list rails --local` | Check local installed version |
| `rails --help` | Rails help command |
| `rails _version_ new application_name` | Make a new project |
 

### Problem (Issue)

**Can't find gem railties (>= 0.a) with executable rails (Gem::GemNotFoundException)**
```
/Users/pc_name/.rvm/rubies/ruby-3.0.3/lib/ruby/3.0.0/rubygems.rb:278:in `find_spec_for_exe': can't find gem railties (>= 0.a) with executable rails (Gem::GemNotFoundException)
        from /Users/pc_name/.rvm/rubies/ruby-3.0.3/lib/ruby/3.0.0/rubygems.rb:297:in `activate_bin_path'
        from /usr/local/bin/rails:23:in `<main>'
```

**Solution:**

Try to run `gem install bundler` then run `bundle`. And if everything get good then check rails version by `rails -v`. If rails version get so everything now working fine else try again by this command `bundle install --path vendor/bundle`. [Link here](https://stackoverflow.com/questions/52051122/cant-find-gem-railties-0-a-with-executable-rails-gemgemnotfoundexceptio)

