# PHP Hello World Form

A barebones PHP web page.

## Deploy on Heroku

* Create a [Heroku][heroku] account.
* Install the [Heroku Command Line Interface (CLI)][heroku-cli].
* Clone this repository:

  ```bash
  git clone https://github.com/MediaComem/php-hello-world-form
  ```
* Create a Heroku application:
  1. Either at the command line:

     ```bash
     cd php-hello-world-form
     heroku create
     ```
  2. Or from the Heroku dashbord, then add the remote:

     ```bash
     cd php-hello-world-from
     heroku git:remote -a my-app-name
     ```
* Deploy the application to Heroku by pushing the `master` branch:

  ```bash
  git push heroku master
  ```

[heroku]: https://www.heroku.com
[heroku-cli]: https://devcenter.heroku.com/articles/heroku-cli
