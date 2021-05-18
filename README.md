# spring-security-oauth
Example to use OAuth login using github.

1. Create an application in github, use client id and client token in our app.

2. start app, http://localhost:8080/ will redirect to github and ask use for github authentication
3. On successfull login in github, it will return a token to our app which means it has authenticated from github hence a valid user.
4. We can open /user url to verify our login name and other details recieved from github account.

5. Same setup can be done for ggoogl as well.
