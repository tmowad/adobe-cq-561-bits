+ fix-cq-error-dialog-bookmarklet.js
--> So I've found CQ's error dialogs (in the content editing screen) to be, while rare, annoying when they happen, since they're set at 100px wide, 
which is too narrow to read.  After manually digging into the DOM a few times of getting this error, I decided to try my hand at some simply jQuery
and to figure out how to "run javascript as a bookmark" (aka create a bookmarklet).  This works for me right now, but if it doesn't work for you,
feel free to modify or shoot me a comment as to where its breaking, and we'll see if we can make the solution "just work" in more places.  
