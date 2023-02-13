---
name: API Calls Part 2
---

### Objective:
- Till now we are familiar with the API calls in this half we will complete our checkpoint finally.
- First we will be working on the Chart of the Coin Page where the status of the coin will be displayed, we will be fetching data for the chart using the chart API.
- Use the API, fetch the data and assign the data to the historicalData state.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676289888/Screenshot_20230213_173213_ku24ql.png" height="300px" width="700px" />

- Use CoinTable API in the api.js file in the config folder to the fetch the data and get the response, finally the response should then be assigned to the state.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676276553/Screenshot_20230213_134949_ynvtol.png" height="300px" />
 
- Now finally we are done with our Coin Table, but what if the user wants to know more about a particular coin, so for that we will fetch data for that Single Coin as well, but before that we will make sure that when a user clicks on a coin the Id of the coin is passed properly in to the url. In our case the ID is the name of the coin itself.

  ``https://cryptoowatch.vercel.app/coins/bitcoin``
  
- In the coin page we have to fetch data for the single coin using the id from the URL and display the data on the page.

## Note

- Make sure to visit the api.js file as all the required API endpoints are in this file
