# Meetup Event Planner

account creation, event creation, event display

The app must provide a form for users to create an account. 

The app should allow users to create a new event.

The app should display events that have been created.

Requirements
You do not need to create a functioning back-end or save user information. Only the form components themselves and their performance will be evaluated.

1) You do not need to create a real back-end or save user information, but the app must provide a form for users to create an account. Account creation should include, but is not limited to:

Name
Email address
Secure password (with character and length requirements)
Optional public biographical information (such as employer, job title, birthday, etc)
2) The app should allow users to create a new event. Each event should, at a minimum, allow a user to set:

Name of the event
Type of the event (birthday party, conference talk, wedding, etc.)
Event host (could be an individual’s name or an organization)
Event start date and time
Event end date and time
Guest list
Location
Optional message to the guests with additional information about the event
3) The app should display events that have been created.

4) Review the evaluation rubric for this project early and often.




## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Use bower install
	Install packages with bower install. Bower installs packages to bower_components/.
	
## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.


##Notes:
Have used date range picker from http://www.daterangepicker.com/ 


## Demo site
https://meetup1-b9738.firebaseapp.com/