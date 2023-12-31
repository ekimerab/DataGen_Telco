# DataGen_Telco
Data Generator for Telco project simulation
This is VBA code for using Excel spreadsheets to generate artificial datasets based on actual past projects and experiences in Telco Asset Tracking. Entire dataset is housed in an MS Access database where I use SQL procedures primarily for JOINS and other set creation processes. The Excel VBA phase is for most of the more complicated data manipulations, standardizations, and stochastic simulations. Most of the code here is for randomly selecting sets and quantity ranges (e.g., randomly select one of several markets, and then randomly select a randomly selected number (between x and n) of base stations to perform additional random manipulations). Procedures tend to involve multiple levels of random selection -- as in, randomly select a set to randomly select from, and then before selecting, randomly select a number to select, where that number is something between x and n. 
This repository also captures stages of development, since it is often the case that a version of script returns errors or does not produce what was intended. I'll try to take notes RE what happened (e.g., as found in debugging) or what was the script's unexpected behavior and why?.
