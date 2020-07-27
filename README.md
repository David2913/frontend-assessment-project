# Frontend skills assessment project

For this task you will create a **React application** that will consume elements from an API of your choice and will also have a **Favorites** section for authenticated users.

API Examples: 

- [https://pokeapi.co](https://pokeapi.co/)
- [https://developers.giphy.com/](https://developers.giphy.com/)

**The app must be of production quality according to your understanding of it: testing, mobile-first, README, etc. The app must not require anything else than running `npm install` and `npm start` to run.** 

The application must have the following features:

# Searchable list

You must show the elements from the API in a scrollable list showing an image and a title per item (e.g. When using the Pokemon API you would show the name of the Pokemon and its photo). The list must also contain a search bar at the top to filter the list using the API. If the API you are using can't filter using free text, you can add a list of available filters instead.

Clicking an element of the list, must direct the user to the detail page.

# Detail page

The detail page must show the title of the element, an image and a short description. The user should also be able to go back to the main list page.

# Favorites section

The header must show a link to a favorites section. The favorites link, section and route must only be reachable if the user is authenticated. If the user is not authenticated, it should redirect them to the login route. There is no need to implement adding an element as favorite, you can show the same data of the main list or hardcode the data shown in this section. What will be evaluated is how you handle private routes and redirection.

# Login form

The app must have a login form, after submitting the username and password, it must call an async function that returns the user information and then redirects the user. There is no need to implement an authentication mechanism. You can build a mock async function that takes a username and a password and returns the user's information.

# Header

The header must show the favorites link and username if the user is authenticated.

# Bonus

Build an infinite scroll feature for the main list. When the user reaches the bottom of the list it retrieves the next elements until it retrieves all of them.

# Final considerations

Please write this application using ReactJS. You are free to implement it however you’d like with whatever resources or 3rd party code you’d want.

**Deadline:** We expect you to get back to us with the solution in 7 days. It won't be better if you delivery it before, so if you finish early, improve your code. Finally, don't rush, if you need more time please ask us whenever you need.

Create a private project in GitHub and share with us your code.

The repo should have your name, for example "david-zarate-sample-react-project", it will help us to identify your project.

Feel free to ask questions at any time (david.zarate@payclip.com)
