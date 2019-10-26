## Ruby on Rails Web Development - Capstone: Photo Tourist Web Application

Projects for Johns Hopkins University Ruby on Rails Web Development - Capstone: Photo Tourist Web Application

I may break these out into stand alone repos if needed.

https://www.coursera.org/learn/photo-tourist-web-app-capstone


### Project 1

Upgraded to Rails 5.2.3 - follow these instructions https://github.com/jlollis/rails5-mongoid. 

After commenting out all the old gems and replacing with newer versions compatible with Rails 5.2.3 in your Gemfile, and deleting or changing the name of Gemfile.lock, run:
```ruby
gem install bundler
bundle update rails
```

You need to add the changes to git and push to your staging area:
```bash
git add .
git commit -m "upgrade to rails 5.2.3"
git push staging getting-started
```

Then you can:
```bash
git push --force staging getting-started:master
```

Ignore the link Heroku puts to the screen and go to:
https://your-app-name.herokuapp.com/

In my case, that is:
https://polar-falls-82862.herokuapp.com
