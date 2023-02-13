---
name: API Calls
---

### Objective:
- API stands for application programming interface, which is a set of definitions and protocols for building and integrating application software, Like YouTube API allows developers to integrate YouTube videos and functionality into websites or applications. Twitter offers Twitter APIs for embedding tweets.

- In our checkpoint we will be using [coingecko.com](https://coingecko.com) APIs for fetching coin data.
- In the Home Page we will be having a Coin table that will contain all the coins and their data respective. Our responsibility will be to fetch the data from the CoinTable API in the api.js file in the config folder.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676271839/Screenshot_20230213_121835_g789ts.png" height="300px" width="700px" />
 
- The API will return an array of coin with their realtime data.
- To fetch the image of the movie, you need to use the `backdrop_path` which is returned by the above API and make a call to the following URL:
    - ``https://image.tmdb.org/t/p/original/${backdrop_path}``
- The Banner component should be imported inside the `App` component and should be rendered inside the `App` component after `Navbar` component.

### Note:
- You should be making changes in the Banner.js file, which is present inside the `components` folder.
- All the CSS styles are already present inside the `Banner.css` file, which is present inside the `components` folder. so make use of it!

### Expected output:

<img src="https://ik.imagekit.io/hashinsert/hash-learn/Screenshot_20230128_054847.png?ik-sdk-version=javascript-1.4.3&updatedAt=1674908353162" height="300px" width="600px" />





## API Calls

- Our checkpoint's final and most crucial part is teaching you how to use API calls.
- There are 4 instances in the application where you will use API calls; the API endpoints are listed in the config folder's api.js file.
- Use the CoinList endpoint to get the list of coins to display on your website.
- The SingleCoin API endpoint should get the details of a particular coin when a user clicks on it and display them on the singleCoin page.
- The Chart that is displayed on the Single Coin page is accessible via the third API endpoint in the api.js file.
- The Trending CoinList endpoint appears at the conclusion. You'll utilise this Endpoint to get the popular Coins.

