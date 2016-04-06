# Deploy aar file to Artifactory and Heroku app.

# Deploying to Heroku:

Use the following command to install the heroku-deploy plugin:

``$ heroku plugins:install https://github.com/heroku/heroku-deploy ``

# Deploy your WAR
In order to deploy your WAR use the following command:

``$ heroku deploy:war --war <path_to_war_file> --app <app_name>``

# Example

``$heroku deploy:war --war /Downloads/artifactory-oss-4.7.0/webapps/artifactory.war --app testwar ``

 Artifactory ContextUrl 

``artifactory_contextUrl=http://testwar.herokuapp.com``


Thanks to https://github.com/heroku/heroku-deploy

Inspire from :
http://jeroenmols.com/blog/2015/08/13/artifactory2/