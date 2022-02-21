# ITS-Team-Sapuangin

# Introduction
This Repository contain :
1. main.ipynb
2. battery_maintenance.ipynb
3. motor_maintenance.ipynb
4. brakepad_maintenance.ipynb
5. best_workshop.ipynb
6. final_result.xlsx
7. README.md

There are some module need to install:
jupyter==1.0.0
sklearn==0.0
graphviz==0.19.1
pandas==1.4.1
seaborn==0.11.2
h5py==3.6.0
or you can install them by type 
pip install -r requirements.txt 
on folder root project

How to run:
### If you want to run whole code follow this instruction

1. Download all files in this repository 
2. Download folder dataset in this link [here](https://drive.google.com/drive/folders/10lxxbqzn1Qkjn7hdhWzokYKtrzqIJ5yQ?usp=sharing)
3. Put all files in same folder
4. Open file named "main.ipynb" in Jupyter notebook
5. Run whole notebook
6. There will some results printed in screen
7. This code will produce final result named "final_result.xlsx" that contain list of best workshop 

### If you want to run with more specific output follow this instruction

1. Download all files in this repository 
2. Download folder dataset in this link [here]()
3. Put all files in same folder
4. Open code (battery_maintenance.ipynb; motor_maintenance.ipynb; brakepad_maintenance.ipynb ) that you want to run in Jupyter notebook
5. There will printed specific output in your screen
6. After run maintenance code you will got status of every components on "need_maintenance.xlsx" that in folder dataset
7. With run "best_workshop.ipynb" code you will get list of best workshop for repair your components


# Brakepad

How to run Brakepad code:
1. Download file "Brakepad.ipynb" 
2. Open file in Jupyter notebook
3. Run whole notebook
4. If the code is executed successfully, there will printed information about percentage & thickness of brakepad
5. This is the decision tree diagram will look like this [tree](https://user-images.githubusercontent.com/99813942/154808293-eb9b0004-6ee9-40ff-8608-a32543d512a0.png)

# Battery

How to run Battery Maintenance code:
1. Download file "battery_maintenance.ipynb" 
2. Open file in Jupyter notebook
3. Run whole notebook
4. If the code is executed successfully, there will print information about battery life cycle.

# Motor

How to run Motor Maintenance code:
1. Download file "motor_maintenance.ipynb" 
2. Open file in Jupyter notebook
3. Run whole notebook
4. If the code is executed successfully, there will print information about the classification of motor condition, for example: normal or imbalance 

# Workshop recommender
1. Download need_maintenance.xlsx and datashet_workshop.xlsx
2. Make sure need_maintenance.xlsx and datashet_workshop.xlsx are exist in dataset folder
3. Download file "best_workshop.ipynb" 
4. Open file in Jupyter notebook
5. Run notebook
6. If the code is executed successfully, there will show the recommendation workshop and file final_result.xlsx will exist in current folder
