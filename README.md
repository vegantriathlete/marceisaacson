# Course Creation Template
Base course creation template that is meant to be forked to create actual course instances

The idea is that you will clone this template for each course you are working on and give it an appropriate name for the directory. For example, you could clone this repository and name it My-Amazing-Udemy-Course. Then, you would have a new directory on your computer with the name My-Amazing-Udemy-Course which would contain all the files, directories and subdirectories in this template.

**For those not using version control:**  
Don't get hung up on whether you are forking this or simply downloading and extracting a zip file.

**For those who don't know:**
* The .md extension stands for "markdown". Don't worry it's still just a simple text file. If you like, you can [learn about markdown](https://guides.github.com/features/mastering-markdown/).
* It's common in technical circles that some files don't have extensions. You can safely assume that all files without extensions in this repository are just text files. Feel free to rename them with a .txt extension so that you can easily open them on your computer if you are having trouble.

## Before you get started
Do yourself a big favor and make sure that you have enrolled in and completed the following official Udemy courses:
* https://www.udemy.com/official-udemy-instructor-course/
* https://www.udemy.com/udemy-policies/
* https://www.udemy.com/how-to-market-your-udemy-course/

## The process
Udemy has documented the course creation process. [Check it out for yourself.](https://teach.udemy.com/process/)

## For those who do want to use version control
While above I did use the words "fork" and "clone", that is probably not
what you are actually going to do on an ongoing basis.

You will initially create a fork / clone of the repository.
(assume the directory is named course-creation-template)

Then, you are likely to follow this process as you create actual
course instances:
* `cp -r course-creation-template your-new-course`
* `cd your-new-course`
* `rm -rf .git`
* `git init`
* `git add .`
* `git commit -m 'Import from Course Creation Template'`

If you are actually planning to host the repository on Github:
* Create a new repository without a README, license or .gitignore
* Copy the lines with the repository's specific `git remote add origin git@github.com:. . .` and the `git push -u origin master` that appear on the following screen
* Paste those lines in your terminal and press Enter
