# Marathon-Form
A form to register for a marathon

This is a basic webpage that uses simple HTML elements within a form for a user to be able to sign up and choose which race they would like to participate in.

The form starts with a link to reference the CSS stylesheet. 

Afterwards there is the body element which contains all the HTML code.  The body contains the Header which holds the H1 element.

Following the header is the Form attribute.  The form attribute contains the majority of all the code and is broken up into several divs to be able to style them more distinctly.  

The name div contains a label and a text input filed for the first and last name.  
In order to select which race the user wants to participate in they have to select from the 3 radio buttons within the "race" div.  By default the Full Marathon is selected.

An email and password are then required along with the age group of the user.  There are only 2 age groups.  Those being 18 and above and 6 - 18.  No one under 6 may participate for legal reasons.  

At the bottom of the page is the Submit button which then sends the information to the server which will be setup at a later time.  

<!-- UPDATE 3/22/2022-->

Added more styling to the form along with basic password validation.  
Now along with all the fields being required the password is also requiring a length of 7 characters in conjunction with one number, one lowercase, one uppercase character.

The button has been styled a bit.  Added 2 shadows to the h1 and h4 attribute.  The background now has color with opacity.  There is a fixed footer with a copyright message

<!-- UPDATE 4/08/22 -->
  Added some text and info to the sections within the grid (this filled out the webpage a lot more)
  Began creation of a Form Popup using Webkit, Animation and JS onClick() 
