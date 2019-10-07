# Dogs API

for the Dogs API

How to build an API app?

* Step 1 - watch for user input; tell waiter your meal,
* - Step 1a - create a trigger
* - Step 1b - get user input
* - Step 1c - input validation
* - Step 1d - use the api function


* Step 2 - define the function to make the api call; waiter goes to kicthen to prepare your meal
* - Step 2a - make the api call using the URL, dataType (JSON or JSONP), type (GET or POST)
* - Step 2b - success scenario (call the function to display the results)
* - Step 2c - failure scenario (display errors)


* Step 3 - display the results; sales process
* - Step 3a - console.log the results
* - Step 3b - if there are no results show errors
* - Step 3c - if there are results, create an HTML results variable
* - Step 3d - if there is more than one result, use a for loop (or .each) to populate the empty HTML results variable
* - Step 3e - send the content of HTML results variable to the HTML ($("class or id name from the HTML").html(HTML results variable))

## Where do I find the API documentation?

https://dog.ceo/dog-api/#breed and select /api/breed/{breed name}/images


## What is the API end point syntax?

https://dog.ceo/api/breed/' + queryTarget + '/images,

## Do I need an API key?

No.

## My page refreshes as soon as I click the button

Use event.preventDefault(); (mode details here https://www.w3schools.com/jquery/event_preventdefault.asp)
