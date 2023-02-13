---
name: API Calls
---

### Objective:
- Application programming interface, or API for short, is a collection of definitions and protocols for creating and integrating application software. Like Twitter offers Twitter APIs for embedding tweets on our site, YouTube API enables developers to incorporate YouTube videos.
- To retrieve coin data for our checkpoint, we will use the [coingecko.com](https://coingecko.com) APIs.
- In the Home Page we will be having a Coin table that will contain all the coins and their data respective.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676271839/Screenshot_20230213_121835_g789ts.png" height="300px" width="700px" />

- Use CoinTable API in the api.js file in the config folder to the fetch the data and get the response, finally the response should then be assigned to the state.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676276553/Screenshot_20230213_134949_ynvtol.png" height="300px" />
 
- Now finally we are done with our Coin Table, but what if the user wants to know more about a particular coin, so for that we will fetch data for that Single Coin as well, but before that we will make sure that when a user clicks on a coin the Id of the coin is passed properly in to the url. In our case the ID is the name of the coin itself.

  ``https://cryptoowatch.vercel.app/coins/bitcoin``
  
- In the coin page we have to fetch data for the single coin using the id from the URL and display the data on the page.

## Note

- Make sure to visit the api.js file as all the required API endpoints are in this file
