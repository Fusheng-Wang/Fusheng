# a1: Basic Tools I
### Preparation
1. Please read: (1) Freeman and Ross(2019), Chapters 1-4 and (2) O’Neil (2016), Introduction (pp. 1-14).
1. Download and install [Atom](https://atom.io/) or other text editor (if you prefer).
2. Download and install [Git](https://git-scm.com/).
3. Sign-up for a [GitHub](https://github.com/) user account.
4. Download and install [R](https://cran.r-project.org/) (optional for this assignment).
5. Download and install [RStudio](https://www.rstudio.com/) (optional for this assignment).

### Useful documentation

* [Markdown documentation for GitHub](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)
* [Markdown 2-pager cheetsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

### Notes on grading
* This assignment as 53 points, as indicated in requirements below
* Partial points can be awarded
* All writing should be concise, clear, and free of spelling and grammatical errors

### Objectives
**Please note:** This assignment should be completed _individually_.

1. Demonstrate how to navigate the file system from the command line and manage files, with these and similar commands (see F&R, chap. 2):
```
pwd             # print working directory
cd <PATH>       # change directory to <path>
cd ..           # change to parent directory (go up)
ls              # list files of current directory
ls -las         # list files (show some details)
#
mkdir <PATH>         # make a directory
rm <PATH>            # remove a file or directory
cp <PATH1> <PATH2>   # copy a file or directory
cat <FILENAME>       # display the contents of a file
```
2. Describe the purpose of git and GitHub (see F&R, chap. 3).
3. Demonstrate how to manage a project using git and GitHub, with these and similar commands (see F&R, chap. 3):
```
# Setting up basic identifying information
git config --global user.name <YOUR FULL NAME>
git config --global user.email <YOUR EMAIL ADDRESS>
#
git clone <REPO_URL>             # Copy a repo to your machine
git status                       # Check the status of a repo
git add <FILENAME>               # Add file to staging area
git add .                        # Add all files in current directory to  staging area
git git commit -m "<A MESSAGE>"  # Make changes s
git push
```
4. Use markdown syntax to format document (see F&R, chap. 4).
5. Consider how data science can be both a **tool** and a **weapon**.
6. Professional practice: (a) Work closely with requirements; and (b) Reflect on the benefits/costs of planning before doing.

## Part I: The Command line
In the root directory you will find a file named ``git-commands.md``. The purpose of this file is for you to demonstrate your knowledge of working with the terminal. You will document the commands that you used to complete each of the tasks.

**Your work**: Following each prompt in the file ``git-commands.md``, write the line of code that you used to accomplish the task or otherwise answer the question.

 Make sure to save this file in your text editor, then add, commit, and push the changes to GitHub.

 After completing this assignment, you can continue to add commands to this file and use it as a reference for your own work.

## Part II: Working with Markdown
### Background
Please read the following obituaries. Each of these people were extraordinary coders, thinkers, and innovators. As your read, consider their personal lives and their professional accomplishments:

* [Ada Lovelace](https://www.nytimes.com/interactive/2018/obituaries/overlooked-ada-lovelace.html)
* [Alan Turning](https://www.nytimes.com/2019/06/05/obituaries/alan-turing-overlooked.html)
* [Karen Spärck Jones](https://www.nytimes.com/2019/01/02/obituaries/karen-sparck-jones-overlooked.html)
* [Douglas Engelbart](https://www.nytimes.com/2013/07/04/technology/douglas-c-engelbart-inventor-of-the-computer-mouse-dies-at-88.html)

### Requirements
Now that you have read their obituaries, write a  markdown document (one  page) that meets the following requirements.

1. **Content requirements [14 points total]**. Choose *two* of these extraordinary people and summarize their lives with the following information:
  * Full name [1 point]
  * Photograph [1 point]
  * Date of birth and death and age at death [2 points]
  * Main area of research [1 point]
  * Two key facts about their personal lives [2 points]
  * Two key professional contributions [2 points]
  * A key quotation from the obituary [1 point]
  * A reflective paragraph. If you could, what question would you ask Lovelace, Turning, Spärck Jones, or Engelbart? Give your question and explain why you would ask it? (30-50 words) [2 points]
  * A link to the obituary - link text [1 point]
  * A link to a Wikipedia entry - link text [1 point]
2. **Presentation requirements [2 points total]**.
  * _Consistency_. Format each entry in the same manner [2 points]
  * _Simplicity_. Seek an elegant - simple and clear - presentation [no points]
3. **Coding requirements [11 points total]**. To present the above information, _for each person_, use _all_ of the following markdown elements:
  * A top-level heading (``<h1>``) [1 point]
  * An unordered list [1 point]
  * **Bold** and _italics_ for emphasis [2 points]
  * An image tag to present a photograph (include the `ALT` tag and descriptive text for screen reader accessibility) [2 points]
  * A blockquote to format the key quotation [1 point]
  * A paragraph to present your reflective paragraph [1 point]
  * Hypertext links to the obituary and to a Wikipedia entry [2  points]
  * Include an emoji -- e.g., :rocket: -- in your reflective paragraph [1 point]
4. **Filenames and directories requirements [5 total points]**.
  * Create two directories in `\images\photographs\people`, one directory for each person, named by their last name [2 points]
  * Put the two photographs into the respective directories [2 points]
  * The document should be named `README.md`, located in the root directory of the repository [1 point]
  * Once you are finished, add, commit, and push all changes to GitHub.

**Notes on Professional Practice**: (1) If you find a requirement _ambiguous_, that is, unclear ask your Teaching Assistant or post a question on Teams. Requirements should be _unambiguous_. Always resolve ambiguous requirements before designing and implementing solutions by **communicating directly** with your project manager or team member. (2) Before starting to code, read all of the requirements, draw a **hand-sketch** of your page design, and create a **todo list** of the steps you need to follow. It is almost always a good idea to do a bit of planning before starting to code. Reflect: What are the costs/benefits of planning?

## Part III: Data Science: Tool for Good or Weapon?
A. Data science can be weapon, a tool that harms human beings. As we shall see, O'Neil (2016) presents a devastating critique of data science. We'll explore her arguments in some detail, but to start please answer these two questions from pages 1-14:
  1. By quoting from O'Neil (2016), define "Weapon of Math Destruction" (30-50 words). [1 point for accurate quote; 1 point for introducing and clarifying the quotation]
  2. Give an example of a WMD (30-50 words) [2 points for a complete example]

B. Data science can also, of course, be a tool for good. It can, for example, be used to make discovers about our social and natural worlds. One recent discovery made possible by data science is found in the paper by Wang, Stanovsky, Weihs, & Etzioni (2019). Browse this paper (see below for link) but please note: We do not expect you to understand the full paper in detail. Now, answer this question:
1. In your own words (a) what the the main research question; and (b) What did they find? (about 50 words) [1 point for (a); 1 point for (b)]

**Submission requirements.** Please create a file, named `data_science.md`, located the root directory of your repository. Write your answers with markdown in that file. Please format your answers neatly. Once you are finished, add, commit, and push all changes to GitHub.

Wang, L. L., Stanovsky, G., Weihs, L., & Etzioni, O. (2019). Gender trends in computer science authorship. CoRR, abs/1906.07883. Retrieved from http://arxiv.org/abs/1906.07883
