# Favorite-of-favorite-color-finder
This is a simple code I made that can run on the console to help people decide on their favorite color among many of their favorite colors.
Simply run this in your Chrome browser console:


var name = prompt('What is your name?'); alert('Hi ' +(name) +'!'+ ' Welcome to Adam\'s favorites of favorite color finder!');

var instructions1 = alert('People change, and as we grow we find ourselves liking different things such as colors.');
var instructions2 = alert('Having a problem deciding on your favorite color now a days? Well I can help!');
var instructions3 = alert('You will be asked a a series of questions, and soon you will be given your results of your favorite color!');

var color1= prompt('First things first, lets establish a few colors you like! What is your 1st favorite color?');
var color2= prompt('What is your 2nd favorite color?');
var color3= prompt('What is your 3rd favorite color?');
var color4= prompt('What is your 4th favorite color?');
var color5= prompt('AND FINALLY!, what is your 5th favorite color?') ;

var color11_1v2= prompt('Which color do you like better, ' + color1 + ' or ' + color2 + '?');
var color22_3v4= prompt('Wow ' + color11_1v2 + ' is a great choice! Next question, which color do you like better? ' + color3 + ' or ' + color4 +' ?');
var color33_5v11= prompt('Facinating! You liked ' +color22_3v4+ ' more?! How about ' +color5+ ' or ' +color11_1v2+ '?');

var result= prompt('Interesting choice that you picked ' +color33_5v11+ '! How about ' +color33_5v11+ ' vs ' +color22_3v4+ '?!');
var thinking1 = alert('Ok, let me calculate our result.');
var thinking2 = alert('Still thinking... give me a second.'); 
var thinking3 = alert('Turning on our super computers to help calculate your result.'); 
var thinking4 = alert('BEEP');
var thinking5 = alert('BOOP'); 
var thinking6 = alert('BEEP');
var thinking7 = alert('BOOP');

var end = alert('OK! the results are in! We have concluded that out of all your favorite colors, you liked ' +result+ ' the best!');
var ending = alert('Now when people ask you for your favorite color, you can tell them your result today or try this again sometime in the future, but for now ' +result+ ' is your faovite color!');
