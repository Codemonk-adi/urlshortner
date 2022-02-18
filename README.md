# URLshortner


https://user-images.githubusercontent.com/56336914/154612832-9f2921c6-15a7-4dbb-adf6-4114b1a5928c.mp4

This service makes transfering text and code easier and secure, as a bonus it also doubles down as a url shortner.
A registered user can sign in and enter Text/uploadtext files/paste in the text area and has the option to enter a key for encryption.
upon submission, a shortened url is generated, clicking the link takes the user to the frontend where the time and ip address is logged and the data is decryted if needed.

Track route lists all the queries for the user with the ip address and time of access,
delete route deletes the query and the renew route extends the life of the link.

links get deleted after a day using TTL in mongodb.

Tech Stack

Backend is built using node and express and MongoDB is used to store the user info as well as the query details. Heroku is used to deploy the backend.

React is used in frontend and is deployed on netlify.

<b>Deployment Link </b>

Backend: https://consise-farms.herokuapp.com/


Frontend: https://polynomial-front.netlify.app/signin

<video src='https://github.com/Codemonk-adi/urlshortner/blob/master/Polynomial-Demo.mp4' width=180/>

![Demo Video](https://github.com/Codemonk-adi/urlshortner/blob/master/Polynomial-Demo.mp4)
![Home Page](https://github.com/Codemonk-adi/urlshortner/blob/master/Home-page.png)
![Signup](https://github.com/Codemonk-adi/urlshortner/blob/master/signup-page.png)

  

