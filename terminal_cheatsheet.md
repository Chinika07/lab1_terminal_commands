# Terminal Cheatsheet

1. **ls:**
    Lists what is in the current directory (files and folders)

2. **ls -l:**
    Shows extra information about what is in the diretory, e.g. when the file was last modified, file size etc.

3. **ls -a:**
    Lists ALL files and folders, including the hidden files

4. **pwd (print working directory):**
    Displays which directory we are currently in

5. **cd [folder]:**
    'Change directory' - moves us into another directory, just need to add the name of the one we want at the end. E.g. cd c8_coursework

6. **cd ~ or cd:**
    Navigates us back to the home directory

7. **cd -:**
    Will take us back to the previous directory if we move to a different directory by accident

8. **tab key:**
    Auto-completes the command, e.g. the directory name

9. **mkdir (make directory):**
    Makes a new directory

10. **touch:**
    Creates a new file in the directory 
    
    **- NOTE:** Need to add the **file extension, e.g. .txt or .pdf**

11. **open:**
    Opens directories, e.g. 'open my_file.txt'

12. **code .:**
    Opens the folder in VS Code - can create a file in VS Code which will now be in the folder

13. **mv:**
    Moves a file    
    **- NOTE:** Need to state the one we're moving and where we are moving it to, e.g. 'mv my_file.txt ..' 
    
14. **.. :**
     Means the 'directory **above**' , e.g. will move the file up a level (into the folder before)

15. **. :**
    Means this '**current** directory'

16. **cp:**
    Copies a file
        
    **- NOTE:** First need to provide the name of what we want to copy and then the location we want to copy it to, e.g. cp profile_picture my_directory 

17. **cp -r:**
    Copies the entire directory

18. **rm:**
    Deletes files

19. **rm -r:**
    Deletes a directory (sometimes asks confirmation if you want to do so)

20. **rm -f:**
    Forces removal - does not ask confirmation if you want to delete something

21. **clear:**
    Clears the terminal file (but if we scroll up, will see the previous work)

22. **cat:**
    Outputs the content of the file, e.g. cat cohortnumber.txt

23. **echo:**
    Places text into the file, e.g. echo "I'm in Cohort 8" >> cohortnumber.txt

24. **'>>' :**
    Adds new text to the file - adds a new line

25. **'>' :**
    Overrides the current text in the file with this text

26. **control + C:**
    Press this to get out of a command we are stuck in, e.g. 'dquote' 

27. **dquote:**
    Means there is a quotation mark missing somewhere

28. **pbcopy:**
    Copies text to the clipboard, e.g. pbcopy < * *TEXT* *

29. **git init:**
    Creates a new git repository in the directory

30. **git:(main):**
    'Git' shows the directory is part of a Git repository and 'main' is the active branch in the repository

31. **git status:**
    Displays the state of the current directory, shows us the changes that have been made and which haven't

32. **git commit:**
    Creates a record of the files that have been staged (step 1) and details of what has changed 

33. **git commit -m " ":**
    '-m' stands for 'message'. Should give a description of what has changed and what has changed in them (needs to give anyone who reads it an idea of what is happening)

34. **git add .:**
    Tells Git to stage all changes in the current directory (current directory = .)

35. **git log:**
    Displays what has happened in the repository so far

36. **git branch -M main:**
    Copied from GitHub after creating new repository (first line that is copied)

37. **git remote:**
    Links the local repository to GitHub, i.e. git remote add origin * *LINK FROM GITHUB* * (second line copied from GitHub after creating new repository)

38. **git push:**
    Uploads one repository to the other, needs the place we are sending code to and the branch we are sending it from, i.e. git push -u origin main (third line copied from GitHub after creating new repository)

39. **git clone:**
    Copying a repository from Github, i.e. git clone * *SSH URL FROM GITHUB GOES HERE* * 
    
    **- NOTE:** Do not clone a repository inside another one

40. **q:**
    Exit - returns us back to the command line
