LAB REPORT 1

QUESTION 1:

I decided to test `cd` first without arguments and the absolute path before the command was run was `/Users/diegoortega`. The output I got was nothing since I didnt include any arguments after `cd`. The output isn't an error since the terminal doesn't explicitly indicate an error.


<img width="271" alt="Screenshot 2024-04-09 at 5 52 51 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/9605d27b-bcd5-4185-938a-ce963c2303e0">


I tested `ls` after this without any arguments and the absolute path before the command was ran was `/User/diegoortega`. The output I got was all the files contained in the `current working directory`. The output wasn't an error since there were no explicit errors pointed out in the terminal


<img width="1321" alt="Screenshot 2024-04-09 at 5 58 13 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/cc3f46d3-b455-4729-b69b-aaccc85cb864">

I tested `cat` without any arguments and the absolute path before the command was still the same `/User/diegoortega`. The output I got when using this command was the terminal waiting for me to type something into the terminal. This output wasn't an error as well since the terminal didn't indicate a specific error


<img width="281" alt="Screenshot 2024-04-09 at 6 09 21 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/f4f1774e-1e7d-4c45-b280-63c30728b8d4">


QUESTION 2:

Next I tested `cd` but this time with an argument, "Documents" as my directory. The absolute path previous to this was `/User/diegoortega`. The output when the command was executed was nothing yet when we put the `pwd` command we see the change made since the absolute path went from `/User/diegoortega` to `/Users/diegoortega/Documents`. There were also no errors when this command was executed


<img width="362" alt="Screenshot 2024-04-09 at 6 40 34 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/a5f5c841-0248-4084-a902-37e063b0a89f">

I then test `ls` with the argument "Applications" directory as my argument. The absolute path before this command was run was `/User/diegoortega/Documents`. The output whe the command was executed were the contents that were store in Applications which was Chrome Apps.localized. There were no errors when this command was executed.


<img width="573" alt="Screenshot 2024-04-09 at 6 47 26 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/2c227e9b-46e9-4ca4-816b-ce83e5ebba5f">

Lastly I test the `cat` command with the directories "Downloads" and "Desktop". The absolute path previous to this was `/Users/diegoortega`. The output of this was an error saying that the operation wasn't permitted. I think this is because the `cat` command only concatenates files and not directories.


<img width="429" alt="Screenshot 2024-04-09 at 10 10 30 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/c09674fb-066c-4518-831e-b9c4b80b038b">

QUESTION 3


Now for the files as paths I first started with the `cd` command and I used "newfile.txt" as my argument. The previous absolute path was `/Users/diegoortega`. The output after the command was executed was an error because the command `cd` stands for "change directory" and "newfile.txt" isn't a directory.


<img width="365" alt="Screenshot 2024-04-09 at 10 20 25 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/6bf2d07e-631a-4594-b5dd-3b786da1b106">

The next command I used was  `ls` and I used the the file "newfile.txt" as my argument. The previous absolute path was `/Users/diegoortega`. The output after the command was executed were the contents of "newfile.txt" which looks like this:


<img width="377" alt="Screenshot 2024-04-09 at 10 30 21 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/d4b61c1a-5caa-4279-bade-31971088a185">


Finally I test cat with a path to the files, "newfile.txt" and "newfile2.txt". The previous absolute path was `/Users/diegoortega`. The output after the command was executed was a sentence consisting of what the files "newfile.txt" and "newfile2.txt" contained.


<img width="481" alt="Screenshot 2024-04-09 at 7 08 43 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/b78b9e36-ae25-41ce-a0e7-b27f09285dbb">

