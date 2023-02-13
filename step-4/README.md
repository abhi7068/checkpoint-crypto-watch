---
name: API Calls Part 2
---

### Objective:
- Till now we are familiar with the API calls. In this half we will complete our checkpoint finally.
- First we will be working on the Chart of the Coin Page where the status of the coin will be displayed, we will be fetching data for the chart using the chart API.

``https://api.coingecko.com/api/v3/coins/${id}/market_chart?vs_currency=${currency}&days=${days}``

- Use the API, fetch the data and assign the data to the historicalData state.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676289888/Screenshot_20230213_173213_ku24ql.png" height="300px" width="700px" />

- At last we will be working on the Trending Coin component.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676290217/Screenshot_20230213_173806_ioeiuf.png" height="300px" />
 
- Move to the Carosel file and fetch the data from the trending API endpoint, and finally assign the response to the trending state.

  ``https://api.coingecko.com/api/v3/coins/markets?vs_currency=${currency}&order=gecko_desc&per_page=10&page=1&sparkline=false&price_change_percentage=24h``

## Note

- Make sure to visit the api.js file as all the required API endpoints are in this file
