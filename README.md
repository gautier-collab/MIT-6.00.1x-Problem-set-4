# MIT-6.00.1x-Problem-set-4-Word-game

This repository contains two different containerized versions of a word game created through the 4th problem set of the course "Introduction to Computer Science and Programming Using Python" (MIT 6.00.1x) of the Massachusetts Institute of Technology. You can find the all the instructions for that problem set on edx.org.

Version A:
Letters are dealt to players, who then construct one or more words out of their letters. Each valid word receives a score, based on the length of the word and the letters in that word.

Version B:
This is the same as the version A except for the fact that the player can now choose to let the computer find the optimal solution.

For each game version, open the directory of the same name in your UNIX terminal and run the following command: sudo docker build -t mit-python-problem-4 . && echo -e "\n\n" && sudo docker run -i -t mit-python-problem-4
