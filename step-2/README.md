
## Step-2 Routing

- Routing is the process of redirecting a user to different pages based on their action or request. We will be using React Router in our application to navigate a user to a different page.

- Four pages make up our application. Even if an unauthorised person repeatedly tries to access the site by changing the url, he should only be permitted to view the login and registration pages. Without successfully registering, he will not be allowed to access the home page or the currency page. Our application's core pages, which contain the majority of its content, will be regarded as our private Routes, rendering anyone who hasn't authenticated unable to access them.

- Put the login and register pages inside public routes and the main page and the coin pages inside private routes.


## Notes
- The efficient usage of localStorage is essential to Perfect Routing.
- Make sure the user cannot access the primary routes even if they alter the URL.
- There are files for both public and private routes on the component folder.


