# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 22-08-2025
### Name: Dheena Darshini Karthik Dheepan

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
```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
data=pd.read_csv("/content/spotify.csv")
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

<img width="1988" height="975" alt="Screenshot 2025-08-25 220452" src="https://github.com/user-attachments/assets/7d2360c2-b104-4a58-bb7c-cc731864122a" />





# RESULT:
Thus we have created the python code for plotting the time series of given data.
