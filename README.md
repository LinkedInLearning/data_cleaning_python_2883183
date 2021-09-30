# Data Cleaning in Python Essential Training
This is the repository for the LinkedIn Learning course Data Cleaning in Python Essential Training. The full course is available from [LinkedIn Learning][lil-course-url].

![Data Cleaning in Python Essential Training][lil-thumbnail-url] 

Do you need to understand how to keep data clean and well-organized for your company? In this course, instructor Miki Tebeka explains why clean data is so important, what can cause errors, and how to detect, prevent, and fix errors to keep your data clean. Miki explains the types of errors that can occur in data, as well as missing values or bad values in the data. He goes over how human errors, machine-introduced errors, and design errors can find their way into your data, then shows you how to detect these errors. Miki dives into error prevention, with techniques like digital signatures, data pipelines and automation, and transactions. He concludes with ways you can fix errors, including renaming fields, fixing types, joining and splitting data, and more.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"
	
## Installing
1. To use these exercise files, you must have the following installed:
	- Python 3.6 and up
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. Install the dependencies
    - `python -m pip install -r requirements.txt`


### Instructor

Miki Tebeka 
                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/miki-tebeka).

[lil-course-url]: https://www.linkedin.com/learning/data-cleaning-in-python-essential-training
[lil-thumbnail-url]: https://cdn.lynda.com/course/2883183/2883183-1632766207382-16x9.jpg




