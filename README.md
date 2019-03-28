# Test Vue/Express/Mocha Project

[Nuxt.js - Vue Framework :](https://nuxtjs.org/guide/directory-structure)  
[Express.js :](https://expressjs.com/en/4x/api.html)  
[Reqres - Dummy API :](https://reqres.in/)  
[Mocha :](https://mochajs.org/)

## Task

    Note: Access the reqres API through the Express server, client side requests should all be routed through Express

Clone this repository and extend the application by completing the following tasks.

>1) Add a Vue component into index.vue to display an unordered list of user records
>
>- Display a list of users returned (three users at a time)  
>```https://reqres.in/api/users/api/users```  
>
>- Include buttons for showing the next three users, and the previous three users  
>
>- If one of the list items is clicked, remove the user from the unordered list
>
>2) Add a Vue component into index.vue to allow users to submit a new account creation form
>
>- Create a form that accepts 'email' and 'password'  
>
>- Add the submit button and display a prompt if submission completes successfully  
>```https://reqres.in/api/users/api/register```  
>
>3) Add a unit test with Mocha to check the get `/api/users` is retrieving the expected data, an array with a length of three
>

## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
