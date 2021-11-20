# GamerBux
 Project Report :
 
 [reportfinal.pdf](https://github.com/khansalikaziz/GamerBux/files/7574380/reportfinal.pdf)

Screenshots 
 
![sc9](https://user-images.githubusercontent.com/76683360/142201865-3d550c07-65bf-4009-a27b-27cd4fd1514a.jpg)

![sc10](https://user-images.githubusercontent.com/76683360/142201876-3d8f858d-378c-421b-918f-84e01e69784a.jpg)

![sc1](https://user-images.githubusercontent.com/76683360/142201883-99551015-85f6-4ef6-9e22-32f56eb7d9f7.jpg)

![sc2](https://user-images.githubusercontent.com/76683360/142201888-5abcdafc-3d55-4bef-8952-57d707c49a7c.jpg)

![sc3](https://user-images.githubusercontent.com/76683360/142201892-dba79ff1-637e-4d56-b1a1-e796c0fe5660.jpg)

![sc4](https://user-images.githubusercontent.com/76683360/142201897-837c83de-7d48-4970-8a7e-501188d9004c.jpg)

![sc5](https://user-images.githubusercontent.com/76683360/142201901-944ebb92-fda0-4e5f-bc79-484294a9b970.jpg)

![sc6](https://user-images.githubusercontent.com/76683360/142201904-469253e7-6a84-4662-b5af-dd1cd34234ba.jpg)

![sc7](https://user-images.githubusercontent.com/76683360/142201907-76569e7d-664b-463e-8c7e-7d218f9d4fc1.jpg)

![sc8](https://user-images.githubusercontent.com/76683360/142202206-f374e6e1-3e4a-4fb5-978b-fb3b5287fba7.jpg)


We are using firebase as our database and we are using pyrebase library to use it’s feature. The main reason for using firebase is that Firebase is a platform developed by Google(so there will not any security issues) and it is providing realtime access to data. 
For GUI I am using Kivy and purpose of using it is that Kivy is a free and open source Python framework for developing desktop application and other multitouch application software with a natural user interface. 
This authentication system includes several activities-:
1)	Main page /Login Page
	On this page there are 2 input fields which collect email and password from user.
	There is a login button which performs the authentication process from firebase database on click event(onclick) and if authentication is successful then user can access dashboard and if it is unsuccessful it will display an error message.
	And there are two links ,the first will navigate user to forgot password page and the second one will navigate user to signup page.
2)	Forgot password page
	This page contains back button on top which will navigate user to main page on button click(onclick).
	There is an input field which collect user email to reset password and there is a button (send login link-:button name)which will send link to reset password on that email.
3)	Signup page
	This page contains back button on top which will navigate user to main page on button click(onclick).
	On this page there are three input fields which collects username , email and password respectively.
	There is a signup button which check if all details are valid or not  on click event(onclick) and if details are valid it will display a signup success message and if details are invalid it will display an error message.




