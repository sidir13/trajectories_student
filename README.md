# Analysis of student trajectories
This study analyzes learner trajectories on an online programming platform by examining submitted code using vector representations. These embeddings capture key program details, enabling the identification of similar attempts and transitions. The findings reveal factors influencing exercise success or failure.


# Hardware Requirements
The project was developed on a machine with the following specs:
RAM: 64 GB
Processor: 13th Gen Intel(R) Core(TM) i7-13800H   2.50 GHz
Operating System: Windows 11 Professionnel



# Dependencies
All the necessary dependencies for this project are listed in the requirements.txt file. Make sure to install them before running the code. The project was developed using Jupyter Notebook 6.5.4, so it is recommended to use this version or a compatible one to avoid any potential issues.


# How to Use the Project
This project contains four notebook files and three Python scripts, originally from another project (link: https://github.com/GCleuziou/code2aes2vec). Special thanks to Frédéric Flouvat, who has worked extensively on the referenced project.

The purpose of this project is to allow users to adapt it to their own data. To do so, simply transform your dataset to match the structure of the project’s data, which can be found in the datasets folder under the name NC5690. Once your data is in the correct format, replace the cells where I import my data with your own.

Additionally, there are cells that include data imports I created using this code. These are located in cells that contain if Variable, where Variable is set to False. To compute your own data (which may take a little longer in some cases), you need to change the value of Variable to True.

# Contributors
This project was developed by Idir Saidi, Frédéric Flouvat and Nicolas Durand.
