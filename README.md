# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
data['Date']=pd.to_datetime(data['Date'])
# Convert Date to datetime

data['Date'] = pd.to_datetime(data['Date'])


# Plot Despacito streams over time

plt.figure(figsize=(10,5))
plt.plot(data['Date'], data['Despacito'], label='Despacito', color='blue')

plt.title('Spotify Daily Streams of Despacito')
plt.xlabel('Date')
plt.ylabel('Streams')   # <-- Corrected y-axis label
plt.grid(True)
plt.legend()
plt.tight_layout()
plt.show()
```

# OUTPUT:
<img width="1988" height="975" alt="Screenshot 2025-08-25 220452" src="https://github.com/user-attachments/assets/2ca3172f-7c5b-4b2d-938e-0e4ecbbd31fa" />








# RESULT:
Thus we have created the python code for plotting the time series of given data.
