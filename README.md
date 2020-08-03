### Settings10
---



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

```
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
model users 
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





```


```
```

```
```

```
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
```

```

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

# ps aux
sudo yum install -y tmux
ps aux
ps aux | grep sprint
kill -15 12241
sprint stop
pkill -15 -f spring


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


