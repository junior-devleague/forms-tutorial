# Forms Tutorial
[Intermediate] HTML/CSS/JS - Basic forms 


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
### HTML
#### Input
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
  
#### Select
- Defines a drop-down list
```
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
 ```
  
#### Text Area
- Multi-line input field
```
<textarea rows="4" cols="50">
Bacon ipsum dolor amet ham hock burgdoggen ball tip sirloin. Ribeye pork buffalo short ribs short loin drumstick meatball burgdoggen pig tail. Pork landjaeger shank cupim pork belly salami bresaola pancetta hamburger pork loin. Tenderloin pastrami burgdoggen pancetta pig. Buffalo ribeye pastrami sausage boudin. 
</textarea>
 ```
### Javascript
#### AddEventListener Submit
- wrap all of your code within
```
window.onload = function() {
 // your code here
};
```
- Use the event name `submit` and attach the `addEventListener` method to the HTML form ID
  - `document.getElementById("myForm").addEventListener("submit", myFunction);`
- use `.value` property to get your input value https://www.w3schools.com/jsref/prop_option_value.asp
- use `event.preventDefault()` to stop form from refreshing
- use `reset()` method to clear input after submit



