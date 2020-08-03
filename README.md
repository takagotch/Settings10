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


