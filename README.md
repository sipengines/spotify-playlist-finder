# Assignment

1) The code provides a query to spotify for a list of categories and appends it to webpage as JSON Data. Design a simple UI to display this data in a list of cards.

2) Make the items clickable. When a user clicks the item, query the spotify api to get a list of that categories playlists and display those to the user as a popup. No need to make this data pretty you can leave it as raw data. Documentation can be found here: https://developer.spotify.com/documentation/web-api/reference/#endpoint-get-a-categories-playlists

3) The purpose of this assignment is to see how you structure your code and your general practices as a developer. Though you may be able to find solutions to this assignment online, we advise you to do this on your own. You can use resources to help understand Jquery, and any of the other libraries provided. We see this assignment as an oppurtunity for you to showcase your abilities and create something unique that will help you stand out. If you have any questions feel free to contact us.

<br>

## Rules
- You may only use the libraries provided in the "/vendor" directory.
- Feel free to use online resources to help you
- ### You should not have to alter any files in the _**/vendor**_ directory or _**config.js**_


<br>

## Guide
- Fork this repo on github and commit/push your changes to your forked repo.
- This project is configured using requirejs. Look at the code provides to see how to define AMD modules.
- _**lib/main.js**_ is the entry point of the app.

<br>

### Getting an spotify credentials
Use the link below to generate credentials for the spotify api and set the **AUTH_TOKEN** variable in the _**lib/api.js**_ file

> https://developer.spotify.com/console/get-browse-categories/
 - You do not need to select any of the scopes in the "Request Token" dialog to access the endpoints needed for this assignment.

`

    const AUTH_TOKEN = '**************************JDFSIJ-RA';

    const BASE_URL = 'https://api.spotify.com/v1';
    
`




