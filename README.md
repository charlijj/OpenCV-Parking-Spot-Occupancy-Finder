<h1 align="center">PARKING SPOT AVAILABILITY CHECKER</h1>

ABOUT:

The purpose of this program is to determine the occupancy status of a specific parking spot. The user can select a parking spot by clicking on the top-left corner of the spot in question. The information about the selected spot is saved in a file called "posList" and is reloaded each time the program is run.

Once a spot has been selected, the program converts the image of the spot into a threshold image, which is a black and white image where the threshold value is used to separate the pixels into either black or white. The number of white pixels in the threshold image is then counted. If the number of white pixels is greater than 130, the program considers the spot to be occupied. Otherwise, it is considered to be empty.

Dependencies:

python-3.8+

python3-pip

python3.8-venv

-----------------------------------------------------------

HOW TO RUN:

clone repo and cd into OpenCV-Parking-Spot-Occupancy-Finder/

cd virtualEnv

source bin/activate

pip install -r req.txt

python3 PL-space-detector.py 

TO SELECT PARKING SPOT, LEFT CLICK ON TOP LEFT CORNER
TO DESELECT PARKING SPOT, RIGHT CLICK ANYWHERE INSIDE SPOT BORDER

TO CLOSE PROGRAM PRESS THE SPACE BAR
