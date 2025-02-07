# Double-Double-Dominoes
1. the libraries required to run the project including the full version of each library

numpy==1.21.2 </br>
opencv_python==4.5.3.56

2. how to run your solution and where to look for the output file.

Regular Task + Bonus Task</br>
script: Solution.ipynb </br>
function: run all the cells in order from the first one to the last one, the last 2 cells call the 2 functions: regular_task(5) and bonus_task(10) </br>
	  make sure the following paths are correct: </br>
		- in cell 14 (function play_game(game_no)) at line 1 dir_path must be initialized with the path of the folder where the test images are </br>
		- in cell 22 (function find_mistakes(board_no)) at line 1 dir_path must be initialized with the path of the folder where the test images are </br>
output: the output consists of txt files in the folders results/regular_tasks and results/bonus_task that will be automatically created if they do not exist
