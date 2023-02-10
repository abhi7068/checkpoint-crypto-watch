
## Step-1___Authentication


- Authentication's main objective is to positively identify each user of our application. Similar to how you're always prompted to enter your email and password to confirm your identity while logging into your preferred social networking application.

- To identify each user and protect our programme from unidentifiable users, we will integrate authentication in our application.


- We'll move on to user registration after starting with user login. In other words, as soon as the user's browser loads our page, it determines if they are authorised and prompts them to log in with their credentials. If the user is not already registered, he will be required to register before being requested to log in a second time. Following a successful login, the user may browse the remaining pages of our software.

- When a new user arrives on our website, our first responsibility is to show him our login page. If the user successfully enters his credentials, he will be sent to our home page, otherwise, if the user is not yet registered, he must register by selecting the register option located beneath the form.

- The user will be asked to provide his name, email address, and password on the registration page. The user will be sent to the login page as soon as they click the registration button, saving their credentials as JSON data in local storage. The user credentials have now been saved to local storage. We will compare the login information with the registered credentials recorded in the local storage throughout the login process. If there are matches, we provide the user access to the main page.







## Screenshots

[App Screenshot](https://res.cloudinary.com/dn83xtspp/image/upload/v1675958471/Screenshot_20230209_210042_a9rccg.png)


# Objective :

Build the App Component which should be the base Component to showcase all other child Components like Navbar, banner and row Component.

