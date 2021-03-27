# Heroku

## How Heroku Works
- > Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP.
- In order to run the application on Heroku you should inform the platform which parts of the application can be run.
- Sometimes, you need to determine which exact part shall be executed, this can be using _Procfiles_.

### Deploying applications
- Heroku uses mainly Git app deployment
- command :
> git push heroku master

### Building applications
- the building of an app starts once  the application source is received.

### Running applications on dynos
- the following command is run in the Procfile on a dyno. 
> heroku ps:scale web=3 queue=2

### Config vars
> heroku config:set ENCRYPTION_KEY=my_secret_launch_codes

### Releases
> heroku releases

### Dyno manager
> heroku run bash

### Add-ons
> heroku addons:create heroku-redis:hobby-dev

### Logging and monitoring
- > heroku logs
- > heroku logs --ps web.1 --tail

### HTTP routing
- > heroku ps:scale web+5

## Hints & Terminology: 
- >_Procfiles_ -list process types - named commands that you may want executed.
- > _Applications_ consist of your source code, a description of any dependencies, and a Procfile.
- > _slug_ is a bundle of your source, fetched dependencies, the language runtime, and compiled/generated output of the build system - ready for execution.
- >  Dynos are isolated, virtualized Unix containers, that provide the environment required to run an application.