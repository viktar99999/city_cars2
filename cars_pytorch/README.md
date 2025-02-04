# city_cars
In the neroset_model will be using lr.pth and lr_1pth. This models will be using correlation method.
Base:
System - Ubuntu20.04.06lts
System - Ubuntu22.04.05lts
System - Ubuntu24.04.01lts
Programming environment - Python3.8.10.2.13
Programming environment - Python3.9.5.3.1
Programming environment - Python3.10.12.3.1
Programming environment - Python3.11.0-rc2
Programming environment -Python3.12.3.1
Progrmming environment - Python3.13.0-1
Install:
Command for install Python:
sudo apt install python3.8
sudo apt install python3.9
sudo apt install python3.10
sudo apt install python3.11
sudo apt install python3.12
sudo apt install python3.13
Check version Python:
Python3 --version
Command for install pip:
sudo apt install python3-pip
Check version Python:
Python3 --version
Check version pip:
pip3 --version
Others.
Command for install pip dependencies:
pip3 install -r requirements.txt
Command for install pip libs:
pip3 install numpy
pip3 install pandas
pip3 install scikit-learn
pip3 install tqdm
pip3 install torch
Check install python-libs:
command python3.8
command python3.9
command python3.10
command python3.11
command python3.12
command python3.13
import numpy
import numpy as np
import pandas
import pandas as pd
import sklearn
import tqdm
import torch
Base:
https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset
License:
Data files © Original Authors
Database:
car.csv
car.zip # due to storage limitation of the github.com necessary of theorchive file.
40 values('listing_id', 'sp_name', 'trimId', 'listed_date', 'back_legroom', 'front_legroom', 'year', 'bed_length', 'body_type', 'daysonmarket', 'dealer_zip', 'engine_cylinders', 'engine_displacement', 'engine_type', 'franchise_make', 'fuel_tank_volume', 'fuel_type', 'width', ''height', 'length', 'major_options', 'model_name', 'maximum_seating', 'highway_fuel_economy', 'horsepower', 'sp_name', 'mileage', 'seller_rating', 'savings_amount', 'power', 'price', 'torque', 'transmission', 'transmission_display', 'wheel_system', 'wheel_system_display', 'wheelbase', 'city_fuel_economy', 'city', 'make_name')
600000 strings
target = city, make_name
Models:
lr.pth
lr_1.pth
File:
body_type.csv
city.csv
engine_cylinders.csv
engine_type.csv
franchise_make.csv
fuel_type.csv
major_options.csv
make_name.csv
maximum_seating.csv
model_name.csv
power.csv
sp_name.csv
torque.csv
transmission.csv
transmission_display.csv
wheel_system.csv
wheel_system_display.csv
