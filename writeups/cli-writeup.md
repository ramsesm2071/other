# Process Writeup

## Name: Ramses Martinez
## Course: SEP 10
## Period: 8
## Concept: Command Line

## Context

CLI or Command Line Interface is a program that allows for you to make directories, files, etc using the command line. Which uses different commands such as mkdir to make those directories, some examples of different commands are:

## Commands

* To print working directory `pwd` 
* used to list `ls` 
* Changes your directory `cd` 
* Makes a directory `mkdir` 
* Removes a directory `rmdir` 
* Touch is used to create files `touch` 
* Used when removing everything in a file `rm -rf` 
* Used to rename a file `mv (to rename)`
* Used to move a file `mv (to move a file)`

## Pros of CLI
* Fast to use/Efficient
* Good for complex tasks

## Cons of CLI
* Easy to lose your work
* Need to know what your doing, need to know commands
* Hard to learn when starting

## Challenges 

One challenge I had was learning to use touch correctly as I never had any experience using it and I didn't take any notes when being taught touch, so when doing the practice work I was stuck using this code:

```language
mkdir cucumber 
mkdir mushroom 
mkdir tomato
Cd cucumber
Mkdir pepper 
mkdir zucchini
Cd pepper 
Touch lettuce
Touch spinach
Cd ..
Cd tomato
Mkdir onion
Touch celery
```

After finished my work up I had asked my partner to skim over it and point out any mistakes I may have made and after looking through my work he told me multiple things were wrong but most importantly that I wasn't adding something when using touch so I had him help me learn to use touch. After he explained it to me and helped me the new code looked like this:

```
mkdir cucumber 
mkdir mushroom
mkdir tomato
Cd cucumber
Mkdir pepper 
mkdir zucchini
Cd pepper 
Touch lettuce.txt 
Touch spinach.txt
Cd ..
Cd ~/tomato
Mkdir onion
Touch celery.txt
```

Another challenge I had when learning command was that I was still figuring out how to make multiple directorys at one or cd back out of multiple without typing something incorrectly so when doing the practice work I was stuck using this code:

```
mkdir orange, banana
cd orange
mkdir pineapple
cd ..
mkdir peach
cd banana
touch grape.txt
pwd
cd orange, pineapple
touch strawberry.txt
cd ..
mv peach, mango
touch mango, watermelon.txt
rm mango
```

The mistake I was doing in this code was adding an apostrophe when I would add another thing to mkdir or cd. I only figured this out when someone went up to the board and did an example for everyone to see, and after the example I quickly changed it and added into my notes, so the code would look like this when correct.

```
mkdir cucumber mushroom tomato
Cd cucumber
Mkdir pepper zucchini
Cd pepper 
Touch lettuce.txt spinach.txt
Cd ..
Cd ~/tomato
Mkdir onion
Touch celery.txt
```

---
## Takeaways

* Pay Attention to my work, I mean this as I need to look over my code when I finish to make sure that I don't miss out on integral parts of my code such as the touch command when not adding .txt to the end.
* Practice at home, I need to practice during free time in order to fully grasp some of the commands such as touch.txt or mv. (rename or move)
* Another takeaway is to update notes whenever possible with what i've learned recently so I can go back to check on what each command does or anything I may be stuck on in the future.
