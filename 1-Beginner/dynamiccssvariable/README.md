# Dynamic CSS Variables

<p align="center">
  <img width="1024" height="600" src=".images/test.gif"></img>
</p>


**Tier:** 1-Beginner

CSS variables are a powerful tool that lets the developer associate a symbolic
name with a value, and then use that name in the stylesheet wherever that
value is required. The advantage is that when a change to that value is 
required it only needs to change in the CSS variable definition rather than in
the many spots it may be used.

What can make this even more powerful is to dynamically change the value of a
CSS variable at runtime.

The goal of this app is to dynamically change the background color of text boxes
based to let you gain experience using both CSS variables and dynamically 
changing them from within the app.

**you need to download the image given in the image credits to make sure the image is shown**

- Install `PyQt5` before running the program
- `python3 main.py` to run the program

## User Stories

-   [x] User can see three two boxes to be used to enter a User ID and Password
along with 'Cancel' and 'Login' buttons underneath them. The default background
color of the text boxes is white.
-   [x] User can enter a user id and password into the text boxes.
-   [x] User can click the 'Login' button to validate the user id and password.
-   [x] User can see a warning message if one or both of the text boxes contains
spaces and the background color of the empty text box will change to light
yellow.
-   [x] User can see a warning message if the user id doesn't match 'testuser'
and the background color of the text box will change to light red.
-   [x] User can see a warning message if the password doesn't match 'mypassword'
and the background color of the text box will change to light red.
-   [ ] User can click the 'Cancel' button to clear the text boxes and reset
their background colors to white.

## Bonus features

-   [x] User can see the color of the text box border change when an error is
detected
-   [ ] User can see the size and font of the contents of the text box change
when an error is detected.

## Useful links and resources

- [Custom properties (--*): CSS variables (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
- [CSSStyleDeclaration (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration)

## Example projects

[Dynamic CSS Variables](https://codepen.io/gordawn/pen/oOWBXX)
[Image Credits](https://unsplash.com/photos/feW76yDP2Ow)
