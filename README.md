# JavaScript30 

This is my work on the JavaScript30 course by Wes Bos.
My method of learning and working on these courses is to code along with Wes, but pasuing the videos and trying to figure out and write the JS code myself to see whether or not I am able to get it to work properly before watching the tutorial.
I will journal how I felt and dealt with each course, any struggles I might have had, anything I felt comfortable or knew, or anything that is brand new to me.

<br>
My goal is to complete this course in consecutive 30 days.  
However if I feel I need more time to focus on the concepts of what is being coded, then I'll take more time as needed.
It is far more important to understand the code itself than to hastily run through projects while learning.

<hr>

Day 1: JAVASCRIPT DRUM KIT (completed: 8/21/2022)

I do not have a file for the Drum Kit.
While working on the code I was unable to get the .play() method to work on Google Chrome, Microsoft Edge, FireFox, or FireFox Developer Edition.
While looking up to figure out while it wouldn't play the sounds I came across a question about the very same project on StackOverflow where someone had said that Chromes recent update had made that play() method hard to execute.
I still haven't been able to try to figure out why it doesn't make a sound on the other platforms.  But I do plan to go back to that project and try to resolve the situation.

*UPDATE* 

The issue with the sounds not playing has been discovered. The file names for the sounds were different from the sound names listed in the starter files. Once I went through them and updated them, everything worked perfect. This was a fun one to do.  I'm a big music fan and have been playing drums since I was 8 years old (obviously I'm not great at them otherwise I'd be a rockstar...maybe). Also I am currently working on a project in which using keydown in an event listener is going to be very useful so the code here will definitely be a good referral guide once I get to the JavaScript stage of that project (if I've completed the project, you can view it right here => (add link to project)). 

<hr>

Day 2: CSS + JS CLOCK (completed: 8/17/2022)

This one I found to be a little bit easier.
In the oast few months I have coded along with 2 clock/time tutorials with Traversy Media (link to project here => https://www.youtube.com/watch?v=fSTQzlprGLI) and Web Dev Simplified (link to project here => https://www.youtube.com/watch?v=Ki0XXrlKlHY).
So I had a basic idea of working with setInterval to 1000 and math operations to get the hands to rotate for the different times.
I did have a few struggles with getting the hands to connect to rotate, but it was mostly syntax errors (ie. leaving the "deg" at the end off of `rotate(${secondsDegrees}deg), etc.`)
This was a fun project and I plan to do some more projects on my own with time and clocks in the future. 
I also made the second hand a dark shade on red, just for a better aesthetic feel. 

<hr>

Day 3: CSS VARIABLES (completed: 8/19/2022)

I liked doing this one because of being able to see how to connect the various areas and change them individually and as a group (the background color and the 'JS' color matching).  I had attempted to try to do this one ahead of watching the code that Wes used, but as soon as he started adding the variables into the style tags, I decided to follow and code along in case I missed something.  I have seen and worked with CSS variables before, but mainly using colors.  One issue that I did come across, but nothing major to break the code, was the mousemove event.  Looking at the console after applying it with the change event, it was not giving me any information.  However, being that the code did work, I wasn't too hung up on it.  I will go back and take a look and see if possibly my syntax was wrong or if there was something that I should've done instead. 

<hr>

Day 4: ARRAY CARDIO DAY 1 (completed: 8/20/2022)

I'm glad that this one showed more of how to use map, filter, sort.  I have gone through those many times but I still get confused by them simply because I do not use them often enough. I do need a lot more practice with these methods, but after completing this I think I'm going to try to do this "cardio" exercise again. Being that I need the practice not just with the coding but with the thought process, this should be good to try. On exercise 5, I did manage to come up with the response alone using a ternary operator based on the answer to exercise 3.  The only issue I had with the return was the -1 and 1.  I initially got them mixed up, so I need to practice that more to get a better understanding of how to correctly use them.  Overall I felt that this was a very helpful video and will be revisiting this one a bit to get better.

<hr>

Day 5: FLEX PANEL GALLERY (completed: 8/21/2022)

Flexbox. I felt that I was learning more about flexbox in this video than I was JavaScript. But that's awesome as well! Flexbox is certainly tricky to get. I still have a lot of problems getting it correct and understanding the different values and how they work.  As far as the JS goes, there was definitely a lot of "toggle" going on.  I have trouble sometimes understanding how toggles work, but I feel like I'm starting to get a better idea. Another JS issue I have is understanding how and when to use events in a function (ie. function(e)).  I'll come back to this video some more for reference as Wes was saying that all the browsers except Safari noted as only flex and not flex-grow.  I'll go back for some more clarification for sure. 

<hr>

Day 6: TYPE AHEAD (completed: 8/22/2022)

This one was a bit more challenging for me.  As soon as Wes started getting into the code, I was already feeling thrown off. Also it could be that I'm a bit tired too... It's been a long day.  Using fetch and .then methods and using APIs is definitely something that I do need more practice with.  Every API that I have dealt with so far has been some sort of code along project and not anything of my own.  So I do need to practice there and find some good APIs to work with. The RegExp is something that is entirely new to me.  I haven't seen that before so I need to look more into that.  Wes might've explained it but I do need to look into it. I had a hard time understanding the use of it. Overall this one was cool. I surely have to come back to this one and practice more on this.  Also bonus points for my home city and my current city both making the list. 👍

<hr>

Day 7: ARRAY CARDIO DAY 2 (completed: 8/24/2022)

So this exercise felt a lot more comfortable than the previous once.  The only problem that I stumbled upon a bit was the findIndex() and then deleting one of them.  I was trying to nest functions to try to use the delete() method, but quickly found myself confused and needing to backtrack.  Even though using the splice() method is easier to type out and looks nicer, I kind of preferred the slice() method instead. It reminded me of when I do editing in music or videos where you need to split something and either add something in between or remove a section that you don't need (just like in this case with the ID). After the first exercise I did try to solve them myself before watching Wes, and one of them I got correct and wrote out the ternary operation for it, but went the extra mile right true and false instead of just letting it equate to true (const comment = comments.find(comment => comment.id === 823423... initially I ended it with the ? true : false which it didn't need).  I like these array cardio exercises.  They're definitely going to be resourceful for me in the future when they'll need to come in handy. I don't know if there are any more of these in the course but we will find out.  

<hr>

Day 8: FUN WITH HTML5 CANVAS (completed: 8/25/2022)

This was a really fun exercise.  I never really thought about drawing, clicking and dragging on a page for art as a JavaScript exercise. There was definitely a TON of code for this one, but it did make sense for me as Wes explained it. I learned a lot of new things with this lesson as well.  This was my introduction to getContext.  I had seen it before but never seen context used in any code that I've worked on. So it was definitely cool to check that out. A lot to pick and go through in this video, but thoroughly enjoyed it.  I'm going to load up this one up to Netlify as well so my girlfriends kids can draw stuff on the computer, they'll love it.  8 videos in... Let's go!

<hr>

Day 9: DEV TOOLS DOMINATION (completed: 8/26/2022)

console.log('We are all up in the %s console today!', 'fucking');

console.log('%cHELL YEAH!', 'font-size:1000000px;');

A bit of overkill I know.  But I do enjoy working in the console.  Having a place to work on figuring out solutions and finding out information on what you are looking for is super important in coding.  I feel like I don't pay as much attention to the Dev Tools as I should.  There's definitely a lot of information there and some of these different console types were new to me.  I was aware of log obviously, but was unaware of most of them.  These will come in handy when I start working more in the console on projects I'm sure. This video was definitely informative for sure.

<hr>

Day 10: HOLD SHIFT AND CHECKBOXES (completed: 8/27/2022)

In this video Wes suggests at the beginning for the viewer to try and do the code themselves before watching the video.  I tried that and I put a querySelectorAll and a forEach loop on the .item, not .checkbox.  Soon after that I felt lost for a bit while watching him code.  It might just be that I'm tired (currently operating on a few hours of sleep the last few days) but it wasn't clicking for me at first.  By the end of the video I was understanding what the code was doing for it to work, but I was having trouble grasping it at first.  Once I manage to get in some rest I will come back to this one and try to code it myself a few times to get a better understanding of it.  It is definitely something commonly used so it'd be very useful to know how the code process works to make something like this.

<hr>

Day 11: CUSTOM VIDEO PLAYER (completed: 8/28/2022)

This tutorial will definitely be something that will come in handy for me soon.  I run a YouTube channel and currently will be expanding a 2nd channel.  I have a website up for one them already (www.drummondreacts.com) and I will make another one for the new channel once I get a better branding idea for it (it's going to be coding based for anyone interested in checking it out here: https://www.youtube.com/channel/UC7A9BktiAOLx4sfosj8zJfQ). I ran into some issues while trying to code this. The big one for me was the scrub.  The progress bar wouldn't release whenever I was clicking my mouse, even after applying the code to prevent that from happening. I've had several issues like that on other videos in this course, but I usually I will check the finished code to make sure that it's running properly, copy the code into the file I'm working on, and then line the codes up to see where the mistake is. Usually it's a syntax error on my part that I don't notice. Sometimes it's a piece of code that I skipped over accidentally. But I did want to take up the challenge at the end of the video to make it full screen.  I got part of the way on my own but was having trouble making it work.  I looked online to get some ideas on how to do it and eventually managed to get it to work.  However I am unable to show it here because Github will not allow me to upload the video file from this project as it's rather large.  I'll probably upload it someplace else and link it here.  And on that note I am going to take a break for a little bit, let my brain refresh while I go and watch Big Buck Bunny (the video from this project).

<hr>

Day 12: KEY SEQUENCE DETECTION (completed: 08/30/2022)

UUDDLRLRAB SELECT START!  This one was awesome to learn.  I always used to love getting a new cd from a band and going to the last track of the album and trying to find that secret song.  It made owning cds pretty awesome.  The scratches and ruining the entire disc was a whole other issue.  Anyway, I really got a kick out of this lesson.  I was unaware that websites had cool hidden gems like this.  The cornify thing was cool too. I gotta look them up and see what others are out there and try them out. I was a bit confused by the math to get the correct number of arrays though.  The -secretCode.length - 1 part threw me off a bit.  I'm still having some trouble dealing with the math aspect of JavaScript when it comes to arrays and .lengths and things like that.  Usually once I understand it it tends to make more sense, but when first shown in some sort of instructional way or just listed in code without really diving into it, it does come across as very confusing.  And I had a syntax error too which did not help.  I was only getting 5 arrays, not 6. I checked the code and it was typed correctly as shown.  However I had listed my secretCode as "wesbo", forgot to add the second "s".  I also added in a code to change the background color when the secret code is typed in to see if I could change that as well.  It worked! :)  

<hr>

Day 13: SLIDE IN ON SCROLL (completed: N/A)

<hr>

Day 14: JAVASCRIPT REFERENCES VS COPYING (completed: N/A)

<hr>

Day 15: LOCALSTROAGE (completed: N/A)

<hr>

Day 16: MOUSE MOVE SHADOW (completed: N/A)

<hr>

Day 17: SORT WITHOUT ARTICLES (completed: N/A)

<hr>

Day 18: ADDING UP TIMES WITH REDUCE (completed: N/A)

<hr>

Day 19: WEBCAM FUN (completed: N/A)

<hr>

Day 20: SPEECH DETECTION (completed: N/A)

<hr>

Day 21: GEOLOCATION (completed: N/A)

<hr>

Day 22: FOLLOW ALONG LINK HIGHLIGHTER (completed: N/A)

<hr>

Day 23: SPEECH SYNTHESIS (completed: N/A)

<hr>

Day 24: STICKY NAV (completed: N/A)

<hr>

Day 25: EVENT CAPTURE, PROPOGATION, BUBBLING AND ONCES (completed: N/A)

<hr>

Day 26: STRIPE FOLLOW ALONG NAV (completed: N/A)

<hr>

Day 27: CLICK AND DRAG (completed: N/A)

<hr>

Day 28: VIDEO SPEED CONTROLLER (completed: N/A)

<hr>

Day 29: COUNTDOWN TIMER (completed: N/A)

<hr>

Day 30: WHACK A MOLE (completed: N/A)

