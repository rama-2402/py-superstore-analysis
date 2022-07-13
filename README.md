# py-superstore-analysis
Superstore Sales Data Analysis is a practice project performing Exploratory Data Analysis on some example Superstore sales data. This project is to learn and understand different data analytic techniques to gain insight from a raw sales data.

## Packages Used
This project uses the following python libraries for data analysis
* Numpy
* Pandas
* Matplotlib
## Clone the project
The packages used in the project are installed in a python virtual environment to avoid conflicts with existing packages. Follow the steps to clone and run the project in jupyter notebook
```
git clone https://github.com/rama-2402/py-superstore-analysis.git
cd py-superstore-analysis/
```
After navigating to the project directory, Create a virtual environment and install the packges using the following commands.
```
python3 -m venv venv/

#If you are using bash shell 
source venv/bin/activate 

#If you are using Fish shell
source venv/bin/activate.fish

#To install the necessary dependencies
pip install -r requirements.txt 

#To run the jupyter notebook 
jupyter notebook
```
## Troubleshooting
```
#Nuke the environment
rm -r venv/

#Install a new environment and dependencies
python3 -m venv venv/                 
pip install -r requirements.txt 
```

## Analysis
Following analysis has been made on the sales data
* Data cleaning
* Finding Cities with highest sales recorded
* Finding top 20 profit and loss generating Cities and States
* Finding most sold items from Inventory and how different shipping methods impacts purchases
* Finding the impact of different categories on sales and profit of Superstore


#### CREDITS
The sales data for this exploratory analysis has been taken from the materials provided in the [youtube video](https://youtu.be/ThV2uLvWhN8). The exploratory analysis was done in my point of view using different approach.



