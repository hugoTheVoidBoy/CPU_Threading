# CPU_Threading
 Log CPU performance

This Python file is to run in the background to log the CPU usage (%) during my activities on my laptop every 10 seconds.

This helps me practice performance load testing.

I used psutil library to get the CPU information and used pandas library to convert it to Excel data frame, then open the Excel file using openpyxl and log information. Also, threading library was used to run the program in the background. A one-million-loop calculation was done to calculate a relative CPU speed in comparison with the data from psutil.

Run this by cloning this repo, or following this bash:

```
Git clone https://github.com/hugoTheVoidBoy/CPU_Threading
Cd “<LOCATION_OF_THE_FILE>”
Python CPU_speed_during_ROS2_dev_test.py
```
