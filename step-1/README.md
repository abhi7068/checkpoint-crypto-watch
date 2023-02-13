---
name: Routing 
---

### Objective:
- Routing is the process of redirecting a user to different page based on their action or request. We will be using React Router in our application to navigate a user to a different page.

- Four pages make up our application. If a user visites our application, the user will be prompted with the login page and if the user is not register then he will be asked to register first.

 <img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676264128/Screenshot_20230213_102312_odsnlh.png" height="300px" width="600px" />

-After successful registration the user will be routed to the login page, and will be asked to enter the same credentials with which he registered.

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676263348/Screenshot_20230213_101010_qfzqfd.png" height="300px" width="600px"/>
 
-Finally the User will be redirected to the main page of our site after successful login.
- On the main page if a user clicks on any coin he should get redirected to the page along with the ID of the coin on the URL
``<Route path='/coins/:id' component={CoinPage} />``

<img src="https://res.cloudinary.com/dn83xtspp/image/upload/v1676261601/Screenshot_20230213_094010_ik3zjt.png" height="300px" width="600px" />

### Note:
- Make sure you are following the instructions properly.
- The efficient usage of localStorage is essential to Perfect Routing.
- Make sure the user cannot access the primary routes even if they alter the URL.
