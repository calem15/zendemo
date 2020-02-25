# zendemo for Dev
## Quick guide to start qa-test dev environment
### You need to install these before proceeding
* git
* docker
* python & pip
* docker-compose
### Steps:
1. Clone this repository to your local PC.
* `$ cd /path-to-workdir/`
* `$git clone git@github.com:calem15/zendemo.git`
2. Go to zendemo directory and clone https://github.com/zenrooms/qa-test 
* `$ cd /path-to-workdir/zendemo/`
* `$ git clone git@github.com:zenrooms/qa-test.git`
3. You are now ready to deploy your development environment to your local PC by running;
* `$ docker-compse up -d`
4. Test your app by pointing your browser to http://localhost

### Note: You may use your local repo `qa-test` directory to update the codes.
