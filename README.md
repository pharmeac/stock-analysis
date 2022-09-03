### Overview of Project
The purpose of this analysis was to refactor an existing subroutine to be more efficient, so that in the future it could be utilized for a much larger data set.

### Process
We started with the existing code that required looping through the data tickers multiple times, and made updates. 

We introduced a tickerIndex to allow the process to only need to loop through the tickers one time to gather volume, starting price, and ending price of each ticker.

![image](https://user-images.githubusercontent.com/109913335/188252554-4b03bd8e-df89-46e3-bc6d-374f7aa84317.png)

To test if the refactored code made the process run faster we used a timer, and created variables for start time and end time. 

![image](https://user-images.githubusercontent.com/109913335/188252569-0d1ed09c-764f-4af4-8c3c-533517e9bfad.png)

We also created a message box to display the time it took the process to run.

![image](https://user-images.githubusercontent.com/109913335/188252580-9dc9c8f9-bcd9-4d3a-99ad-48eb9487d64d.png)


### Results
The refactored code increased the speed of the subroutine significantly. For 2017, the original code took 0.574 seconds to run, while the refactored process took 0.109 seconds. The original code for 2018 took 0.781 seconds, while the refactored code took 0.102 seconds.
Here are the refactored code screen shots.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/109913335/188252468-79cc49a1-bf45-4fb0-807d-e0cb0914dc24.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/109913335/188252481-bf78ce49-4787-472d-9ec2-a2f46cd29ebc.png)




### Summary
Refactoring code versus starting from scratch can save time when you are looking to improve a subroutine. However, it does require the new coder to decipher and understand the previous coder’s work. Since there are various ways to accomplish what you want, different analysts may code slightly different.

Refactoring this particular subroutine did save us time, however setting up the tickerIndex required us to make additional code updates. For me, I ran into multiple areas that either broke or had to be rethought. 
