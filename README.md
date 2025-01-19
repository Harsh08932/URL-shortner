# URL-shortner
 create a server side URL_shortner using core GOlang knowledge


-------------------------------------------------Process workflow---------------------------------------------------

--> Create a structure containing all the fields for saving out URL in DB

--> create a function that takes the originalURL and send back a short URL 
    Shortening is done using hashing and by use of md5 package

--> now to store the shortendURL into DB inside the createURL function

--> We create a function where we give the shortenedURL and endup getting original URL so that we can redirect 
    user.(getURL function)

--> We need to setup our live server and listen for request and create a handler fucntion so that we can intract with the server

--> ShortURL handler - redirects the route to the page where the shortURL is pointing

--> now we create the redirect function to go to different routes