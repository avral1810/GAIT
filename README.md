# GAIT
#REQUIREMENTS

1. Operating System
    1. macOS or Linux
    
2. Software Packages
    1. Python3
    2. OpenCV3
    3. Tensorflow
    4. Pandas (python3)

3. Hardware Requirements
    1. webcam
    2. 4GB RAM
    3. 1.4GHz CPU (Single or Multicore)
    4. 1GB of secorndary storage
    5. Color marker

#HOW TO RUN

TO TEST A SUBJECT
1. Calibrate the colorLED.py using calibration.py (python3 calibration.py --filter HSV --webcam)
2. Run colorLED.py on subject for more than 3 mins (python3 colorLED.py run)
4. run run.sh with test file (./run.sh { dir/to/file }) (dir will be under dataFile/test1/{date}/{file})

TO ADD NEW SUBJECT
1. Calibrate the colorLED.py using calibration.py (python3 calibration.py --filter HSV --webcam)
2. Run colorLED.py on subject for more than 10 mins at different speeds (python3 colorLED.py train)
3. Run ./train.sh with the folder created by step 2, found in dataFiles/{name}/{date}/{file} (./train.sh {dir/to/files})

Everything in this docuemnt placed in { } is a variable and need to be replaced during actual running of the code.
