rizqin@ubuntu:~$ mkdir btmc_prac
rizqin@ubuntu:~$ cd btmc_prac
rizqin@ubuntu:~/btmc_prac$ rails new first_prac_btmc
/usr/lib/ruby/1.9.1/rubygems/custom_require.rb:36:in `require': iconv will be deprecated in the future, use String#encode instead.
/usr/lib/ruby/vendor_ruby/railties/lib/rails_generator/generators/applications/app/app_generator.rb:7: Use RbConfig instead of obsolete and deprecated Config.
      create  
      create  app/controllers
      create  app/helpers
      create  app/models
      create  app/views/layouts
      create  config/environments
      create  config/initializers
      create  config/locales
      create  db
      create  doc
      create  lib
      create  lib/tasks
      create  log
      create  public/images
      create  public/javascripts
      create  public/stylesheets
      create  script/performance
      create  test/fixtures
      create  test/functional
      create  test/integration
      create  test/performance
      create  test/unit
      create  vendor
      create  vendor/plugins
      create  tmp/sessions
      create  tmp/sockets
      create  tmp/cache
      create  tmp/pids
      create  Rakefile
      create  README
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  config/database.yml
      create  config/routes.rb
      create  config/locales/en.yml
      create  db/seeds.rb
      create  config/initializers/backtrace_silencers.rb
      create  config/initializers/inflections.rb
      create  config/initializers/mime_types.rb
      create  config/initializers/new_rails_defaults.rb
      create  config/initializers/session_store.rb
      create  config/initializers/cookie_verification_secret.rb
      create  config/environment.rb
      create  config/boot.rb
      create  config/environments/production.rb
      create  config/environments/development.rb
      create  config/environments/test.rb
      create  script/about
      create  script/console
      create  script/dbconsole
      create  script/destroy
      create  script/generate
      create  script/runner
      create  script/server
      create  script/plugin
      create  script/performance/benchmarker
      create  script/performance/profiler
      create  test/test_helper.rb
      create  test/performance/browsing_test.rb
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/index.html
      create  public/favicon.ico
      create  public/robots.txt
      create  public/images/rails.png
      create  public/javascripts/prototype.js
      create  public/javascripts/effects.js
      create  public/javascripts/dragdrop.js
      create  public/javascripts/controls.js
      create  public/javascripts/application.js
      create  doc/README_FOR_APP
      create  log/server.log
      create  log/production.log
      create  log/development.log
      create  log/test.log
      create  vendor/rails
rizqin@ubuntu:~/btmc_prac$ touch README.md
rizqin@ubuntu:~/btmc_prac$ git init
Initialized empty Git repository in /home/rizqin/btmc_prac/.git/
rizqin@ubuntu:~/btmc_prac$ git add README.md
rizqin@ubuntu:~/btmc_prac$ git commit -m "first commit"
[master (root-commit) ad1c406] first commit
 Committer: Owner <rizqin@ubuntu.(none)>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 0 files changed
 create mode 100644 README.md
rizqin@ubuntu:~/btmc_prac$ git remote add origin https://github.com/BTMC2013/first-prac.git
rizqin@ubuntu:~/btmc_prac$ git push -u origin master
error: Couldn't resolve host 'github.com' while accessing https://github.com/BTMC2013/first-prac.git/info/refs
fatal: HTTP request failed
rizqin@ubuntu:~/btmc_prac$ git push -u origin master
Username for 'https://github.com': rizqueen
Password for 'https://rizqueen@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 212 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/BTMC2013/first-prac.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
rizqin@ubuntu:~/btmc_prac$ mkdir btmc_prac
rizqin@ubuntu:~/btmc_prac$ cd btmc_prac
rizqin@ubuntu:~/btmc_prac/btmc_prac$ rails new first_tut
/usr/lib/ruby/1.9.1/rubygems/custom_require.rb:36:in `require': iconv will be deprecated in the future, use String#encode instead.
/usr/lib/ruby/vendor_ruby/railties/lib/rails_generator/generators/applications/app/app_generator.rb:7: Use RbConfig instead of obsolete and deprecated Config.
      create  
      create  app/controllers
      create  app/helpers
      create  app/models
      create  app/views/layouts
      create  config/environments
      create  config/initializers
      create  config/locales
      create  db
      create  doc
      create  lib
      create  lib/tasks
      create  log
      create  public/images
      create  public/javascripts
      create  public/stylesheets
      create  script/performance
      create  test/fixtures
      create  test/functional
      create  test/integration
      create  test/performance
      create  test/unit
      create  vendor
      create  vendor/plugins
      create  tmp/sessions
      create  tmp/sockets
      create  tmp/cache
      create  tmp/pids
      create  Rakefile
      create  README
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  config/database.yml
      create  config/routes.rb
      create  config/locales/en.yml
      create  db/seeds.rb
      create  config/initializers/backtrace_silencers.rb
      create  config/initializers/inflections.rb
      create  config/initializers/mime_types.rb
      create  config/initializers/new_rails_defaults.rb
      create  config/initializers/session_store.rb
      create  config/initializers/cookie_verification_secret.rb
      create  config/environment.rb
      create  config/boot.rb
      create  config/environments/production.rb
      create  config/environments/development.rb
      create  config/environments/test.rb
      create  script/about
      create  script/console
      create  script/dbconsole
      create  script/destroy
      create  script/generate
      create  script/runner
      create  script/server
      create  script/plugin
      create  script/performance/benchmarker
      create  script/performance/profiler
      create  test/test_helper.rb
      create  test/performance/browsing_test.rb
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/index.html
      create  public/favicon.ico
      create  public/robots.txt
      create  public/images/rails.png
      create  public/javascripts/prototype.js
      create  public/javascripts/effects.js
      create  public/javascripts/dragdrop.js
      create  public/javascripts/controls.js
      create  public/javascripts/application.js
      create  doc/README_FOR_APP
      create  log/server.log
      create  log/production.log
      create  log/development.log
      create  log/test.log
      create  vendor/rails
rizqin@ubuntu:~/btmc_prac/btmc_prac$ git push origin master
error: The requested URL returned error: 403 Forbidden while accessing https://github.com/BTMC2013/first-prac.git/info/refs
fatal: HTTP request failed
rizqin@ubuntu:~/btmc_prac/btmc_prac$ git push origin master
Username for 'https://github.com': rizqueen
Password for 'https://rizqueen@github.com': 
Everything up-to-date
