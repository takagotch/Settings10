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
```

```sh
cd 
```

```
```

```
```

```
```

```
```


