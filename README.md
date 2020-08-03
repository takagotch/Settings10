### Settings10
---

https://github.com/yasslab/sample_apps

```sh
cd ~/environment
rails new apptky
cd apptky
vi Gemfile
bundle install --without production
vi app/controllers/application_controller.rb
vi config/routes.rb

rails g scaffold User name:string email:string
rails db:migrate
rails s
http://localhost:3000/

vi config/routes.rb
vi config/routes.rb
vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb
vi app/models/user.rb
vi app/views/users/index.html.erb
rails g scaffold Micropost content:text user_id:integer
rails db:migrate
vi config/routes.rb
vi app/controllers/microposts_controller.rb
curl https://localhost:3000/
curl https://localhost:3000/users
curl https://localhost:3000/users/new
curl https://localhost:3000/users/1/edit
curl https://localhost:3000/users/1
curl https://localhost:3000/
curl https://localhost:3000/microposts/
curl https://localhost:3000/microposts/new
curl https://localhost:3000/microposts/1
vi app/models/micropost.rb
vi app/models/user.rb
vi app/models/micropost.rb
rails c
vi app/models/micropost.rb
vi app/models/user.rb
vi app/models/user.rb
vi app/models/micropost.rb
vi app/controllers/users_controller.rb
vi app/controllers/microposts_controller.rb
vi app/controllers/application_controller.rb
```

```sh
vi app/views/layouts/application.html.erb
vi app/views/static_pages/home.html.erb
curl -o app/assets/images/rails.png -OL railstutorial.jp/rails.png
curl -0L cdn.learnenough.com/kitten.jpg
vi Gemfile
bundle install 
touch app/assets/stylesheets/custom.scss
vi app/assets/stylesheets/custom.scss
curl https://localhost:3000/
vi app/assets/stylesheets/custom.scss
vi app/assets/stylesheets/custom.scss
vi app/assets/stylesheets/custom.scss
vi app/views/layouts/application.html.erb
vi app/views/layouts/_shim.html.erb
vi app/views/layouts/_header.html.erb
vi app/views/layouts/_footer.html.erb
vi app/views/layouts/application.html.erb
vi app/assets/stylesheets/custom.scss
vi app/views/layouts/application.html.erb
ls app/assets/
vi app/assets/stylesheets/application.css
vi app/assets/stylesheets/custom.scss
vi test/controllers/static_pages_controller_test.rb
rails t
vi config/routes.rb
vi app/controllers/static_pages_controller.rb
vi app/views/static_pages/contact.html.erb
rails t
vi config/routes.rb
vi test/controllers/static_pages_controller_test.rb
vi config/routes.rb
vi app/views/layouts/_header.html.erb
vi app/views/layouts/_footer.html.erb
curl https://localhost:3000/about
rails g integration_test site_layout
vi test/integration/site_layout_test.rb
rails test:integration
rails t
vi test/test_helper.rb
vi test/integration/site_layout_test.rb
vi test/helpers/application_helper_test.rb
rails g controller Users new
vi app/controllers/users_controller.rb
vi app/views/users/new.html.erb
vi test/controllers/users_controller_test.rb
rails t
vi config/routes.rb
vi test/controllers/users_controller_test.rb
vi app/views/static_pages/home.html.erb
vi app/views/users/new.html.erb
```

```sh
<%#
modeling-users
%>
rails g controller Users new
rails g model User name:string email:string
vi db/migrate/[timestamp]_create_users.rb
rails db:migrate
rails db:rollback
vi db/schema.rb
vi app/models/user.rb

rails console --sandbox
User.new
user = User.new(name: "tky", email: "tky@gmail.com")
user.valid?
user.save
user
user.name
user.email
user.updated_at
User.create(name: "A Nother", email: "tky@gamil.com")
User.find(1)
User.find(3)
User.find_by(email: "tky@gmail.com")
User.first
User.all
user
user.email = "tky@gmail.com"
user.save
user.email
user.email = "tky@gmail.com"
user.reload.email
user.created_at
user.updated_at
user.update_attributes(name: "tky", email: "tky@gmail.com")
user.name
user.email
user.update_attribute(:name, "tky")
user.name

vi test/models/user_test.rb
vi test/models/user_test.rb
rails test:models
vi test/models/user_test.rb
rails test:models
vi app/models/user.rb
rails console --sandbox

user.errors.full_messages
user.save
rails test:models

vi test/models/user_test.rb
vi app/models/user.rb
rails test
vi test/models/user_test.rb

rails c
"a" * 51
("a" * 51).length
"a" * 244 + "tky@gmail.com"
("a" * 244 + "@gmail.com").length
rails test
vi app/models/user.rb
rails test
%w[foo bar baz]
["USER@foo.COM", "THE_US-ER@foo.bar.org", "first.last@foo.jp"]
puts address
end

vi test/models/user_test.rb
vi test/models/user_test.rb
rails test


vi app/models/user.rb
rails test:models
vi app/models/user.rb
test/models/user_test.rb
vi app/models/user.rb
vi test/models/user_test.rb

rails console --sandbox
user = User.create(name: "tky", email: "tky@gmail.com")
user.email.upcase
duplicate_user = user.dup
duplicate_user.email = user.email.upcase
duplicate_user.valid?

vi app/models/user.rb
rails test

rails g migration add_index_to_users_email
vi db/migrate/[timestamp]_add_index_to_users_email.rb
rails db:migrate

vi test/fixtures/users.yml
vi test/fixtures/users.yml
vi test/fixtures/users.yml
vi app/models/user.rb
vi test/models/user_test.rb
vi app/models/user.rb

rails g migration add_password_digest_to_users password_digest:string
vi db/migrate/[timestamp]_add_password_digest_to_users.rb
rails db:migrate
vi Gemfile
bundle install
vi app/models/user.rb

rails t
vi test/models/user_test.rb
rails t
vi test/models/user_test.rb

vi app/models/user.rb
rails test:models
rails c
user = User.find_by(email: "tky@gmail.com")
user.password_digest
user.authenticate("not_the_right_password")
user.authenticate("foobaz")
!!user.authenticate("foobar")
```


```sh
vi app/views/layouts/application.html.erb
vi app/assets/stylesheets/custom.scss
curl https://localhost:3000/

rails c
User.count
User.first

vi config/routes.rb
vi config/routes.rb
curl https://localhost:3000/
curl https://localhost:3000/users
curl https://localhost:3000/users/1
curl https://localhost:3000/users/new
curl https://localhost:3000/users/
curl https://localhost:3000/users/1/edit
curl https://localhost:3000/users/1
curl https://localhost:3000/users/1

vi app/views/users/show.html.erb
vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb
vi app/views/users/show.html.erb
vi app/helpers/users_helper.rb
curl https://localhost:3000/users/1

rails c
vi app/views/users/show.html.erb
vi app/assets/stylesheets/custom.scss
curl https://localhost:3000/users/1
vi app/helpers/users_helper.rb
vi app/helpers/users_helper.rb
curl https://localhost:3000/users/signup
vi app/controllers/users_controller.rb
vi app/views/users/new.html.erb
vi app/assets/stylesheets/custom.scss
curl https://localhost:3000/users/signup

vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb
curl https://localhost:3000/users/users

rails c
user = User.new(name: "tky", email: "tky@gmail.com",
                password: "xxx", password_confirmation: "xxx")
user.save
user.errors.full_messages
user.errors.count
user.errors.empty?
user.errors.any?

vi app/views/users/new.html.erb
mkdir app/views/shared
vi app/views/shared/_error_messages.html.erb
vi app/assets/stylesheets/custom.scss

rails g integration_test users_signup
rails c
User.count

vi test/integration/users_signup_test.rb
rails t
vi test/integration/users_signup_test.rb

vi config/routes.rb
vi app/views/users/new.html.erb
vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb

rails c
flash = { success: "It worked!", danger: "It failed." }
flash.each do |key, value|
puts "#{key}"
puts "#{value}"
end

vi app/views/layouts/application.html.erb
rails db:migrate:reset

rails c
vi test/integration/users_signup_test.rb
vi test/integration/users_signup_test.rb
vi app/views/layouts/application.html.erb
vi config/environments/production.rb
vi config/puma.rb
vi ./Procfile
```

```sh
rails g controller Sessions new
vi config/routes.rb
vi test/controllers/sessions_controller_test.rb
rails routes
vi app/views/sessions/new.html.erb
curl https://localhost:3000/login
vi app/controllers/sessions_controller.rb
vi app/controllers/sessions_controller.rb
vi app/controllers/sessions_controller.rb
curl https://localhost:3000/login
curl https://localhost:3000/

rails g integration_test users_login
vi test/integration/users_login_test.rb
rails test test/integration/users_login_test.rb
vi app/controllers/sessions_controller.rb
rails t test/integration/users_login_test.rb
vi rails test

vi app/controllers/application_controller.rb
vi app/helpers/sessions_helper.rb
vi app/controllers/sessions_controller.rb

vi app/helpers/sessions_helper.rb

rails c
session = {}
session[] = nil
@current_user ||= User.find_by(id: session[:user_id])
session[:user_id]= User.first.id
@current_user ||= User.find_by(id: session[:user_id])
@current_user ||= User.find_by(id: session[:user_id])

vi app/helpers/sessions_helpers.rb
vi app/views/layouts/_header.html.erb
vi app/assets/javascripts/application.js
curl https://localhost:3000/users/1
vi app/models/user.rb
vi test/fixtures/users.yml
vi test/integration/users_login_test.rb
rails test test/integration/users_login_test.rb
vi app/controllers/users_controller.rb
vi test/test_helper.rb
vi test/integration/users_signup_test.rb
rails t
vi app/helpers/sessions_helper.rb
vi app/controllers/sessions_controller.rb
vi test/integration/users_login_test.rb
rails t
```

```sh
rails g migration add_remember_digest_to_users remember_digest:string
vi db/migrate/[timestamp]_add_remember_digest_to_users.rb
rails db:migrate

rails c
SecureRandom.urlsafe_base64

vi app/models/user.rb
vi app/models/user.rb
vi app/models/user.rb
vi app/models/user.rb
vi app/models/user.rb
vi app/controllers/sessions_controller.rb
vi app/helpers/sessions_helper.rb
vi app/helpers/sessions_helper.rb
rails t
vi app/models/user.rb
vi app/helpers/sessions_helper.rb
rails t
vi test/integration/users_login_test.rb
rails t
vi app/controllers/sessions_controller.rb
vi test/models/user_test.rb
rails t
vi app/models/user.rb
railt t

vi app/views/sessions/new.htmle.erb
vi app/assets/stylesheets/custom.scss
curl https://localhost:3000/login
vi app/controllers/sessions_controller.rb

vi test/test_helper.rb
vi test/integration/users_login_test.rb
rails t

vi app/controllers/sessions_controller.rb
vi test/integration/users_login_test.rb
vi app/helpers/sessions_helper.rb
rails t
touch test/helpers/sessions_helper_test.rb
vi test/helpers/sessions_helper_test.rb
rails t test/helpers/sessions_helper_test.rb
vi app/helpers/sessions_helper.rb
rails t
```

```sh
vi app/controllers/users_controller.rb
vi app/views/users/edit.html.erb
curl https://localhost:3000/users/1/edit

rails c
User.new.new_record?
User.first.new_record?

vi app/views/layouts/_header.html.erb
vi app/views/users/_form.htmle.erb
vi app/views/users/new.html.erb
vi app/controllers/users_controller.rb
curl https://localhost:3000/users/1/

rails g integration_test users_edit
vi test/integration/users_edit_test.rb
rails t

vi test/integration/users_edit_test.rb
vi app/controllers/users_controller.rb
vi app/models/user.rb
rails t

vi app/controllers/user_controller.rb
curl https://localhost:3000/login

vi test/integration/users_edit_test.rb
rails t
vi app/controllersusers_controller.rb
vi test/controllers/users_controller_test.rb
vi app/controllers/users_controller.rb
rails t
vi test/fixtures/users.yml
vi test/controllers/users_controller_test.rb
vi app/controllers/users_controller.rb
rails t
vi app/helpers/sessions_helper.rb
vi app/controllers/users_controller.rb
vi test/integration/users_edit_test.rb
vi app/helpers/sessions_helper.rb
vi app/controllers/users_controller.rb
vi app/controllers/sessions_controllerr.rb
rails t
vi test/controllers/users_controller_test.rb
vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb
vi app/viewws/users/index.html.erb
vi app/helpers/users_helper.rb
vi app/assets/stylesheets/custom.scss
vi app/views/layouts/_header.html.erb
rails t
curl https://localhost:3000/users
vi Gemfile
bundle install
vi db/seeds.rb
rails db:migrate:reset
rails db:seed
curl https://localhost:3000/users
vi Gemfile
bundle install
vi app/views/users/index.html.erb

rails c
User.paginate(page: 1)
vi app/controllers/users_controller.rb
curl https://localhost:3000/users/
vi test/fixtures/users.yml
rails g integration_test users_index
vi test/integration/users_index_test.rb
rails t
vi app/views/users/index.html.erb
vi app/views/users/_user.html.erb
vi app/views/users/index.html.erb
rails t

rails g migration add_admin_to_users admin:boolean
vi db/migrate/[timestamp]_add_admin_to_users.rb
rails db:migrate

rails c
user = User.first
user.admin?
user.toggle!(:admin)
user.admin?

vi db/seeds.rb
rails db:migrate:reset
rails db:seed

vi test/controllers/users_controller_test.rb
vi app/views/users/_user.html.erb
curl https://localhost:3000/users
vi app/controllers/users_controller.rb
vi app/controllers/users_controller.rb
vi test/fixtures/users.yml
vi test/controllers/users_controller_test.rb
vi test/integration/users_index_test.rb
rails t
curl https://localhost:3000/users
```

```sh
rails g controller AccountActivations
vi config/routes.rb
rails g migration add_activation_to_users \
                  activation_digest:string activated:boolean activated_at:datetime
vi db/migrate/[timestamp]_add_activation_to_users.rb
rails db:migrate

rails c
vi app/models/user.rb
vi db/seeds.rb
vi test/fixtures/users.yml
rails db:migrate:reset
rails db:seed

rails g mailer UserMailer account_activation password_reset
vi app/views/user_mailer/account_activation.text.erb
vi app/views/user_mailer/account_activation.html.erb
vi app/mailers/application_mailer.rb
vi app/mailers/user_mailer.rb
vi app/mailers/application_mailer.rb
vi app/mailers/user_mailer.rb
vi app/views/user_mailer/account_activation.text.erb
vi app/views/user_mailer/account_activation.html.erb

rails c
CGI.escape('tky@gmail.com')

vi config/environments/development.rb
vi test/mailers/previews/user_mailer_preview.rb
vi test/mailers/previews/user_mailer_preview.rb
curl https://localhost:3000/rails/mailers/user_mailer/account_activation
curl https://localhost:3000/rails/mailers/user_mailer/account_activation.txt
vi test/mailers/user_mailer_test.rb
vi test/mailers/user_mailer_test.rb
vi config/environments/test.rb
rails test:mailers
vi app/controllers/users_controller.rb
vi test/integration/users_signup_test.rb

rails c
a = [1, 2, 3]
a.length
a.send(:length)
a.send("length")

user = User.first
user.activation_digest
user.send(:activation_digest)
user.send("activation_digest")
user.send("#{attribute}_digest")

vi app/models/user.rb
rails t
vi app/helpers/sessions_helper.rb
vi test/models/user_test.rb
rails t

vi app/controllers/account_activations_controller.rb
curl https://localhost:3000/users/101
vi app/controllers/sessions_controller.rb
curl https://localhost:3000/
vi test/integration/users_signup_test.rb
rails t
vi app/models/user.rb
vi app/controllers/users_controller.rb
vi app/controllers/account_activations_controller.rb
rails t

vi app/models/user.rb
vi app/controllers/users_controller.rb

vi config/environments/production.rb
curl https://localhost:3000/users/1
```

```sh
rails g controller PasswordResets new edit --no-test-framework
vi config/routes.rb
vi app/views/sessions/new.html.erb
curl https://localhost:3000/login
rails g migration add_reset_to_users reset_digest:string \
                  reset_sent_at:datetime
rails db:migrate
vi app/views/sessions/new.html.erb
vi app/views/password_resets/new.html.erb
curl https://localhost:3000/password_resets/new
vi app/controllers/password_resets_controller.rb
vi app/models/user.rb
curl https://localhost:3000/password_resets
vi app/mailers/user_mailer.rb
vi app/views/user_mailer/password_reset.text.erb
vi app/views/user_mailer/password_reset.html.erb
vi test/mailers/previews/user_mailer_preview.rb
curl https://localhost:3000/rails/mailers/user_mailer/password_reset
curl https://localhost:3000/rails/mailers/user_mailer/password_reset.txt
curl https://localhost:3000/
vi test/mailers/user_mailer_test.rb
rails t
vi app/views/password_resets/edit.html.erb
vi app/controllers/password_resets_controller.rb
curl https://localhost:3000/rails/mailers/user_mailer/password_resets/xxxxx
vi app/controllers/password_resets_controller.rb
vi app/models/user.rb
curl https://localhost:3000/password_resets/xxxx
curl https://localhost:3000/users/101

rails g integration_test password_resets
vi test/integration/password_resets_test.rb
rails t
vi app/models/user.rb
vi test/integration/password_resets_test.rb
vi app/controllers/password_resets_controller.rb
vi config/environments/production.rb
```

```sh
rails g model Micropost content:text user:references
vi app/models/micropost.rb
vi db/migrate/[timestamp]_create_microposts.rb
rails db:migrate
vi test/models/micropost_test.rb
vi app/models/micropost.rb
rails test:models
vi test/models/micropost_test.rb

rails c
"a" * 10
"a" * 141

vi app/models/micropost.rb
rails t
vi app/models/micropost.rb
vi app/models/user.rb
vi test/models/micropost_test.rb
rails t
vi test/models/micropost_test.rb
vi test/fixtures/microposts.yml
rails test test/models/micropost_test.rb
vi app/models/micropost.rb

rails t
vi app/models/user.rb
vi test/models/user_test.rb
rails t


rails db:migrate:reset
rails db:seed

rails g controller Microposts
vi app/views/microposts/_micropost.html.erb
vi app/controllers/users_controller.rb
vi app/views/users/show.html.erb
curl https://localhost:3000/users/1
vi db/seeds.rb

rails db:migrate:reset
rails db:seed
curl https://localhost:3000/users/1
vi app/assets/stylesheets/custom.scss
curl https://localhost:3000/users/1
curl https://localhost:3000/users/5
curl https://localhost:3000/users/1?page=2

rails g integration_test users_profile
vi test/fixtures/microposts.yml
vi test/integration/users_profile_test.rb
rails t

vi config/routes.rb
vi test/controllers/microposts_controller_test.rb
vi app/controllers/application_controller.rb
vi app/controllers/users_controller.rb
vi app/controllers/microposts_controller.rb
rails t
vi app/controllers/microposts_controller.rb
vi app/views/static_pages/home.html.erb
vi app/views/shared/_user_info.html.erb
vi app/views/shared/_micropost_from.html.erb
vi app/views/shared/_micropost_form.html.erb
vi app/controllers/static_pages_controller.rb
vi app/views/shared/_error_messages.html.erb
rails t
vi app/views/users/new.html.erb
vi app/views/users/edit.html.erb
vi app/views/password_resets/edit.html.erb
rails t
curl https://localhost:3000/
curl https://localhost:3000/microposts
curl https://localhost:3000/microposts/1

vi app/models/user.rb
vi app/controllers/static_pages_controller.rb
vi app/views/shared/_feed.html.erb
vi app/views/microposts/_micropost.html.erb
vi app/views/static_pages/home.html.erb
curl https://localhost:3000/
vi app/controllers/microposts_controller.rb
vi app/views/microposts/_micropost.html.erb
vi app/controllers/microposts_controller.rb
curl https://localhost:3000/
vi test/fixtures/microposts.yml
vi test/controllers/microposts_controller_test.rb

rails g integration_test microposts_interface
vi test/integration/microposts_interface_test.rb
rails t
vi test/integration/microposts_interface_test.rb

vi Gemfile
bundle install
rails g uploader Picture
rails g migration add_picture_to_microposts picture:string
rails db:migrate
vi app/models/micropost.rb
vi app/views/shared/_micropost_form.html.erb
vi app/controllers/microposts_controller.rb
vi app/views/microposts/_micropost.html.erb
curl https://localhost:3000/
vi test/integration/microposts_interface_test.rb
vi app/uploaders/picture_uploader.rb
vi app/models/micropost.rb
vi app/views/shared/_micropost_from.html.erb
curl https://localhost:3000/

sudo yum install -y ImageMagick

vi app/uploaders/picture_uploader.rb
curl https://localhost:3000/
vi config/initializers/skip_image_resizing.rb
vi app/uploaders/picture_uploader.rb
vi config/initializers/carrier_wave.rb

vi .gitignore

```

```sh


```










```sh
git init .
git add .
git commit -m "1st save"
git remote add origin git@bitbucket.org:takagotch/apptkyxxx.git
git push -u origin 

heroku create
git push heroku master
heroku run rails db:migrate

heroku logs
heroku run rails console --sandbox
heroku maintenance:off

heroku pg:reset DATABASE
heroku run rails db:migrate
heroku run rails db:seed
heroku restart

heroku addons:create sendgrid:starter
heroku config:get SENDGRID_USERNAME
heroku config:get SENDGRID_PASSWORD

heroku addons:create sendgrid:starter
heroku addons:add sendgrid:starter

git push heroku 
heroku pg:reset DATABASE
heroku run rails db:migrate
heroku run rails db:seed
```

```sh


```

```sh
cd ~/environment
rails new apptky2
cd apptky2
vi Gemfile
bundle install --without production
bundle update
vi app/controllers/application_controller.rb
vi config/routes.rb
rails g controller StaticPages home help 
vi config/routes.rb
rails s
https://localhost:3000/
https://localhost:3000/static_pages/
https://localhost:3000/static_pages/home
https://localhost:3000/static_pages/help

vi app/controllers/static_pages_controller.rb
vi app/views/static/pages/home.html.erb
vi app/views/static/pages/help.html.erb
vi app/views/static_pages/home.html.erb
vi app/views/static_pages/help.html.erb

ls test/controllers/
vi test/controllers/static_pages_controller_test.rb
rails test
vi test/controllers/static_pages_controller_test.rb
rails t
vi config/routes.rb
rails t
vi app/controllers/static_pages_controller.rb
rails t
touch app/views/static_pages/about.html.erb
vi app/views/static_pages/about.html.erb
rails t
curl https://localhost:3000/
curl https://localhost:3000/static_pages
curl https://localhost:3000/static_pages/about
mv app/views/layouts/application.html.erb layout_file
vi test/controllers/static_pages_controller_test.rb
rails t
vi app/views/static_pages/home.html.erb
curl https://localhost:3000/
vi app/views/static_pages/help.html.erb
vi app/views/static_pages/about.html.erb
rails t
vi test/controllers/static_page_controller_test.rb
vi app/views/static_pages/home.html.erb
rails t
vi app/views/static_pages/help.html.erb
vi app/views/static_pages/about.html.erb
mv layout_file app/views/layouts/application.html.erb
vi app/views/layouts/application.html.erb
vi app/views/static_pages/home.html.erb
vi app/views/static_pages/help.html.erb
vi app/views/static_pages/about.html.erb
rails t
vi app/views/static_pages/contact.html.erb
vi config/routes.rb
vi test/controllers/static_pages_controller_test.rb
vi config/routes.rb

vi test/test_helper.rb
bundle exec guard init
sudo yum install -y tmux
vi Guardfile
vi .gitignore
bundle exec guard
```

```sh
vi app/views/layouts/application.html.erb
vi app/helpers/application_helper.rb
vi app/views/layouts/application.html.erb
vi test/controllers/static_pages_controller_test.rb
rails t
vi app/views/static_pages/home.html.erb
rails t
vi ~/.irbrc
rails c
vi app/helpers/application_helper.rb
vi app/views/layouts/application.html.erb
vi app/helpers/application_helper.rb
vi app/views/layouts/application.html.erb

vi  example_user.rb
rm exaple_user.rb
```

```
<%#
# generate, destroy
rails g controller StaticPages home help
rails destroy controller StaticPages home help

rails g model User name:string email:string
rails destroy model User

# rails db:migrate
rails db:migrate
rails db:rollback
rails db:migrate VERSION=0

# git 
git checkout -b static-pages
git checkout master
git merge static-pages

git checkout -b rails-ruby
git checkout master
git merge rails-ruby

git checkout -b layout
git checkout master
git merge layout

git checkout -b modeling-users
git checkout master
git merge modeling-users

git checkout -b sign-up
git checkout master
git merge sign-up

git checkout -b basic-login
git checkout master
git merge basic-login

git checkout -b advanced-login
git checkout master
git merge advanced-login

git checkout -b updating-users
git checkout master
git merge updating-users

git checkout -b account-activation
git checkout master
git merge account-activation

git checkout -b password-reset
git checkout master
git merge password-reset

git checkout -b user-microposts
git checkout master
git merge user-microposts

git checkout -b following-users
git checkout master
git merge following-users

# ps aux
sudo yum install -y tmux
ps aux
ps aux | grep sprint
kill -15 12241
sprint stop
pkill -15 -f spring

# test, development, production
rails c
rails c test
rails s --environment production
rails db:migrate RAILS_ENV=production
heroku run rails console

heroku config:set S3_ACCESS_KEY="xxx"
heroku config:set S3_SECRET_KEY="xxx"
heroku config:set S3_BUCKET="xxx"
heroku config:set S3_REGION="xxx"
%>
```

```
```

```
```

```
```

```
```


