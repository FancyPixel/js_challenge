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

* Make the application responsive, in your own taste ( CSS )

* [optional] The page must show 6 profiles on page load. Find the best way to browse the full list and show more profiles

* [optional] Provide a solution to show only the saved profiles
 
* [optional] Show a search text input to filter the profiles by username


## Guidelines

You can use Vuejs, Reactjs or JS Vanilla, you can start with the boilerplate you want.

You must use the given API calls to retrieve profiles and you can choose any API client to work with
You must provide the instructions to let us run the application.

If not specified in the design, it’s up to you to decide what’s best

## API docs
- This is the basic curl to retrieve a product listing. You'll have to implement client API calls to get paginated response. The "limit" parameter is used to retrieve a defined number of items, "offset" is the number of items to be skipped
```
  curl -X GET \
    'https://api.musement.com/api/v3/activities?limit=6&offset=0' \
    -H 'accept-language: it' \
    -H 'content-type: application/json' \
    -H 'x-musement-currency: EUR' \
    -H 'x-musement-version: 3.4.0'
```
- From the call above, consider these response props:
```
  * cover_image_url => is a URL string where you have to append this query string to make a responsive image ?q=60&fit=crop&w=[image_width_in_px]&h=[image_height_in_px]
  * title => product title
  * description => product description
  * retail_price => the product price
```
Please refer to [this page](https://api-docs.musement.com/reference#search) for documentation.

## Delivery

Create a **private Git repository** with the following format: 

	js_challenge_<first-name>-<last-name> 

[Github](https://github.com) allows private repositories for free, you only need to grant us access to it afterwards.
Please, use these accounts: [tommasoberlose](https://github.com/tommasoberlose), [andreamazz](https://github.com/andreamazz), [madAle](https://github.com/madAle).

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