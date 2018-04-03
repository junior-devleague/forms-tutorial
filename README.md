# Forms Tutorial
[Intermediate] HTML/CSS/JS - How to set up basic form with functionality


## What are forms?
Forms are used to collect user inputs. Allows user to send data to the website. We can send information like, name, email, birthday, login name, password, and etc. 

## Live-Code 
- Forms are created in HTML with the `<form></form>` tag
- Form Elements are nested within the `<form>` tag
  - Form Elements:
    - `<input>`
    - `<select>`& `<options>`
    - `<textarea>`
  - Form Attribute:
    - `value`
    
### Input
- Input type: Text
  - Defines a one-line text input field
  - `<input type="text" name="firstname">`
- Input Type: Pasword
  - Will mask your password as you type
  - `<input type="password" name="psw">`
- Input Type: Submit
  - Submits data to your backend and Javascript
  - `<input type="submit" value="Submit">`
- Input Type: Radio
  - User can select ONLY ONE of the choices
  - 
  ```
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
  ```
- Input Type: Checkbox
  - User can select 0 or more options
  - 
  ```
  <input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
  <input type="checkbox" name="vehicle2" value="Car"> I have a car 
  ```
- Input Type: email
  - Validates and should contain an email address
  - 
  ```
   E-mail:
  <input type="email" name="email">
  ```
  
### Select
- Defines a drop-down list
```
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
 ```
  
### Text Area
- Multi-line input field
```
<textarea rows="4" cols="50">
At w3schools.com you will learn how to make a website. We offer free tutorials in all web development technologies. 
</textarea>
 ```
 
### AddEventListener Submit
- `document.getElementById("myForm").addEventListener("submit", myFunction);`
- use `event.preventDefault()` to stop form from refreshing
- use `reset()` method to clear input after submit



