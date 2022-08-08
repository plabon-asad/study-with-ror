# Study with RoR
Study for self development to be a ROR developer.

# Check Rails Local Status

👉 [Check all available version of Rails](https://rubygems.org/gems/rails/versions)<br>
👉 [Rails simple commands](https://dev.to/fromwentzitcame/your-go-to-rails-command-line-cheat-sheet-1ok7)

| Command | Description |
| ------ | ------ |
| `gem list rails --local` | Check local installed version |
| `rails --help` | Rails help command |
| `rails _version_ new application_name` | Make a new project |
| `bundle pristine` | Restores installed gems to their pristine condition [Link here](https://bundler.io/man/bundle-pristine.1.html) |

### Redis - Install
I had the same issue and the steps I used to solve this in Mac OSX were:
 - Install redis (if not installed) `brew install redis`
 - Start the redis server, goto terminal and run `redis-server`
 
Or to start in background *By default Redis does not run as a daemon. Use 'yes' to use it*
`redis-server --daemonize yes` [Link here](https://stackoverflow.com/questions/36155607/error-connecting-to-redis-on-127-0-0-16379-errnoeconnrefused-wercker)
 

### Problem (Issue 🐝)

⚠️ **Can't find gem railties (>= 0.a) with executable rails (Gem::GemNotFoundException)**
```
/Users/pc_name/.rvm/rubies/ruby-3.0.3/lib/ruby/3.0.0/rubygems.rb:278:in `find_spec_for_exe': can't find gem railties (>= 0.a) with executable rails (Gem::GemNotFoundException)
        from /Users/pc_name/.rvm/rubies/ruby-3.0.3/lib/ruby/3.0.0/rubygems.rb:297:in `activate_bin_path'
        from /usr/local/bin/rails:23:in `<main>'
```

✅ **Solution:**

Try to run `gem install bundler` then run `bundle`. And if everything get good then check rails version by `rails -v`. If rails version get so everything now working fine else try again by this command `bundle install --path vendor/bundle`. [Link here](https://stackoverflow.com/questions/52051122/cant-find-gem-railties-0-a-with-executable-rails-gemgemnotfoundexceptio)

# Spree-4.4 | Rails 6 application

| Link | Description | Compatible Version |
| ------ | ------ | ------ |
| [Create new Spree project](https://github.com/spree/spree_starter) | Spree starter template | ✅ Spree 4.4 |
| [Spree Extensions directory](https://github.com/spree-contrib) | Officially supported 3rd party integrations & plugins for @spree | ✅ Spree 4.4 |
| [Spree comments](https://github.com/cloudsailor/spree_comments) | Add commenting to orders / shipments | ❎ Spree 4.4 |




N.B. You can use it for better documenting. Just **copy** & **paste** <br> ⛑️ 🐝 ⭐ ✅ ❎ ❌ 🚫 ⁉️ 🔔 🔕 🔸 🔹 ‼️  ✏️ 📌 📍 📎 📗 📕 📙 🍕 👉 👍 👎 
