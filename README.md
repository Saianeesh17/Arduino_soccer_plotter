The purpose of this project is to map soccer attacks given x,y coordinates (the ball position) during certain intervals of the attack.
The python code contains some example data of random soccer attacks I mapped out manually by watching some youtube clips.
The circuit diagram to set up the circuit is as follows:
![image](https://github.com/user-attachments/assets/ee3f90b1-c60c-4abf-8a60-414a2da5ed3f)

Link to mermaid code for circuit diagram: https://mermaid.live/edit#pako:eNqVlFFvgjAQx79KU2OiCSRQNWM8LHFBzRY1Zsu2LOJDA0WJQE2BuWXxu6_SIowuhvFQ2t6_v-vdtf2GHvUJtOGW4cMOzJ_cBPBvzPw8TOha_sGCbPEG6PodcFj4QZi5fpkvkWEM5Bh0zE27lUhZieRK0Xa7YEWPfN6jSUK8LKRJKizFdK83egUBo3HpqN-vb6umrPtsOJgxmie-6mG2dHo93vzF5NNXiDIWU2WWedB1sHpbgNXDElgKvBKVmtsWGtNoIzIVkRwU4SxoRnk1kXX__qgPraqOzdDQtdBKZ0jJkKoZtNAMW2hGikYOqrhQLa7fp8yLcJo6JABYcoMwiuyOObGsyUhLM0b3xO4EQSD7-jH0s52NDp-aRyPKClsD5YtECdJ0OjYM40Kq-pJkViRua5Di8-YlaDgYG8ObViB1S4fiIgiQM0BTNP0fqIa7VEBmrG6SB0orCyAyUVeIY6aJqoj46ubiwmrnK1bsGGowJizGoc8fpu-z0IXZjsTEhTbv-pjtXegmJ67DeUafvxIP2hnLiQb5zd7uoB3gKOWj_ODjjDgh5q9bLCSnHzwchcM

The parts for this project have been 3d printed.

To run this project, you will need to download the python code, and install the serial library using the following command:
pip install serial

you will then need to flash the code within the .ino file to an arduino of your choice

Run the arduino first connected to the COM port of your choice and make sure to edit the python program to accomodate the appropriate com port.
Then run the python program and choose which attack you want to simulate using the plotter.

It should run on the arduino.

Inspiration for plotter design:
https://www.youtube.com/watch?v=og1506q67mo&t=46s
