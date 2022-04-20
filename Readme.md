Register/Login Procedure
Register :
=> Front-End will display the input fields that you want to capture from the user.like name,age,email etc.
=> User will be providing the details in the fields,then he will click on submit button or signup button.
=> Front-End will verify if all the fields are properly filled and correct.
=> Front-End will be having an Api call which will pass this complete data in Api to Backend.
=> Now the Details will be store in DataBase.
  
Login :
=> Front-End will take data from user like emailor usernameand password. 
=> Click to Login Button,then Front-End will call an Api from Backend and will pass Email and Password to it.
=> Api comes up with different types of error messages , like if the email and password is not provided then message would be
        "please provide required details".

=> if mails is not already present in database, then message would be "given mail is not Registered,please Register" password's hashed value will be created once againand then it willcompare it with the one saved in DataBase,if it returns then home page if not then error message will be : 
"your password is incorrect, please try with correct password." 