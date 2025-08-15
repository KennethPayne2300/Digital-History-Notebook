# Digital-History-Notebook.
### Digital History Notebook: Computer Science Pioneers
Welcome to your first project for the "History of Technology" class. Your assignment is to create a digital notebook to document key figures and events in the history of computer science. This notebook will be version-controlled, allowing you to track your work and manage your revisions. 
<br><br>
Your final submission will be a public GitHub repository with a complete digital notebook that follows all of the steps below.<br><br>
#### Assignment 1: Setting Up Your Notebook
Your first task is to set up your digital notebook's central repository
#### Instructions:
1. Create a **new public repository** on GitHub. Name it exactly:<br>
Digital-History-Notebook.
2. Add a **README.md** file when you create the repository.
3. After creating the repository, clone it to your local computer. Open the README.md file in a text editor and copy and paste this entire assignment briefing into it.
4. Once the content is in the file, you will need to push it back to GitHub.
#### Report Status (These questions need to be answered for part of your grade):
- **1.1:** What command did you use to bring the repository to your local machine?
  - Answer: **git clone https://github.com/KennethPayne2300/2526PMNotes.git**
- **1.2:** What was your first commit message to push this file to GitHub?
  - Answer: "update README.md"
#### Assignment 2: The Founding Visionaries
Now, let's begin documenting the pioneers of our field. You will create files for two key figures.<br><br>
##### Instructions:
1. On your local machine, create a new file named **ada-lovelace.md**.
2. In this file, research and write a short paragraph about her contributions to early computing. (Cite those sources!)
3. Create a second new file named **alan-turing.md**.
4. In this file, research and write a short paragraph about his contributions to modern computer science. (Cite those sources!)
5. In this README.md file, add two hyperlinks below to your new files. The links must be named "Ada Lovelace" and "Alan Turing" and must lead to the corresponding files you just created. (Hint you will need to research how to put in a link in markdown)
6. Use **git add .** to stage both new files.
7. Use **git commit -m "Added pioneers Ada and Alan"** to save these changes to your local notebook.
8. Finally, use **git push** to publish your work to GitHub.
#### Report Status:
- **2.1**: What two file names did you create?
  - Answer: 
- **2.2**: What was your commit message?
  - Answer: Added pioneers Ada and Alan

[ada lovelace](ada-lovelace.md), [alan turing](alan-turing.md)

#### Assignment 3: A Timeline of the Internet
To celebrate the interconnected world of computing, you will create a timeline of key events in the internet's history. You will do this by editing your README.md file directly on GitHub.
#### Instructions:
1. Go to your Digital-History-Notebook repository on GitHub.
2. Edit the **README.md** file directly.
3. At the bottom of the README.md file, add a new section titled Timeline: The Rise of the Internet.
4. In this new section, add a brief, bulleted timeline (7 points) of major milestones, such as the creation of ARPANET, the invention of TCP/IP, or the launch of the World Wide Web. Be sure to include pictures as well (might need to figure out how to add a picture in markdown).
5. Commit this change directly on GitHub with the message: "Added internet timeline".
6. Return to your local machine's terminal.
7. Use **git pull** to retrieve the timeline you created from your remote repository.
#### Report Status:
- 3.1: What command did you use to retrieve the new information from GitHub?
  - Answer: git pull
#### Assignment 4: The Modern Era
Now, let's add two more influential figures who shaped the modern era of computing.
#### Instructions:
1. On your local machine, create a new file named **bill-gates.md.** Research and write a short paragraph about his role in the personal computer revolution.
2. Create a second new file named **steve-jobs.md.** Research and write a short paragraph about his role in user interface and consumer technology.
3. In this README.md file, add two new hyperlinks below to the files you just created. The links must be named "Bill Gates" and "Steve Jobs" and must lead to the corresponding files.
4. Use **git add .** to stage the new files and the updated README.md.
5. Use **git commit -m "Added modern innovators"** to save your work.
6. Use **git push** to publish your changes.
#### Report Status:
- **4.1:** What command did you use to save your changes to your local notebook?
  - Answer: git add ., git commit -m "added modern innovators
- **4.2:** What command did you use to publish your changes to the remote repository?
  - Answer: git push

[bill gates](bill-gates.md), [steve jobs](steve-jobs.md)
#### Assignment 5: Peer Review
Your classmates are now reviewing your work. A peer has left a suggestion for one of your files.
#### Instructions:
1. Simulate a peer's action: go to your Digital-History-Notebook repository on GitHub.
2. Find and edit the **steve-jobs.md** file directly.
3. Add the following line to the end of the file: "Peer review: Could you add more details about the first Macintosh computer?"
4. Commit this change directly on GitHub with the message: "Peer review on Steve Jobs file".
5. Return to your local machine's terminal.
6. Use **git fetch** to check for updates, then use **git status** to see what's different.
7. Finally, use **git pull** to get your peer's feedback.
#### Report Status:
- **5.1:** What did git status tell you after you ran git fetch?
  - Answer:
- **5.2**: What command did you use to merge your peer's changes into your local notebook?
  - Answer:
#### Assignment 6: The Web's Inventor
With the internet's timeline now in your notebook, let's document one of its key figures.
#### Instructions:
1. On your local machine, create a new file named **tim-berners-lee.md.**
2. In this file, research and write a short paragraph about his role in creating the World Wide Web.
3. In this README.md file, add a hyperlink to this new file. The link should be named "Tim Berners-Lee".
4. Use git add . to stage the new file and the updated README.md.
5. Use git commit -m "Added Tim Berners-Lee" to save these changes.
6. Use git push to publish this final piece of research.
#### Report Status:
- **6.1:** What was your commit message for this assignment?
  - Answer:
- **6.2:** What command did you use to publish your work?
  - Answer:
#### Assignment 7: Final Edits
As a final step, you realize your notebook could use a concluding thought. You will add this directly on GitHub.
#### Instructions:
1. Go to your Digital-History-Notebook repository on GitHub.
2. Edit the **README.md** file directly.
3. At the very end of the file, add a new section titled Final Thoughts.
4. In this new section, write one or two sentences reflecting on the project.
5. Commit this change directly on GitHub with the message: "Final thoughts on project".
6. Return to your local machine's terminal and use git pull to get your concluding thoughts.
#### Report Status:
- **7.1:** What command did you use to retrieve your final thoughts from GitHub?
  - Answer:
#### High-Level Challenge: The Editing Mistake
You were working on a file for an extra credit assignment but made a mistake. You committed the error to your local history, but you realize your mistake before pushing. You need to completely erase the commit so there is no record of the error.
#### Instructions:
1. On your local machine, create a new file named **extra-credit.md.**
2. Add a line of text that you know is factually incorrect.
3. Use git add . and git commit -m "Mistake commit" to save this mistake locally.
4. **Do not push this commit.**
5. Now, find a way to **undo the last commit** and completely remove it from your local history.
6. Once undone, verify that the commit is gone by using git log.
#### Report Status:
- **Extra Credit:** What command(s) did you use to undo the commit, and why did you choose that particular method?
  - Answer:
#### Submission Instructions
When you have completed all assignments and answered all of the "Report Status" questions in your README.md file, you are ready to submit. Please submit the following to Google Classroom:
1. A link to your public Digital-History-Notebook repository.
2. A screenshot of your repository's commit history on GitHub. To find this, navigate to your repository, click the "commits" link near the top right, and take a screenshot of the page.<br><br>
Be sure to answer the questions above as well.

# Timeline:
## The rise of the internet
- 1936 - The first universal turing machine was built.
  - ![a turing machine](https://upload.wikimedia.org/wikipedia/commons/0/03/Turing_Machine_Model_Davey_2012.jpg)
- 1942 - the Atanasoff-Berry Computer was invented being the first digital computer.
  - ![the Atanastoff-Berry Computer](https://www.inventionandtech.com/sites/default/files/styles/landmark_node_/public/Atanasoff-Berry_Computer.jpg?itok=OAsntryE)
- 1943 - the Colossus, the first programable computer, was invented.
  - ![The Colossus computer](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Frontal_view_of_the_reconstructed_Colossus_at_The_National_Museum_of_Computing%2C_Bletchley_Park.jpg/960px-Frontal_view_of_the_reconstructed_Colossus_at_The_National_Museum_of_Computing%2C_Bletchley_Park.jpg)
- 1969 - ARPANET was created to share information securely.
  - ![the ARPANET logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCX17S_dBcLxFSisf4wNkCbrFddGIB7P5iGA&s)
- 1971 - The first home computer was made
  - ![the first home computer](https://observer.com/wp-content/uploads/sites/2/2015/08/ibm_pc_5150.jpg?quality=80)
- 1974 - TCP/IPs were invented.
  - ![how TCP/IPs work](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJuim1k_u3pD32j--6UMsqiqL_Po8ab33umA&s)
- 1989 - The World Wide Web was developed.
  - ![the world wide web logo](https://tariqaustralia.wordpress.com/wp-content/uploads/2013/04/14821565-internet-world-wide-web-concept-earth-globe-with-www-text-and-computer-hand-cursor-isolated-on-white.jpg?w=640)
