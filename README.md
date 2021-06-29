# Characterizing-and-Classifying-IoT-Traffic-in-Smart-Cities-and-Campuses
To classify IoT and non-IoT Devices by characterizing and profiling network traffic traces.

Contents of the folder:

1.Source Code - Execute the .ipynb file in Jupyter Notebook - Please execute all cells in sequence - The code is commented for understanding

2.IoT_pcap folder - Input folder - keep all the input pcap files in this folder

3.Database - Group24_NS_Project.db - vew in DB Browser tool

4.List_Of_Devices.txt - text file containing all devices and their respective MAC addresses

5.Presentation PPT

Dependencies:
Jupyter Notebook IDE - To execute code

Scapy - To parse the .pcap files and extract the necessary data/features into the SQLite tables.

SQLite - To store data in sqlite database.

Pandas -  To clean and preprocess data.

Numpy - To work with arrays.

Matplotlib - To plot graphs, histograms to represent the results visually.

Scource Code Files:

1. PcapToDB.ipynb - Run this first on pcap files to save data into database
2. 
3. ExtractFeatures.ipynb - Run this file after PcapToDB.ipynb. Extract the features of the dataset and compare the graphs of IoT(Light Bulb) and non-IoT device(Macbook - other devices were not active on that day)
				As mentioned in paper, the data of Light bulb of 28th September 2016 was used.
				
3. Graph.ipynb - Plot graphs of ports and frequencies

Download pcap data from opensource - https://iotanalytics.unsw.edu.au/iottraces
