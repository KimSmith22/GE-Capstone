# GE-Capstone
Repo for GE Capstone Project
This is a project implemented for the WOS Java Capstone Project segment.
Project members are: Kimberli Smith, Jeff Sanchez, and Kristen Boyd

The summer event mapping tool will allow the user to quickly search for local carnivals
and music festivals.  

The current version of the application is built with the following technologies:
Front End: HTML5, CSS3, Polymer2.0
Database/API:
Back End:

Future updates of the application will utilize Google Map's location service to capture the user's location;
the application will then allow the user to query the returned results by proximity to user's location
as well as by price.  

<!-- Running the project -->
To construct this project it was necessary to install the polymer cli, Node.js, npm, Git, and bower_components

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.

## Viewing the Application

```
$polymer serve

Open your browser and navigate to the following url:
http://127.0.0.1:8000
```

## Building The Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

The application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
