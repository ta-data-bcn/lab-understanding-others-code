![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Understanding others code
## Filled in 

## Description
Yesterday you spent some time improving your first week's code. Today we ask you to take someone else's code and understand it. 

## Goals
This is important because you:
* Learn from others by reading their projects.
  * New methods.
  * New ways of thinking.
  * Best practices.
* Your partner learns from you thanks to your feedback.
  * He/she knows his/her strenghts.
  * He/she learns some ways to improve.

## Code Analysis [Hangman by Kerim]

#### 1. Look for the repository of the partner you have been assigned to.
#### 2. First, understand the workflow he/she built in their improved version of their code.
- naming of steps
- renaming some variables

#### 3. Draw / write the workflow for yourself and note your doubts about it.
Workflow of refractoring:

- step1 : copy code into new file
- step2 : check for correct spacing in code and between functions
- step3 : change names of variables

Clear - no doubts


Workflow of game:
- step1: import libraries needed
- step2: welcome message and defining variables
- step3: defining functions
        * print string
        * print hangman
        * play funciton
- step 4: run play 

#### 4. Look for things he/she made that you think could be useful for you.
- descriptions added in line in the code to clarify variables
- colouring you results thorught use of pyfiglet library 


#### 5. Now go to the first version of the code and compare it with the new version. Do you think the improvement is significant?
- Not many changes. 
- Original version was allready very clear - missing description of functions
- Change of variable names and addition to some description of code are helpful.


#### 6. Is the git flow useful? Does it clarify some doubts you had?
- Yes, not many commits, but also not many changes done.
- Changes done are clearly described


#### 7. Try the game. Do you find something that could be improved? Does something surpises you? Set some glows and grows for your partner!
###### Glows:
- graphic additions to the game is very well done - I like the colours :)
- clear workflow throught file
- well described through # notation
- consistant and good variable naming

###### Grows
- put your funcitons into separate files and import them to the a main function where you define variables and call on the play() function
- describe in detail you functions (use """ """)
-  for the alphabet list could have used: 
        >>> import string
        >>> list(string.ascii_uppercase)
- for input error handeling, try not to use a while loop (to avoid infinite while loops). Rather add a if funciton and a sys.exit("Wrong input") or similar. 




### Let's give some feedback!
* Order the things you want to say.
* Look for your partner and schedule some time with him/her.
* Have a nice time!
