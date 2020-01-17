## Kindergarten Oral Testing GUI
There are typically 20-25 students in a Kindergarten class. Say, every month they have an oral exam for teachers to get an understanding of the progress of the students on how much they have learnt in that month. The teacher will typically call each student near her, ask the questions, write down the answers and their score. She will do this for each student, so on an average say 20 times. Can you imagine how much time and energy is spent unnecessarily by repeating the questions and recording everything by hand? What if all this could be done automatically? Keeping these problems in mind, I was determined to find a solution easier for the teachers as well as interesting for the students. In today's age of internet and computers, we can find innovative solutions to minimize efforts and conveniently infer student learning trends from the data.

This kindergarten oral testing GUI has the following features:
- Take user input of student name and roll number.
- Begin the test, record student answers for each question and calculate the score.
- Restart the process for the next student.
- Display a report in table format with name, roll number, score and answers for all the students. This report can be downloaded and further analyzed as well.
- Create a database with the report table for future usage and analysis at the end of the year.
- Generate and display graphs for count of students for each score, percentage of students for each score, the class statistics and list of students and their scores who need re-teaching.

I have used the standard GUI toolkit of tkinter for generating and displaying the testing GUI, pygame library for audio messages and deep learning speech_recognition to check student answers. I have given a sample of five questions in the testing GUI. These questions can easily be changed by the teacher by modifying the images, the questions and answers.

### Installation
- Download the images(PNG files) and the PPT on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
- If you don't have Tkinter installed on your machine, please follow instructions here to install it.
