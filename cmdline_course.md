---
layout: default
---

## Introduction

<img src="http://img.youtube.com/vi/I_THXnIoxNg/0.jpg" alt="Photo" hspace="20" width="30%" align="right"/> My name is Dean Rahman. In fall of 2019 (period II), I studied the course titled "Command Line Tools for Linguists" at University of Helsinki. It was taught by fantastic lecturers [Hande Celikkanat](https://www.linkedin.com/in/hande-celikkanat-08664423/) and [Miikka Silfverberg](https://www.linkedin.com/in/miikka-silfverberg-78146019). Here is the [description of the course](https://courses.helsinki.fi/en/kik-lg219/129824412) by the course organizers. Below is a summary of my experience with the course which I have a written as a part of the final project for the course.

Like all 5-credit single-period courses at U of Hel (which constitute the great majority of courses here), the Command Line course was 7 weeks of action-packed compressed learning fun, each week with a new module of concepts. Hence the week by week structure of the summary. (The redundant numbering with each of the week numbers is to highlight the use of a markdown list discussed in week 7 :) Enjoy!            

## Experience (List)

1. Week 1

   Introduction to Command Line Environments

   We familiarized ourselves with Command Line Environments. Even though the majority of us had already gotten at least a peak at command line environments before (e.g. in the prerequisite course Introduction to Linguistics), this is the spot for me to express what each of us felt the first time we really comprehended what command lines were about: Holy Cow! We were culture shocked and delighted at the simultaneous self-service orientation and simplicity of  command lines after growing up with graphical user interfaces (GUIs) such as Windows, Macs and smartphones. The most cliché but effective explanation to a newbie is something along the lines of..imagine, instead of clicking an highlighting a file icon inside a folder and dragging it into another folder, you type in a highly specific sentence to the computer so it does the same thing. (This is of course because the folders thing is a just an analogy for our human brains for the construct that computers use in an array of memory..blah blah blah..). As you will see if you read the rest of the course summary, moving a file is the tip of the visible tip of the hidden iceberg, but for this week, it's enough to say the other simple things we learned which were mind blowing.

   Typing in the simple two character command <ls> (abbreviation for list), lists out all the visible files and folders in a folder (called "directory" in non-iconic speak). You can move out of a directory (folder) to go one folder up by typing <cd ..>. Using some pre-specified few characters or the folder path allows you to see the list of files in any directory or change to any directory (e.g. cd ~/KIK-LG219/final/). <wget https//somewebsite.com/somefile.jpg> lets you download a file from a website without opening up a GUI browser. Holy cow! One of the students remembers a reference to this in either the movie The Social Network or the show Silicone Valley, both about programmers.  

2. Week 2

   Navigating a UNIX System

   Stuff we were doing in Week 1 to files (copying, moving, deleting), we started doing to entire directories in Week 2! We also learned how to move files *between* computers. Holy guocamole! (The other computer, not the one you're physically typing on, being called a "remote server" through a remote connection command named <scp>).

   Besides all the wowing, this is the week that the necessary mindset became extra clear for me. It was in the context of zipping and unzipping files, but it applies to everything command line. Should we sit around memorizing <tar -czvf name-of-archive.tar.gz /path/to/directory-or-file> to zip files? Or <tar -xf name-of-archive.tar.\
   gz> to unzip files? Of course not. Either we acquire these or any commands because we use these every day or we always have the internet for reference. While learning by Googling is becoming the modus operandi for most practitioners, especially in a powerful domain as powerful as command line, it is essential to become aware of what is possible and expand the problem solving mindset and look up exact commands (syntax) by reference.    

3. Week 3

   Basic Corpus Processing

   The simple command <wc text_file.txt>. That's how we can find out the number of lines words and characters are in a file. What about getting rid of all capital letters in a file? We also learned how to do that and every other cool thing we thought was only ever possible in Microsoft Word. What about text processing in Microsoft Excel? Well, we can cut and paste columns in formatted text files right at the command line.

   It's one thing to be able to use this functions in an out of the box software. It's another thing to be able to program them right from a (free) operating system. And forget about Word and Excel; they're nothing. We even learned the command line sequences that allowed us to do something we could only do using AntConc previously. Thats right, we learned all the steps to compute descending word frequencies in a file as well! (I knew you were wondering why we would want to change all upper cases :)

4. Week 4

   Advanced Corpus Processing

   Regex, grep and sed. In Week 4, we started getting into the hardcore stuff. Regular expressions are a way of expressing different but related words or characer strings using a single expression. Using the grep command, we learned out to display or output all of the sentences or lines with words that satisfy a regular expression. Using the sed command, we learned how to replace all instances of strings satisfying a regular expression with a different expression.

   As with Week 3, it became clear not only how softwares implement word processing features such as find-and-replace which we used as laypersons, but also how to execute aslew of processes which would now be available to us as aspiring language technologists. Each week's lessons were underscored with a quiz and this week's quiz was my favorite because every question felt as if I were solving a puzzle for fun.

5. Week 5

   Scripting and Configuration Files

6. Week 6

   Installing and Running Programs

7. Week 7

   Version control on github  
   Markdown files (simple text files with links to websites, references to pictures and some cool text-based tricks such as tables and lists) and building static webpages thereof using Jeckyll. Hosting on github.io

+ Final Project

   Webpage introducing myself created from a markdown file.
   A similarly created webpage introducing this course. (You are in fact looking at this very page).
   A webpage created in Latex using Overleaf of my CV.

## A Summary of the Summary (Table)

`Week` | `Theme` | `Example`
--- | --- | ---
1 | Command Line Enviroment | 3
2 | Navigating Unix Systems | 3
3 | Corpus Processing | 3
4 | Corpus Processing continued | 3
5 | Scripting and Configuration Files | 3
6 | Installing and Running Programs | 3
7 | Version Control | 3
Final | Markdown-based Static Websites | 3

## Concluding thoughts
must have a table (done), picture (placeholder in) and a list (??) somewhere

Operate in a linux environment. Process corpora..and hilarious comics about every new week's topic

