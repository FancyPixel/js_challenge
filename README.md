# Javascript Developer coding challenge

Using the assets provided, your task is to build a simple web application that shows a list of GitHub profiles.

Please, read all sections within this document carefully.

Points marked as optional are entirely up to you.
They will give you the chance to shine within the selection process but they are not required.

With the ["Guidelines"](#Guidelines) section in mind, you should complete at least the following required features.


## Required features

* Avoid to use ANY external libraries for components

* Develop the “Add/Remove to Favorites” action which works client side only

* The number of saved profiles in the header must be updated with the favorite profiles count

* Make the application responsive and with a modern design, in your own taste ( CSS )

* Initially the page must load only 6 profiles. Find the best way to browse the full list from the server and show more profiles

* Provide a solution to show only the saved profiles

* [optional] Show a search text input to filter the profiles by username

* [optional] Use of Typescript

* [optional] Use of Redux Toolkit

* [optional] Use of CSS preprocessors

## Guidelines

You're free to use the framework of your choice (Vuejs, Reactjs, Angularjs...) or just 'ol plain Vanilla JS. Also you can start with a boilerplate if you want.

You must use the given API to retrieve a list of profiles and you can choose any API client to work with.
You must provide the instructions to let us run the application.

If not specified in the design, it’s up to you to decide what’s best.

## API docs

At [this page](https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api?apiVersion=2022-11-28&tool=javascript) you can find GitHub's "Getting started with the REST API" guide, with plenty of code snippets
and JS examples ready to use. Please avoid to use the Octocat JS library.

As you can read in the linked doc, GitHub's API require authentication. ***You must own a GitHub account in order to complete this challenge.***

##### AUTH TOKEN Creation: TL;DR Version

Go to [your profile's settings page](https://github.com/settings/profile). On the left menu, click on the last entry, that should be
[Developer settings](https://github.com/settings/apps). On the left menu, click on Personal Access Token and then on [Fine-grained tokens](https://github.com/settings/tokens?type=beta). 
On the top right, click on `Generate new token`. Give the token a name by filling in the required `Token name` field. You can leave all the remaining fields with the default values.

### Brief summary of needed GitHub's API

These info are expecially useful in case you choose to not use octocat.js

```text
Host: api.github.com
Protocol: https
Headers:
    - content-type: application/json
    - accept: application/vnd.github.v3+json

endpoints:
    - GET /users  # Get a list of users
```

## Delivery

Create a **private Git repository** with the following format:

	js_challenge_<first-name>-<last-name>

[Github](https://github.com) allows private repositories for free, you only need to grant us access to it afterwards.
Please, use these accounts: [tommasoberlose](https://github.com/tommasoberlose), [andreamazz](https://github.com/andreamazz), [madAle](https://github.com/madAle), [micheletedeschi](https://github.com/micheletedeschi).

Commit your work as you progress, we look at the commit history as well

You can delete the contents of this README and replace it with content of your own

## Eliminatory Points

Not following these points may cause an immediate elimination:

* Project is delivered in any way other than in a private GIT repository
* The project's required features aren’t fulfilled
* Lack of instructions to run the project

## Assets Provided

* Fonts
* HTML code - index.html
* CSS code - main.css
* API docs
