# Ceres Nutri - M
Ensure Healthy lives and promote well being for all ages

# Inspiration
Sustainable Development Goals #3
To ensure proper diet and food availability for all ages, including infants and expecting mothers.

![SDG_report_2023_infographics_Goal 3](https://github.com/benjji0/Ceres-diet/assets/117336957/5e821d04-015c-44a2-b895-a499dabf7fd3)

# Quick Prototype
See nutrional data and plans


![Screen Capture_select-area_20230812185224](https://github.com/benjji0/Ceres-diet/assets/117336957/665b9c4d-7284-4660-a559-ba5df357b1ff)

# Fruit bowl maker, nutri - m style


![Screen Capture_select-area_20230812185453](https://github.com/benjji0/Ceres-diet/assets/117336957/5bb81a99-f563-4899-aba4-4f535c1635de)

# Intel OneAPI Tools/Libraries used
- Intel scikit-learn-intelex
- Intel daal4py
- Intel OneAPI Devcloud JupyterLab

#

![image](https://github.com/benjji0/Ceres-diet/assets/117336957/9965b09d-6fef-4b8e-8663-2e029cd3fe88)

# 
- We first reset numpy version, by upgrading it this is beacause there is a an error while reading interlex
- Next we !pip install sklearn - interlex package which force resets and reverts numpy package and downloads remaining packages
- Then we import daal4py from OneDAL Library et voila we good to go
#
![image](https://github.com/benjji0/Ceres-diet/assets/117336957/bf706079-2972-46c4-b682-bb1aa83653d3)

![image](https://github.com/benjji0/Ceres-diet/assets/117336957/81190186-6ecf-4d8a-aa68-7ed168e9fa16)

We can make use of intel's sklearnex for optimised performance for heavy computing tasks like clustering and linear regression
It works wel with regular sklearn packages that are not available in sklearnex like standardscaler
