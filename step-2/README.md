
## Routing

- Routing is the process of redirecting a user to different pages based on their action or request. We will be using React Router in our application to navigate a user to a different page.
- Four pages make up our application. Even if he keeps attempting by manipulating the url, an unknown user will only be given access to the login and register pages and will not be able to reach the home page or the coin page. Our application's core pages, which house the bulk of its material, will be considered our private Routes, making them inaccessible to anybody who hasn't authenticated.
- Put the login and register pages inside public routes and the main page and the coin pages inside private routes.


## Notes
- The efficient usage of localStorage is essential to Perfect Routing.
- Make sure the user cannot access the primary routes even if they alter the URL.
- There are files for both public and private routes on the component folder.


