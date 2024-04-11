This is a practice project to learn how spring security works.
<br/>
We have made Rest APIs in this project and each API is associated with authorized user.
<br />
Ex: 
<br/>
https://local:8080/home/public -> Any one can access this url
<br/>
https://local:8080/home/normal -> Normal user with correct credentials can access this url
<br/>
https://local:8080/home/admin -> Only admin can access this after successful login can access this
<br/>
<br/>
<br/>
Steps to run the project:
1. Clone the project
2. Run -> mvn clean install
3. Run the main function of the application: SpringSecurityTestApplication.java