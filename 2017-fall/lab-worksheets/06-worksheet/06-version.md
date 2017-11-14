# Worksheet 6: Version Control

## Instructions

- Due on Tuesday (Nov, 14th) at Midnight
- Copy the worksheet, answer the questions, and SUBMIT TO [OUR GITHUB
  REPOSITORY](https://github.com/denten-courses/technologies-of-dissent/tree/master/2017-fall/lab-worksheets/06-worksheet)
via pull request (see question 8).
- It is recommended that you Complete the GitHub "Hello World" tutorial before
  starting with this worksheet.
- Include your UNI id on your submission (I recommend you don't use your full
  name).

## Questions

1. In your own words, what is version (or source) control?

Version control allows a user to record changes that occur to a file over a period of time.  This allows a user to look back at specific revisions of a document - it is a way to control changes to file over time.  Revisions can be compared amongst users, can sometimes be merged, and, if needed, can be restored to the file.

2. Explain the difference between Git and GitHub.

Git is a version control system, so the definition above applies.  It allows users to track changes locally.  GitHub, on the other hand, is an online repository that allows for the version control management of Git, except via the web.  It also adds on some more features specifically meant for collaborators, such as wikis for projects 

3. In a few sentences, explain what a "commit" is?

When you save something on Git/GitHub, you are making a "commit."  This would be a revision that you made to a file.  Each commit has associated with it a commit message.  This commit message is a way for the user to articulate why she/he made certain revisions/changes to a file.

4. What is a "branch" in Git terms?

A "branch" in Git is one version of a repository.  A repository has one default branch, the "master branch".  When you create other branches from the master branch, you are making a copy of the master branch at that specific moment in time.  You can then edit that specific copy of the master branch without changing that actual master branch itself.

5. What is a repository? Explain what happens when you "push" to and "pull"
   from a repository?
   
A repository is a way to organize files on Git/GitHub. It can include many types of files (data sets, images, etc.)  In short, it     is a place that contains data.  A "push" is a way of sending your commit changes to a remote repository, say, GitHub. Pulling, on the other hand, will take any changes from a remote repository and merge them with your local repository.  

6. What is involved in the "clone" operation?

 When you "clone" a repository, you clone it from a remote repository in order to create a local copy for yourself.  You have to "clone or download" the repository to your local computer.  GitHub gives instructions on how to clone a repository on GitHub:
 
"On GitHub, navigate to the main page of the repository.

Clone or download button Under the repository name, click Clone or download.

Clone URL button In the Clone with HTTPs section, click  to copy the clone URL for the repository.

Open Git Bash.

Change the current working directory to the location where you want the cloned directory to be made.

Type git clone, and then paste the URL you copied in Step 2.

Press Enter. Your local clone will be created."

So cloning is effectively pulling, except that if you are working with others, cloning only takes a screenshot of the master branch at that specific point in time.  Pulling, on the other hand, isn't a screenshot, but a merge of what has been updated to the master branch.  Pulling will register the constant changes occurring in the master branch from the pushes of the other users.
 
7. Find an example of Git being used for a peer production project. In several
   paragraphs answer the following: Who are they? What do they do? Who
maintains the repository? What are the rules for contributing?

Croducate.me is a peer production product project: https://github.com/crowducate/crowducate-platform/ 
Crowducate is about democratizing education, but in a more structured way than, say, Wikipedia.   In the about page, they write that “You are the crowd.”  This includes the people who take courses, and people who create courses.  In addition, users can copy the courses already made and develop new ones (more specialized, say).  This is done through open source software and most notably GitHub.  
“In contrast to MOOCs, at Crowducate all courses are open source. This means people can copy courses to develop into different branches. Furthermore, the whole software itself is open source, too. You can find the source code at Github. You see, we are serious about open source.” 

The idea for Crowducate is that the formal teaching structure of the teacher possessing knowledge and sharing it to students can be flipped, where the student can then become a “teacher” with another course, or can create a course that goes even further into the material that was originally made.  Individuals can contribute in notably three ways: 1) They can send a request to a teacher (the one who created the lecture) and make a comment about something specifically in the lecture (whether that is a grammar mistake, something is too vague, etc.)  Constant feedback to the teacher will allow four the course to get better and better.  2)  You can copy an existing course and based of it develop a new one (it sounds analogous to cloning in Git).  3)  If you sign up and login, you have the option to create a course.  

Crowducate’s guiding principles are:
“Everyone has the right to education. Education shall be free.
Work towards Universal access to all knowledge
Foster cultural diversity
Support participatory culture and the rights to produce and remix
Knowledge is constructed
Facilitate peer learning
Build trust through open communication and transparency
Respect freedom, privacy, and decentralization
Think and communicate in systems (1, 2, 3, 4)
Preserve and improve the open data and knowledge commons (linked, open data)
Align with existing common good initiatives”

This is from their website https://github.com/Crowducate/crowducate-platform 

8. Submit this worksheet (in .txt or .md plain text format) by filing a pull
   request to our Github repository.

## Extra Challenge

9. Explain the difference between a fork and a clone.

10. Find a small spelling error on the *Programming Historian* and submit a
    pull request to the owners. (Check with me for this option, if you are not
sure).

## Hints

Steps for your first pull request (PR):

- Fork the project (via the GitHub interface online). This copies the *whole
  repository* from my account on the GitHub servers to your account.

- Clone the project (via the command line or GUI). This copies the repository
  from your remote GitHub account to your local machine.

- Make your changes. In this case you are simply adding a file to the
  repository (give it a unique file name).

- Push your changes to GitHub. This copies your local changes to the remote.

- Using the GitHub interface file a pull request. This will notify me to pull
  your changes into my repository (from the first step).


