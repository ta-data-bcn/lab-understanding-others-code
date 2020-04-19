![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Understanding others code

* *Beto Sibileau*. Data Barcelona (FT), April 2020.

## Description
I take *Aitor Quinza's* code from Project 1 to analyze and report the present feedback. His project is about the game **Guess the number** to be played against the computer in three different levels available.

## Feedback Report
* After having a look at the slides I jumped directly into Aitor's GitHub repo and followed his Jupyter Notebook.
* Being both the slides and the code very well structured, I got into the workflow without any struggle.
* The error handling is done in a very good manner such that the code does not crash.
* Some minor comments on error handling:
    * When doing the level input (`which_level`), the string check could have been made case insensitive.
    * Also in `which_level`, take into account that once the level input has been inserted incorrectly, the `finally:` statement is executed again even if the input is retyped correctly.
* Finally, it could be considered to have a historic variable that stores the user choices. This could be useful to remind the user that a choice has been repeated while re-executing the user input function accordingly.
