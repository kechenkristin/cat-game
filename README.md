## About this project
This project originally from ucb cs61a fall2020 project2, it is a typing game which supports various functionalities like computing typing speed, autocorrect, mutiplayers. 
The GUI and the intergration with front end is done by ucb, I'm in charge of the implementation of back-end logic.
My implementation has passed all the local test cases of ucb's ok server.
![avatar](https://github.com/kechenkristin/imagesGitHub/blob/main/projects/CS61A/grade.png)

## Features
1. User can select which paragraph to type and can choose a specific topic( better to be cat related)
![avatar](https://github.com/kechenkristin/imagesGitHub/blob/main/projects/CS61A/demo.png)

2. Calculate and show your typing speed, 
Implementing it by calculating the accuracy and computing the words typed per minute.
![avatar](https://github.com/kechenkristin/imagesGitHub/blob/main/projects/CS61A/speed.png)

3.Autocorrect
Whenever the user presses the space bar, if the last word they typed doesn't match a word in the dictionary but is close to one, 
then that similar word will be substituted for what they typed.
![avatar](https://github.com/kechenkristin/imagesGitHub/blob/main/projects/CS61A/autocorret.png)

4.Mutiplayer
![avatar](https://github.com/kechenkristin/imagesGitHub/blob/main/projects/CS61A/mutiplayer.png)



## Project Structure
cats.py: The typing test logic.

utils.py: Utility functions for interacting with files and strings.

ucb.py: Utility functions for CS 61A projects.

data/sample_paragraphs.txt: A file containing text samples to be typed. These are scraped Wikipedia articles about various topics.

data/common_words.txt: A file containing common English words in order of frequency.

data/words.txt: A file containing many more English words in order of frequency.

gui.py: A web server for the web-based graphical user interface (GUI).

gui_files: A directory of files needed for the graphical user interface (GUI).

images: A directory of images.

ok, proj02.ok, tests: Testing files.

## Project Demo
https://cats.cs61a.org/

## Contact
Author: Kechen Liu

Email: kechenkristin@gmail.com

Project Link:https://github.com/kechenkristin/cat-game

