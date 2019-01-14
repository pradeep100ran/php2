# PHP Hello World Form

A barebones PHP web page.

## Deploy on Heroku

1. Create a [Heroku][heroku] account.
2. Install the [Heroku Command Line Interface (CLI)][heroku-cli].
3. Clone this repository:

   ```bash
   git clone https://github.com/MediaComem/php-hello-world-form
   ```
4. Create a Heroku application:
   * Either at the command line:

     ```bash
     cd php-hello-world-form
     heroku create
     ```
   * Or from the Heroku dashbord, then add the remote:

     ```bash
     cd php-hello-world-from
     heroku git:remote -a my-app-name
     ```
5. Deploy the application to Heroku by pushing the `master` branch:

   ```bash
   git push heroku master
   ```

[heroku]: https://www.heroku.com
[heroku-cli]: https://devcenter.heroku.com/articles/heroku-cli
