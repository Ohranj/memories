# Memories

### https://memories-app-1.herokuapp.com/

Login with:
memorytest123@outlook.com and password
memory123

The project allows users to login and upload memories. Memories consist of an image and a description. A randomly selected memory is then emailed out each morning. Additionally the user can input additional emails to also recieve a copy of the memory.

You can view emails that were sent logging into outlook via memory2demo@outlook.com and password memory456

### Tech used

Built with react, node, express, mondoDB

<!-- prettier-ignore -->
* Redux. Included to help with practicing it more than anything
* Nodemailer. Used to time email being sent each morning
* Cloudinary. Used to store a users memory images in the cloud
* MongoDB. Stores user details as well as links to their memory image stored in cloudinary
* Passport.Used to handle user sessions

### Additional features include:

<!-- prettier-ignore -->
* Register an account or login with google
* Sort images dependant on their class (achievement, holiday, birthday etc) or date
* Click a memory card to bring up its description
* Delete a memory
* Change users account profile image

User can create an account or login with google

### Images

Home page allowing users to register or login with google
![Image of login page](https://github.com/Ohranj/Memories/blob/master/login.PNG)

Dashboard where users can view and filter their upload memories
![Image of login page](https://github.com/Ohranj/Memories/blob/master/dashboard.PNG)

Upload page. Here users upload their image
![Image of login page](https://github.com/Ohranj/Memories/blob/master/upload.PNG)

Account page. Users can upload a new profile image, and input additional emails to recieve memories inside a scrollable container
![Image of login page](https://github.com/Ohranj/Memories/blob/master/account.PNG)

Note that memories are due to send every minute to help with demo, due to heroku restrictions causing dyno to sleep when not is use
