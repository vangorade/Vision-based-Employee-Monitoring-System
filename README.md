# Vision-based-Employee-Monitoring-System
<p align="center">
  <img src="https://github.com/vangorade/Vision-based-Employee-Monitoring-System/blob/master/src/UI.png" height="500" width="500"/>
</p>

## Intro
This repository contains source code for my personal project Vision-based-Employee-Monitoring-System.

## Setup
First download the code by git clone this repo:
```bash
git clone https://github.com/vangorade/Vision-based-Employee-Monitoring-System
```
then create conda/pip env and install dependencies using 
```bash
conda activate benvname
pip install -r requirements.txt
```
Or you can create docker enviourment using provided Dockerfile 

## Run
```bash
cd src/
python app.py
```
1. fill information
2. click Take images -> webcam will start
3. click Train images 
4. click Predict -> webcam will start

## Code structure
The src folder contains all of the implementation code.
+ src/ main folder
+ src/app.py main file 
+ src/client.py contains important functions
+ other folders contain as folder name suggest

## Referances
1. https://github.com/ipazc/mtcnn
2. https://github.com/deepinsight/insightface
