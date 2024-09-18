2. Recall from our lectures that we typically name our read-me files README.md on GitHub.
What does .md stand for? Why we do prefer to use .md extension for README files on GitHub?  
.md stands for for mark down and we prefer to use it because it is an easier form of coding. 

4. Does the git software index and track empty folders in your project?  

No it only tracks folders with files

4. Does every Git project have a .git folder?  

Every git project should have a .git folder or it is not a git project.

5. What is the purpose of the .git folder in Git projects?  
.git folder stores the metadata  

6. What does the Linux Bash command cd do? (Hint: See the Linux cheatsheet in the lecture notes)  

cd takes you to home   
   
7. What does the Linux Bash command ls -a do? (Hint: See the Linux cheatsheet in the lecture notes)  

ls shows the directory listing   

8. What does the Linux Bash command pwd do?

pwd shows your location in the directory       

9. Name and briefly describe the three different areas in a Git project.  

The three different areas are the working area where work is modified but not staged, the staging area where work is staged to be committed, and the repository where work has been committed.  

10. What is a Version Control System (VCS)? A brief explanation is enough.  
VCS records changes to a file.

11. Name 6 major benefits of using distributed VCS as opposed to not using any VCS at all for project indexing and maintenance.  
Offline work, backups, private work, faster, flexibility, collaborations.

12. Name the three major historical classes of VCS.
Local, centeralized, and distributed VCS. 

13. What is Git and how is it different from GitHub?
Git is a VCS and GitHub is a website that uses git.

14. What does git status command do?  
git status shows the current status of the wotk in the directory.

15. What does git push --all command do?  
uploads all local repository content to a remote repository.

16. What does git pull command do?  
pulls content from the remote repository and updates the local repository.

17. What is Markdown? (A brief answer is sufficient)  
markdown is a way to style text 

18. How do you make a text boldface in Markdown? (Hint: Read the Markdown cheatsheet in the lecture notes)  
By adding two astericks or underscores before and after the words you want to bold. 

19. How do you make a text italic in Markdown? (Hint: Read the Markdown cheatsheet in the lecture notes)
By adding one asterick or underscore before and after the text you want to italicize.

20. What is the Git command to initialize an empty git project on your local system?  
git init

21. What do . and .. mean in directory path names (For example, in ./README.md and ../README.md?
. takes you to your current location, .. takes you to the previous folder.

22. The following steps will guide you to create an empty Git project using the terminal (on macOS / Linux) or Git Bash environment (on Windows).
If you have not set up Git on your system in class before, here is your last chance to do so.
1. Open your terminal (on Linux or macOS) or Git Bash (NOT Windows CMD or PowerShell) on Windows.  
2. Navigate to your hocdme directory and type the command that shows the path to the current directory on the command line (Hint: Recall the Linux commands to achieve this from our classes or the lecture cheatsheets.)
3. Select the commands that you have typed and their output from the command line and paste it into your README.md file for this quiz in the section for this question.
   summe@Oracle MINGW64 ~/downloads/IDS2024F (main)
$ cd

summe@Oracle MINGW64 ~  

4. Create a new folder named testdir in your home directory (where you are).
(Hint: Recall the Linux command for making directories.)

Copy the command and its output again to the README.md file you have created for the quiz.
summe@Oracle MINGW64 ~
$ mkdir testdir

summe@Oracle MINGW64 ~
$

6. Change directory to testdir. (Hint: Recall the command to change directory from the Linux cheatsheet and our class)
summe@Oracle MINGW64 ~
$ cd testdir

summe@Oracle MINGW64 ~/testdir
$

8. Is this folder testdir already a git repository? Why? Can you prove your answer with the command ls -a (What does this command do? Hint: -a stands for all.)
   yes
10. If your answer to the above is YES, then you can safely skip this part.
If your answer is NO, then how would you make this folder a Git project? (Hint: What is the right git command to achieve this? Hint: Consult our lecture notes on git project initialization.)
11. Recall the vim software from our lectures and classes. What does it do?
Use vim to create a README.md file and type This is a README.md file for the test git project of quiz1.
How do you save the contents of this file using vim and quit the vim environment? (Hint: Again remember our class discussion and lectures.)
12. Once you are out of the vim environment, type cat README.md on the command line and press Enter key.
What do you see? Copy and paste this command and its output to as answer to this section of your quiz1 README.md file.
13. How would you check the status of your test Git project that you have created in this folder? (Hint: Again, consult the lecture notes.)
Paste the git command and its output as your answer to this question in your quiz README.md file.
14. If you see no changes, you can skip this question.
If you see changes in your git project from the step above, how would you stage and commit those changes to your test project on the command line?
Type those two (or both in one) commands in the terminal and copy/paste the output to your quiz1 README file.
15. Check the status of your test project one more time on the command line.
Copy/paste the command and its output to your quiz1 README file.
16. Now type the following command exactly as is in your terminal and press Enter.
cd .. && rm -rf ./testdir
Explain what you just accomplished with the above command? What does -rf do in the above command?
(Hint: && means perform the first command and if successful, perform the command that follows &&.)

23. Name four newly emerging branches of science that are growing exponentially fast with respect to the traditional fields of science. (Hint: Consult our lecture notes)  
Biomedical
Neuroscience
Cognitive Science
Neurobiology

25. Name four modern scientific tools or algorithms that have been growing exponentially fast in popularity over the past decades. (Hint: Consult our lecture notes)  
Computer
Optimization
Simulations
Bayesian  
26. Name three major modern pillars of science. (Hint: Consult our lecture notes)  
Experiment, theory, and computation+data  
27. Name three major modern applications of computational and data sciences. (Hint: Consult our lecture notes)  
Data scientist, data analyst, and data engineer.   
28. Name the three major components of the field of Data Science? (Hint: Consult our lecture notes)  
coding, stats, and domain  
29. You are hopefully on track to become a Data Scientist. Recalling our discussion in class, how would you best define a Data Scientist? (Hint: Check, your answer to the previous question, consult our lecture notes and recall our detailed class discussion on data scientist as someone who knows more or less of certain topics compared to other scientists.)  
   a data scientist is someone who can use data to create something in any way. 
30. Extra Credit. What is the difference between a relative and an absolute file path?
    An absolute path has a direct path from the original file whereas a relative path is a path from any other file. 
Which one is more appropriate to use in your GitHub projects? Why?
Relative paths are more approporate since they are easier to track.
32. Extra Credit. Write down the Git command that lists all Git commands for you (Hint: See the lecture notes)

33. Extra Credit. What does the Linux Bash terminal command cd ~ do? (Hint: Recall our class discussions on what ~ means.)
