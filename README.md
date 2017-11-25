# christmas-countdown

Christmas is almost here! But... when? Create a countdown to Christmas with HTML, CSS, and JS!

![Countdown Example](https://github.com/junior-devleague/christmas-countdown/blob/master/christmas-countdown.gif)

## Objective

Use the **JavaScript Date Object**, **CSS Keyframe Animations** and the **Window setInterval** method to display a clock, winter animation, and countdown to Christmas on the page.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of Flexbox.
* Basic understanding of JavaScript and DOM.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
* JS file
3. Link all of your files correctly.

### Part II HTML

To complete Part II, fulfill the following requirements:

1. Create a ```div``` with an ```id``` of 'container'.
2. Inside of this div, create the following and maintain the nested relationships:
* ```div``` with an ```id``` of "main"
  * ```div``` with ```id``` of "clock"
  * ```div``` with ```id``` of "christmas-time"
    * ```h1``` with ```id``` of "update"
* ```div``` with an ```id``` of "bottom"
  * ```div``` with a ```class``` of "snow" and ```id``` of "mound1"
  * ```div``` with a ```class``` of "tree" and ```id``` of "tree1"
  * ```div``` with a ```class``` of "layer" and ```id``` of "layer1"
  * ```div``` with a ```class``` of "snow" and ```id``` of "mound2"
  * ```div``` with a ```class``` of "tree" and ```id``` of "tree2"
  * ```div``` with a ```class``` of "snow" and ```id``` of "mound3"
  * ```div``` with a ```class``` of "layer" and ```id``` of "layer2"
  * ```div``` with a ```class``` of "tree" and ```id``` of "tree3"
  * ```div``` with a ```class``` of "snow" and ```id``` of "mound4"
  * ```div``` with a ```class``` of "snow" and ```id``` of "mound5"
  * ```div``` with a ```class``` of "layer" and ```id``` of "layer3"

### Part III CSS

To complete Part II, fulfill the following requirements:

1. Target the ```body``` element.
* Set its ```margin``` property to 0.
* Set its ```box-sizing``` property to ```border-box```.
* Find out how to change a font with a font from https://fonts.google.com/
2. Target the ```container``` id.
* Set its ```height``` property to 750px.
* Set its ```width``` to 100%.
* Activate flex box! *Hint: The property starts with a d!*
* Set its ```justify-content``` property to ```space-between``` so that the elements are spread out to the entire height of the page.
* Center it horizontally using Flex Box.
* Set the direction that the elements will line up to ```column```. *What Flex Box property deals with direction that the elements line up?*
3. Target the ```clock``` id.
* Set the color to ```rgb(30,30,30)``` to get a slightly less black color which is more appealing to the eye on a webpage.
* Set the ```font-size``` property to something relatively big (~300px depending on your font).
* Activate flex box!
* Center the elements horizontally and vertically with Flex Box.
4. Target the ```main``` id.
* Activate Flex Box!
* Center the elements horizontally and vertically.
* Make the direction of how the elements line up to a column. *Which Flexbox property allows us to modify the direction that elements will line up?*
5. Target the ```bottom``` id.
* Set its ```width``` property to 100%.
* Set its ```position``` to absolute.
* Set its ```bottom``` property to 0px.

**Snow**
6. Target the ```snow``` class.
* Set its ```width``` property to 220px.
* Set its ```height``` property to 190px.
* Set its ```border-radius``` property to ```300px / 270px```.
* Set its ```background-color``` property to white. However, if you want to see if it appears, you can change the color to something else initially.
* Set its ```position``` property to absolute.
* Set its ```bottom``` property to 0px.
* Set its ```box-shadow``` property to ```10px 15px 20px 8px rgba(0,0,0,0.30)```.

**The Trees**
7. Target the ```tree``` class.
*Since we want this to be a triangle, we're going to have to do some different things!*
* Set its ```width``` property to 0px.
* Set its ```height``` property to 0px.
* Set its ```border-left``` property to ```50px solid transparent```.
* Set its ```border-right``` property to ```50px solid transparent```.
* Set its ```position``` property to absolute.
* Set its ```bottom``` property to 0px.
7. Target the ```tree1``` id.
* Set its ```bottom``` property to 50px.
* Set its ```border-bottom``` property to ```200px solid rgb(82, 164, 112)```.
8. Target the ```tree2``` id.
* Set its ```bottom``` property to 40px.
* Set its ```border-bottom``` property to ```200px solid rgb(18,95,83)```.
9. Target the ```tree3``` id.
* Set its ```bottom``` property to 30px.
* Set its ```left``` property to 100px.
* Set its ```border-bottom``` property to ```200px solid rgb(59,237,109)```.

**Layers**
10. Target the ```layer``` class.
* Set its ```width``` property to 100%.
* Set its ```position``` property to absolute.
* Set its ```bottom``` property to 0px.
* Set its ```background-color``` property to white.
11. Target the ```layer1``` id.
* Set its ```height``` property to 170px.
12. Target the ```layer2``` id.
* Set its ```height``` property to 150px.
13. Target the ```layer3``` id.
* Set its ```height``` property to 130px.

**Keyframe Animations**
14. Create a ```CSS Keyframe Animation``` called translate. *Hint: Use https://www.w3schools.com/css/css3_animations.asp*
* This animation should begin with the ```opacity``` property set to 0.
* At 10%, set the ```opacity``` property to 1.
* At 80%, set the ```opacity``` property to 1.
* At 90%, set the ```opacity``` property to 0.
* At the very end, set the ```transform``` property to ```translateX(calc(100vw))```. This means that it will calculate the length of the entire view width (vw) and translate the elements across the entire page.
15. Let's assign this animation to our moving elements! Go to your ```snow``` class.
* Add an ```animation-name``` property and set that to the name of your animation.
* Add an ```animation-iteration-count``` property and set that to ```infinite```. This means that the animation will continuously repeat.
* Add an ```animation-timing-function``` property and set that to ```linear```. This means that the animation will play with the same speed throughout. Do these same steps to your ```tree``` class.
16. Target the ```mound1``` id.
* Set the ```animation-duration``` property to ```10s``` (10 seconds).
17. Target the ```mound2``` id.
* Set the ```animation-duration``` property to ```9s```.
18. Target the ```mound3``` id.
* Set the ```animation-duration``` property to ```8s```.
19. Target the ```mound4``` id.
* Set the ```animation-duration``` property to ```7s```.
20. Target the ```mound5``` id.
* Set the ```animation-duration``` property to ```6s```.

Check to see that your snow mounds are moving! Now that you've made them move, let's move the trees. Go to where you've targeted the ```tree1```, ```tree2```, and ```tree3``` ids. Set the ```animation-duration``` property of these trees to ```10s```, ```8s```, and ```6s``` respectively.

### Part IV JS
To complete Part II, fulfill the following requirements:
1. Begin your code with a function that will start onload of the window as follows:
```JavaScript
window.onload = function() {
  //Put all of your code in here!
}
```
2. Store your ```div``` with the ```id``` of ```clock``` and ```h1``` with the ```id``` of ```update``` in variables. *Hint: Use document.getElementById()!*
3. Create a ```setInterval``` method that takes in a function called ```updateTime``` and will run that function every second.
5. Create a function called ```updateTime``` .
* In this function, create a variable called date that will store a new ```Date``` Object.
* Create a variable called hours that will store the hours using your date variable.
* Create a variable called minutes that will store the minutes using your date variable.
* Create an if statement that checks if hours is greater than 12. If so, set the variable hours equal to ```hours - 12```. This is so you don't view time like 22:23.
* Create another if statement that checks if minutes is less than 10. If so, set the clock's ```innerHTML```  to a string that takes in hours and minutes to form the time (such that 4:09 does not appear as 4:9). Else, set the clock's ```innerHTML```  to a string that takes in hours and minutes to form the time.
6. Create an if statement that checks if the current month is December.
* If so, create another if statement within it that checks if the current date is less than 25.
* If so, create a variable called countdown and set that equal to 25 - the current date.
* Create an "else if" statement that checks if the current date is equal to 25. If so, change the innerHTML of the update element to "Merry Christmas!".
* Create another "else if" statement that checks if the date is greater than 25. If so, update the innerHTML to "A year until Next Christmas!"
* Create an "else" statement. In this else statement, create a variable called countdown that subtracts ```date.getMonth()``` from 11. Then, update the innerHTML to display how many months are left until Christmas!
