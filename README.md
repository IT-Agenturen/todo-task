# ToDo Application

### Project Architecture to be used (MANDATORY)
1. Clean Code Architecture + MVVM Arhcitecture  
2. Set Alarm of each and every ToDos created.
3. Display Local push notification. (contains Title, Description, DataTime)


### Libraries to be used
1. Room DB (Add 1 small migration scenario)
2. Retrofit + Coroutine 
3. JUnit test cases(If Possible) 


### Total 3 Screens: 
1. Login Screen. 
2. Home Screen. 
3. Create/Update ToDo Screen. 


### Acceptance Criteria:- 
1. Login screen 
    - Email (Email validation) 
    - Password  
    - [LOGIN] button 
    - POST https://reqres.in/api/login 
        
          Request Body (application/json):  
          {  
            "email": "eve.holt@reqres.in", 
            "password": "cityslicka" 
          }

          Response : 
          {  
            "token": "QpwL5tke4Pnpja7X4" 
          } 
        
2. Home Screen 
    - List of Added ToDos (Fetch it from Room Database) 
    - Users can Delete Todo by clicking the list item. 
    - Create ToDo (+) Button 

3. Create / Update ToDo Screen (Save it to Room Database) 
    - Title* 
    - Description 
    - Time (HH:mm)* 
    - Date (dd/MM/yyyy) 
    - Types: ◉ Daily and ◉ Weekly *  
    - CREATE button 


For Ex:
If 1st ToDo is created at 4:00 PM for type Daily then the app will notify daily at 4:00 PM.
If 2nd ToDo is created at 5:00 AM, 28 May 2021 for type Weekly then the app will notify weekly at 5:00 PM starts from the selected date. 

Notes: Maintain Proper Project Structure, Coding standards, naming conventions, and validations.
