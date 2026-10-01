1. What did `pwd` print?
Ans- /Users/Pankaj

2. What did `ls -a` show that plain `ls` did not?
Ans- 'ls -a' showed all the hidden files too (ex- zsh files) whereas 'ls' only showed the normal files.
 
3. Pick one line from `ls -l`. What do you think the first column means?
ans-class
class.py
Desktop
Documents
Downloads
first coloumn represents the file type and submission.

4. Why does that work from where you are standing? Which kind of path is `coding-cafe/week02`? Absolute or Relative?
Ans-first coloumn represents the file type and access permissions. it is relative path.

5. `mv` did two different jobs above. What were they?
Ans- job1-  old file -> new name
job2-> move a file to a new folder

6. How many folders are on your `PATH`? (They are separated by `:`)
ans- there are 11 folders on my path.
7. **Write down exactly where your `python3' lives?
ans-/Library/Frameworks/Python.framework/Versions/3.14/bin/python3
8.Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
ans- no,because they have installed different version of python than me.
9. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
ans- it said zsh: no matches found: same?
zsh: command not found: 9
because when you type pyton3, the shell searches every folder in your path for that program. since pyton3 doesn't exist in ant PATH directory, the shell reports that the command was not found.

10. `.venv` did not appear with plain `ls`. Why not? (Refer back to section 1.)
ans- .venv is a hidden file (or directory) because its name starts with a dot (.). Plain ls hides dotfiles by default, whereas ls -a is required to show them

11. What changed about your prompt?
ans- (.venv) was added to the beginning of the prompt.
12. compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell
    you about what `activate` actually did to your `PATH`?
    ans- no the path is different , it puts your virtual environment's folder at the front of your path.

    13. What is in the second list that was not in the first?
    ans- certifi, charset-normalizer,idna,and requests

    14. Where does `python3` point now?
   ans- /Library/Frameworks/Python.framework/Versions/3.14/bin/python3

     15. Find what `ls -h` does. Write it in your own words.
     ans- it displays file sizes in a format of human readable(like KB,MB,Or GB) instead of showing plain bytes,making it much easier to understand

     
16. What is the difference between what Ctrl + C and Ctrl + D did?
ans- ctrl+c sends an interrupt signal whereas ctrl+d sends an end of file (EOF) signal gracefully exit the shell session.

