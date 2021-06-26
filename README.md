## Module 9 Challenge - Surf and Ice-Cream shop 


### Overview of the Analysis

The objective of this analysis is to provide a potential investor in a surf and ice-cream shop with temperature trends for the months of June and December for the years 2010 to 2017 in Oahu, which is on the North Shores. 

The analysis will provide the investor with statistics for the dataset of temperatures for the months of June and December, so that he can determine the sustainability of the surf and ice-cream shop business.

The data used for the analysis is stored in a SQLite database. SQLAlchemy is used for the code written using Python to communicate with the database.

To obtain the statistics about the temperature trends and to present it to the investor, the following have been used:
- Python queries to extract the data from the database as well as filters to get the data specific to the months on June and December.
- The Matplotlib library has been used to visualize the data.

### Results of the Analysis

- After extracting and running a statistical analysis for the months of June for the years 2010 to 2017, the following was found:
  - The average temperature for the months of June for the eaight years is 74.94 degrees F
  - Minimum temperature reached is 64 degrees F
  - Maximum temperature reached is 85 degrees F
  
- The above along with some more statistical results are illustrated in the table below:

<p align="center">
<img src="https://user-images.githubusercontent.com/82583576/123497553-25f1a380-d5fc-11eb-8501-413c50e49ada.png">
</p>

The line plot below shows the temperatures for the months of June for the eight year period of 2010 to 2017.
 ![June_Temps](https://user-images.githubusercontent.com/82583576/123499095-4290da00-d602-11eb-92e8-12fcc1abb132.png)
    
        
 - After extracting and running a statistical analysis for the months of December for the years 2010 to 2016, the following was found:
   - The average temperature for the months of June for the eaight years is 71.04 degrees F
   - Minimum temperature reached is 56 degrees F
   - Maximum temperature reached is 83 degrees F
  
- The above along with some more statistical results are illustrated in the table below:     

<p align="center">
<img src="https://github.com/BLuckoo/surfs_up/blob/main/dec_temps_stats.PNG">
</p>

The line plot below illustrates the temperatures for the months of December for the seven year period of 2010 to 2016.
![Dec_Temps](https://user-images.githubusercontent.com/82583576/123499082-27be6580-d602-11eb-9e54-6b2401a83f83.png)

          

