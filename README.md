# Deploy on Heroku
Here are listed step by step the commands to run for deploy in Heroku. This commands were executed in cmd (**windows command line**) after .exe package standard setup.
  * heroku login
  * heroku create (inside the local repository)
  * git push heroku main (deploy at the web address given)
  * heroku ps:scale web=1 (at least one instance of the app is running)
  * heroku open (open from cmd the web address given)
