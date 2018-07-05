# pokemonAPI

This runs a local host server 8000 and shows the different Starter type pokemon from generation 4 in this API.

# How It's Made:
Tech used: HTML, CSS, JavaScript and Node-JS

In the index.html I used a input tag so the user can type in the names of each of the three pokemon stored in our API, a button tag to run our JavaScript function, heading tag and a paragraph tag, to display the result in the DOM. The main.js runs when the user clicks on the button. When the button is clicked, the value stored in the input tag is passed as a parameter to the server.js. The pokemon name is passed as a parameter, then the respective pokemon information is passed through the JSON and sent to the main.js. The main.js receives this JSON and parses the information and displays it in the DOM for each respective bit of information called on.

# Optimizations
Still need more generation pokeomon starters to add to the API. Possibly add more information regarding the pokemons weakness type to our database.

# Lessons Learned:
Will come back and add more when the changes are made to make it user friendly.
