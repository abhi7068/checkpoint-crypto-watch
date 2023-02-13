---
name: Authentication
---

### Objective:
- Authentication's main objective is to positively identify each user of our application, to identify each user and protect our programme from unidentifiable users, we will integrate authentication using the localStorage.

- Starting with registration, a form is already built for you, your task is to give fuctionality to it. Create a state and store the user data into it in the form of json.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676264128/Screenshot_20230213_102312_odsnlh.png" height="300px" width="700px" />

- Now when the user clicks on the register button, save the credentials to the localStroage of the User's Browser and navigate him to the login page.
 
 <img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676263348/Screenshot_20230213_101010_qfzqfd.png" height="300px" width="700px" />

- The user will be asked to provide his name, email address, and password on the registration page. The user will be sent to the login page as soon as they click the registration button, saving their credentials as JSON data in local storage. The user credentials have now been saved to local storage. We will compare the login information with the registered credentials recorded in the local storage throughout the login process. If there are matches, we provide the user access to the main page.

