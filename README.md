# Re-former project

- Re-former is part of the forms project in the Odin's Ruby on Rails' curriculum projects.
- It gives a chance to actually build some forms, both using nearly-pure HTML and then graduating to using the      helper methods that Rails provides.
- Here, I have built the form in the old fashion way and then in a new fashion way.

## To get started

1. Clone this repo in your local machine, then `cd` into the re-former directory.
```
$ git clone https://github.com/Leon-Mbegera/re-former.git
$ cd re-former
```
2. Install required gem files, excluding gem to run production.
`bundle install --without production`

3. Migrate the database
`rails db:migrate`

## Deploying
- To deploy this form application, you’ll need to create a new Heroku application, switch to the right branch, push up the source, run the migrations, and seed the database with sample users:

```
$ heroku create
$ git checkout updating-users
$ git push heroku updating-users:master
$ heroku run rails db:migrate
$ heroku run rails db:seed
```

- Visiting the URL returned by the original heroku create should now show you the re-former running in production.

## Author

👤 **Leon**

- GitHub: [@githubhandle](https://github.com/Leon-Mbegera)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/leon-mbegera-053991174/)
