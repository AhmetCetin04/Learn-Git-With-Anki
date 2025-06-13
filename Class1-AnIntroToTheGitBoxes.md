To best understand Git, we must understand why it exists. 

To put it simply, manual version control is both hard and tedious, and doing it in a team is practically impossible. Hence we have git.

Back when I was a wee little lad, I had the misfortune of working on a group project for my intro to C class where no one in my group really knew what git was, or how it was used.

Even today I believe keelhauling would've been preferable to that experience.

Sharing a handful of csv files, testing folders full of constantly changing input and output files, header files, and C programs through Discord is similar to playing a game of telephone with a codebase. This torment is difficult to articulate, but please be certain Dante was mistaken when he wrote that the lowest level of hell was a frozen ice lake.

Those who may disagree have never spent 2 hours debating why test case 10 keeps failing, only to realize that your test10.txt file is different from the other lads test10.txt file. 

Git exists to solve this problem. It allows multiple people to work on a project with multiple versions at the same time, and it forces them to maintain a certain level of documentation and organization while doing so, while simulatenously storing all the previous versions of the project. This last part ensures that when shit hits the fan we can easily revert back to before shit hit the fan, we can compare to past versions and quickly figure out a). What code was changed before shit hit the fan, and b). Who to blame for shit hitting the fan.

So with this out of the way, lets start talking about git. 

I want to start off with the workspace
