---
name: Authentication
---

### Objective:
- Authentication's main objective is to positively identify each user of our application, to identify each user and protect our programme from unidentifiable users, we will integrate authentication using the localStorage.

- Starting with registration, a form is already built for you, your task is to give fuctionality to it. Create a state and store the user data into it in the form of json.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676264128/Screenshot_20230213_102312_odsnlh.png" height="300px" width="700px" />

- Now when the user clicks on the register button, save the entered credentials to the localStroage of the User's Browser and navigate him to the login page.
 
 <img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676263348/Screenshot_20230213_101010_qfzqfd.png" height="300px" width="700px" />

- Here when the user clicks on the Login button and some how the user credential is wrong ALERT the user user with a message saying "Credentials are not valid"

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676265467/Screenshot_20230213_104536_qwsroh.png" height="300px" width="700px" />

- If the user enters correct credentials then the user should get the access of main page of our site.

##Notes
- User should not access the main page without a valid authentication.
- Make sure to store user's credentials in the form of json iin the local strorage. localStorage.setItem('credentials', JSON.stringify(credentials)) for registring credentials and JSON.parse(localStorage.getItem('credentials')) for getting Credentials
-Once the user is registered, in any way he should not reach to the login/register page and same if the user is not registered or logged in he should not reach to the main page of our site.
