# Person Detector

## Description
Detect person and capture their image in a video feed. Built for Raspberry Pi 3 Buster using tflite models

## Getting Started
OpenCV and tensorfow lite needs some updated packages. Instead of using a newer operating system we can just update buster
```
sudo apt-get update
```
```
sudo apt-get dist-upgrade
```

## Creating and activating a virtual environment
Create:
```
python3 -m venv venv
```

Activate:
```
source venv/bin/activate
```

## Installing required dependencies
OpenCV and tensorflow has some specific dependecies that needs to be installed. I have written a bash script that automatically installs all the required dependencies.
```
bash requirements.sh
```

## Start the program (Inside the virtual environment)
python app.py

## Stop the program
Press "q" when in the screen

