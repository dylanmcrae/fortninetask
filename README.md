# fortninetask
HTML/CSS/JS project utilizing dynamic input components to validate strings

TWInput component takes an array of callback methods and props.
Whenever something is entered, the string is looped through all callback methods and calling them one by one.

If any of the callbacks return TRUE, validation has failed.