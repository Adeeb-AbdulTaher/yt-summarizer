<h1 align="center"> YouTube-Summarizer</h1>

## Problem Statement

The Covid Pandemic has changed many of our ways including how newer generations are getting educated; watching hour long recorded lecture videos, trying their best to grasp concepts but failing to do so efficiently. 

## GOAL

Our time efficient solution revolves around AI technologies like Natural Language Processing and Machine Learning by summarizing the video content into a text passage to greatly improve the learning experience of the user whilst consuming their least possible time, bringing all of this to an easy to use user-friendly interface.

## Process

* Get the English Trasncript from the user given YouTube link
* Remove all the time stamps and clean it and store in one text document
* Run the NLP text summarization algorithm on the given document
* Set the location for the summary to be saved in
* Develop a GUI for the same

## GUI
![GUI](GUI.png)
![Result](result.gif)


<br/>
<br/>
<br/>
<h1 align="center"> STEPS</h1>

<h1> 1) </h1> First make sure you have python installed and ensure pip is installed and added to the PATH variable and then install virtualenv using the command:

 `pip install virtualenv`
 
<h1> 2) </h1>&nbspOpen the terminal or Command Prompt and navigate to the directory where the project needs to be created. Run this command to create a virtualenv with the name "summarizer":

`virtualenv summarizer`

<h1> 3) </h1>  Activate the virtual environment using

`summarizer\scripts\activate` or if already in the folder `.\scripts\activate`


## SCOPE

- Allow support for Udemy and other such educational websites
- Process entire playists and save in separate files
