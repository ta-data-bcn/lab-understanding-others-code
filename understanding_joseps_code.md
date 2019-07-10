### Understanding Josep's Code (Project 1: Encryption and Decryption) 

### Understanding the Workflow 

I understand that the game follows this structure: 

1. Ask user choice (Encryption and Decryption)
2. Input validation 
IF ENCRYPT: 
3. Message to encrypt 
4. Image choice to be used for encrypt or decrypt. 
5. Create a string with the encrypted message based on the image 
IF DECRYPT: 
3. message to decrypt 
4. image choice to be used for decrypt


#### Questions 
1. why are you creating a class for the functions? 
    Josep's answer: Because I wasn't aware of how to import scripts and functions from a separated file. He has worked so much with PHP and this is how it is done there. 
2. If we want to decrypt a message, the code isn't finished, and so this feature is not implemented. 
    Josep's answer: This is a further step. Right now, the game can encrypt but not decrypt.  
3. There is a variable called no_quit, but it's not changed alongside the code. How can it be changed? 
    Josep's answer: this is a feature to be done in a further step. However, he structured the code to implement this feature, but he hasn't had time to do this. 

### Useful things Josep has done 
- Writing a description of the code at the very beginning can help us to understand the purpose of the code. 
- Creating a separated script for all the functions. 
- Each function has a description that is used as a documentation and that can be accessed on Pycharm by shift+tab.
- good naming of variables (WhatToDo). It makes easier for us to understand the code. 

### Comparison with the first version of the code. Do you think the improvement is significant?
- Josep has added more descriptions of what each function does, and it can be accessed as a documention. 
- He has changed the name of the script with all the functions to a shorter and understandable name. 

However, the improvement is not super significant since he has structured the code all in functions and with good variable naming. 
 

### Is the gitflow useful? Does it clarify some doubts you had? 

He hasn't done so many commits. Also, the commits don't provide useful information on the features/changes that have been done. 

### Try the game. Do you find something that could be improved? Does something surprises you? Set some glows and grows for your partner. 

GLOWS: 
- There is a good documentation on the functions and also on the game. 
- Two scripts, one for functions and the other one for the game. 
- Good comments to understand what each function does, and also the libraries.  


GROWS: 
- I'm not quite sure, but maybe instead of entering all the ASCII_UNICODE characters you could use a library called "string".
- Add more information on the commits. 
- Finish the game to be able to decrypt the image. 
- He wanted to be able to exit the code at any time, but he didn't implement this feature. However, since this is something that he wanted to implemented, it should be provided as an instruction to the game when choosing Encryption 


