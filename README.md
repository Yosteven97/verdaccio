# verdaccio

## installing globally using this methods

npm install --location=global verdaccio

or

yarn global add verdaccio

## running verdaccio on terminal globally on your pc locally
verdaccio

## running localhost
open http://localhost:4873/ on search engine

## create user
npm adduser --registry http://localhost:4873/

## login
user: *********
password: ********

## publish your project to verdaccio on your pc locally
npm publish --registry http://localhost:4873/

## refresh you search engine to check your new project has been added


## init npm on your new project
npm init

## install package on your project
npm install {your_package_name@1.0.0}


## remove publish package from global on your pc locally
npm unpublish --force {your_package_name@1.0.0}
