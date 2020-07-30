LAB: Creating Mario
Lesson Time: 45 Minutes

In this lab, we will represent the video game character Mario as a struct as a way to start thinking about how 
complex data is created.
Scenario:
You work for a company that allows users to play classic video games on their web site. 
You’ve been asked to re-create the classic character Mario for use on the website. 
Using a struct, create various data points that makeup Mario.

1. We need to begin by thinking of all of things that Mario might need. Let’s start making a list.
Here’s the list we came up with.
Number of lives
Number of gold coins
Current Stage
Size (small or large)
Can Shoot a fireball? (yes or no)
Is jumping right now ( yes or no)

2. Now, let’s turn this into a struct. This code is written ABOVE the Main() Code Block. Do not place it inside of it.
Don’t worry just yet about the “public” keyword. We’ll discuss that in detail in a future lesson on OOP. 
We’ve created an enum called Size, integers for lives, a string for the current level, and we are tracking if 
Mario is jumping and can shoot his fireballs.


3. Now in the Main() code block, let’s create Mario and give him some default values.
Let’s play some Super Mario in C#

Open the 5_4 LabStarter, read through the code. Change the values of Mario as directed as he moves through “the level.”

Starting Code:   https://github.com/ACTWebDev/SD104/blob/master/5_4LabStarter/5_4LabStarter/Program.cs 
