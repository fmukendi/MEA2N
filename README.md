# Mea2nApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

http://localhost:4200/

/////////////////////////HTTP//////////////////
echo "# MEA2N" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/fmukendi/MEA2N.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/fmukendi/MEA2N.git
git push -u origin master

///////////////////////////SSH///////////////////////////////
echo "# MEA2N" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:fmukendi/MEA2N.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin git@github.com:fmukendi/MEA2N.git
git push -u origin master

//// NOTES ////

git remote set-url origin git@github.com:fmukendi/MEAN_SAMPLE.git

git remote set-url origin https://github.com/fmukendi/MEAN_SAMPLE.git

git remote show origin

git remote -v

git remote rm origin

git commit -m  'commit message'

git commit -am  'commit message'

git status


///// KILL RUNNING SERVERS 

Windows Machine:

Need to kill a Node.js server, and you don't have any other Node processes running, you can tell your machine to kill all processes named node.exe. That would look like this:

taskkill /im node.exe
And if the processes still persist, you can force the processes to terminate by adding the /f flag:

taskkill /f /im node.exe