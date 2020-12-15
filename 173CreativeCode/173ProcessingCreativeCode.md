# Quotes Collection (173)


# Processing (P5JS and more) Creative Code 



## Sources:

### Online Sources
	Wikipedia (the free encyclopedia that anyone can edit)
	
	Khan Academy (A Free World-Class Education for Anyone, Anywhere.) https://www.khanacademy.org/computing/computer-programming
	
	Daniel Shiffman (Learn Creative Code) https://shiffman.net/
	
### Book Sources 
	Make: Getting Started with P5.js https://www.oreilly.com/library/view/make-getting-started/9781457186769/
	https://www.timeanddate.com/ 


## Quotes

## Make: Getting Started with P5.js Quotes and Code

Chapter 1. Hello



P5.js is for writing software to make images, animations, and interactions. The idea is to write a a single line of code, and have
a circle show up on the screeen. Add a few more  lines of code, and the circle follows the mouse. Another line of code, and the
circle changes color when the mouse is pressed. We call this sketching with code. You write one line, then add another, then
another, and so on. The result is a program created one piece at a time.

Programming courses typically focus on structure and theory first. Anything visual--an interface, an animation--is considered
a dessert to be enjoyed only after finishing your vegetables, usually several weeks of studying algorithms and methods. Over
the years, we've watched many friends try to take such courses only to drop out after the first lecture or after a long, frustrating
night before the first assignment deadline. What initial curiosity they had about making the computer work for them was lost
because they couldn't see a path from what they had to learn first to what they wanted to create.

p5.js offers a way to learn programming through creating interactive graphics. There are many possible ways to teach coding,
but students often find encouragement and motivation in immediate visual feedback. p5.js provides this feedback, and its
emphasis on images, sketching, and community is discussed in the next few pages.



Sketching and Prototyping

Sketching is a way of thinking, it's playful and quick. The basic goal is to explore many ideas in a short amount of time. In our
own work, we usually start by sketching on paper and then moving the results into code. Ideas for animation and interactions
are usually sketched as storyboards with notations. After making some software sketches, the best ideas are selected and
combined into prototypes. It's a cyclical process of making, testing, and improving that moves back and forth
between paper and screen.



Flexibility

Like a software utility belt, p5.js consists of many tools that work together in different combinations. As a result it can be used
for quick hacks or for in-depth research. Because a p5.js program can be as short as a few lines or as long as thousands,
there's room for growth and variation. Libraries extend p5.js even further into domains including playing with sound and
adding buttons, sliders, input boxes, and webcam capture with HTML.



Giants

People have been making pictures with computers since the 1960s, and there's much to be learned from this history. For
example, before computers could display to CRT or LCD screens, huge plotter machines were used to draw
images. In life, we all stand on the shoulders of giants, and the titans for p5.js include thinkers from design, computer graphics,
art, architecture, statistics, and the spaces between. Have a look at Ivan Sutherland's Sketchpad (1963), Alan Kay's Dynabook
(1968), and the many artist featured in Ruth Leavitt's Artist and Computer (Harmony Books, 1976). The ACM SIGGRAPH 
and Ars Electronica archives provide fascinating glimpses into the history of graphics and software.

## KhanAcademy: Computer programming Quotes and Code


Learning programing on Khan Academy


In this course, we'll be teaching the concepts of the JavaScript programming
language and the cool functions you can use with it in the ProcessingJS
library. Before you dig in, here's a brief tour of how we teach programming
here on Khan Academy, and how we think you can learn the most.

Normally, we teach on Khan Academy using videos, but here in programming
land, we teach with something we call "talk-throughs". A talk-through is like a
video, but it's actually interactive- you can pause at any time if you want to
play with code yourself, and you can spin-off if you want to make your 
own version of what we made. Here's an animated GIF of a talk-through
(there will be sound in the actual talk-throughs!):

After a talk-through, we'll give you a step-by-step coding challenge and guide
you through them with messages and hints. If you feel like you're spending too
much time on a challenge and getting frustrated, try re-watching the talk-
through or just keep going and re-visit the challenge later. Here's an animated
GIF of the Bucktooth Bunny challenge:

When you're learning to program, you've got to practice-practice-practice. The
challenges are a good way to try out what you've learned, but we want you to
go deeper. That's why we now have projects in the course, opportunities to
spend a lot more time and be more creative than you can be in the challenges.
Some of the projects will be evaluated by your peers, and some just by 
yourself. You'll also evaluate some of your peer's projects, so you can learn
from them. In programming land, we're constantly learning from our peers,
there's always something new to learn!

Besides the projects, you should also make up completely new programs,
whatever's in your head. Just click "New program" on the programming
homepage, and look at the documentation to remember how to do things.

And hey, it's totally okay to make mistakes. That's what programmers do all
the time - we break things, we make mistakes, we learn from them.

Once you've made a program, you can save it and share it with your friends
and family. It'll also show up in our community programs area, and other
programmers can comment on it or ask you questions about how you did 
something. You can do the same for any interesting programs you find, too,
and if you have an idea for customizing a program you see, just click "Save as
spin-off" and you'll have your own copy of it.

All in all, there are 40 talk-throughs, 35 challenges, and 9 projects in this
course, and it takes about 15-40 hours to complete, depending how wild you
go with your projects. That might seem like a lot of time, but it's worth it,
because at the end, you'll know the fundamentals of programming that are
common across all programming languages.

Welcome to programming land: we're a community learning together and
inspiring each other to turn the visions in our head into reality. Onward!



Spin-off of "Making drawings with code"
Khan Academy Code:
https://www.khanacademy.org/computer-programming/spin-off-of-making-drawings-with-code/5574775330521088

	ellipse(200, 200, 360, 360); // Head

	ellipse(200, 300, 180, 50); // Mouth

	ellipse(150, 150, 33, 33); // left Eye

	ellipse(250, 150, 33, 33); // right Eye

OpenProcessing Code:
https://www.openprocessing.org/sketch/1036211

	// Khan Academy Spin-off of "Making drawings with code"

	function setup() {
		createCanvas(windowWidth, windowHeight);
		background(100);
	}

	function draw() {
		ellipse(windowWidth*0.50, windowHeight*0.50, windowWidth*0.825, windowHeight*0.825); // Head

		ellipse(windowWidth*0.50, windowHeight*0.75, windowWidth*0.45, windowHeight*0.125); // Mouth

		ellipse(windowWidth*0.375, windowHeight*0.375, windowWidth*0.08, windowHeight*0.08); // left Eye

		ellipse(windowWidth*0.625, windowHeight*0.375, windowWidth*0.08, windowHeight*0.08); // right Eye
}
