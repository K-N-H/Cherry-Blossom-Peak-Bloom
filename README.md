# Cherry Blossom Peak Bloom Date (PBD) Exploratry Data Analysis (EDA)

### **Description**
The cherry blossom peak bloom in Washington D.C. is a highly anticipated annual event, drawing over a million visitors each year to witness the display. These blossoms have come to symbolize the arrival of spring, with their timing largely shaped by environmental factors. The peak bloom date (PBD) refers to the day in which 70% of Yoshino cherry blossoms are in full bloom. The purpose of this notebook is to analyze the relationship between pre-bloom temperatures and the PBD of Yoshino cherry blossoms, the dominant variety at the Tidal Basin.

Utilizing over 100 years of PBD data from the National Park Service (NPS) and temperature records from the National Weather Service (NWS), this EDA aims to identify trends in the timing of peak bloom and examine how variations in temperature might influence the timing of this iconic event.

**Research Question:** How do pre-bloom temperatures influence the timing of the peak bloom date of Yoshino cherry blossoms in Washington D.C.?

The detailed findings and analysis are documented in the `PBD_EDA.ipynb` notebook.

### **Data Sources**
The data files used in this project were obtained from the following sources and are located in the Datasets folder:

* **`PBD.csv`**: Washington D.C. Yoshino peak bloom dates from the NPS
*     downloaded from [https://www.epa.gov/climate-indicators/cherry-blossoms] (Accessed March 23, 2025)
* **`DC_monthly_temp.csv`**: Monthly temperature data for the Washington D.C. area from the NWS from 1921-2025
*     downloaded from [https://www.weather.gov/wrh/Climate?wfo=lwx] (Accessed March 27, 2025)
* **`daily_temp.csv`**: Daily March and April temperature data for the Washington D.C. area from the NWS from 2000-2025
*     downloaded from [https://www.weather.gov/wrh/Climate?wfo=lwx] (Accessed April 1, 2025)

### **Dependencies**
The functionality of this project depends on the availability of the following Python packages. Please ensure they are installed in your environment:
- pandas
- numpy
- matplotlib
- statsmodels
- seaborn
- scipy
- scikit-learn
  
### License
This project is licensed under the CC0 1.0 Universal License - see the LICENSE.md file for details

