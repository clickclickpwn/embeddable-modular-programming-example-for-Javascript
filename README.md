# embeddable-modular-programming-example-for-Javascript


A trick I learned from working with CHATGPT, to solve an interesting problem I had.

***How do we create modules of javascript, thats embeddable across the web, in one copy paste code, like you can do with google sites***?


Many programmers use _import_ and _export_, and multiple files, but I wanted to have it all one copy and paste, and have it leggible.


How this trick works is, you create your modules with the script tag, then you give them Id's to be called as objects.


# Modules are just individual ***scripts*** in seperate files. 

The difference between this and regualar module programming of javascript is:



It has to be layered in a specific order, like you do within an algorithm.

_This is due to how the DOM loads things in HTML_.

***Its an HTML file, not a javascript one***.



With this trick, you can create individual callable scripts as objects, that can be further troubleshot and debugged,

_all embeddable_.




***To check if it works, run the file, which is a blank white screen, and hit inspect to read the console.log to see the sum equal***

4



Two scripts interacting and calling each other, from two seperate tags in the same html file.


This is Unlicensed, as a thank you to ***<sup>god</sup>*** for giving me the privilege, Codecademy for the free knowledge, and chatGPT for the free helper to solve this complex problem that school couldn't.



I may provide more complex examples later.
