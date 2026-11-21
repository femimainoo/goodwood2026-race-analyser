# Project: How does the performance of a Greenpower car change during a race?

My team and I are going to use data from our performance at Goodwood race on 18/10/2026 to analyse how the performance of Empress (our car) changes during a race.

Main objectives:

▪ See what conclusions can be made about the performance of empress.

▪ Identify the source of what causes empress to slow down during race.

▪ Use the data to make the process of looking for solutions that allow empress to maintain speed for as long as possible during races easier.

**Graphs:**

<img width="990" height="800" alt="Graph - Race 1 Speed of Empress to Complete Each Lap" src="https://github.com/user-attachments/assets/21e84465-c7f5-4b49-9480-c0e2555f9d9a" />

<img width="972" height="766" alt="Graph - Race 1 Time taken for  Empress each Lap" src="https://github.com/user-attachments/assets/6b55ab34-d4f9-4281-9608-72e822650a80" />

<img width="998" height="790" alt="Graph - Race 2 Speed of Empress each Lap" src="https://github.com/user-attachments/assets/6604d4c2-1387-44e1-b466-646ec4975b1a" />

<img width="998" height="786" alt="Graph - Race 2 Time Taken for Empress to Complete Each Lap" src="https://github.com/user-attachments/assets/a5c16935-f631-43c8-84e2-2c626739131c" />

**Race 1:**

**Conclusions from Graph titled "Race 1: Time Taken for Empress to Complete Each Lap":**

The time taken for the car to complete each lap is quite steady around 340 seconds to 360 seconds (despite an anomaly on lap 5 of around 468 seconds, which is likely from a pit change) until lap 9 out of 11 where it jumps to around 509 seconds, drops slightly on lap 10 to 418 seconds, and then spikes to 824 seconds on lap 11. This final lap is well over double the initial time taken. 

Therefore, Empress' performance declined significantly toward the end of the race. The time taken was quite consistent in the first section (laps 1 to 8), but in the final three laps it became erratic and increased sharply as the batteries ran flat around the 45-minute mark.

**Conclusions from Graph titled "Race 1: Speed of Empress each Lap":**

The speed of the car is quite constant between 3.4 m/s and 3.6 m/s (despite a dip on lap 5 to around 2.6 m/s from a likely pit change) until lap 9 out of 11 where it drops to around 2.4 m/s, recovers slightly to 2.9 m/s on lap 10, and then falls to about 1.5 m/s on lap 11. This final speed is less than half the initial speed.

One area of note is the sharp drop-off in speed during the final three laps rather than a gradual decline across the whole race. Because the 40Amp batteries died at roughly 45 minutes instead of lasting the full 90-minute race, the car lost power rapidly at the end. Using an eChook (data logging tool to log current, voltage etc.) during races could help determine why the battery drained so quickly.

Empress' performance declined. The speed was quite consistent in the first section, but in the final laps it decreased sharply.

**Race 2:**

**Conclusions from Graph titled "Race 2: Time Taken for Empress to Complete Each Lap":**

The time taken for the car to complete each lap is quite steady around 340 seconds to 346 seconds until lap 5 out of 10, where it jumps to around 472 seconds and stays between 452 seconds and 488 seconds through lap 7. On lap 8, there is a massive anomaly where the lap time spikes to 1956 seconds (over 32 minutes), likely due to a red flag stoppage or an extended pit change. For laps 9 and 10, the time settles around 403 to 409 seconds, which is still noticeably higher than the initial time taken.

Therefore, Empress' performance declined and was heavily disrupted by a major stoppage on lap 8, splitting the consistent lap times into two different sections (laps 1 - 4 and laps 5 - 7/9 - 10).

**Conclusions from Graph titled "Race 2: Speed of Empress each Lap":**

The speed of the car is quite constant around 3.5 m/s until lap 5 out of 10 where it drops to between 2.5 m/s and 2.7 m/s for laps 5 to 7. On lap 8, the speed drops to an anomaly of around 0.6 m/s (corresponding to the 1956 second lap time). On laps 9 and 10, the speed recovers slightly to around 3.0 m/s, which is still lower compared to the initial speed.

Therefore, Empress' performance declined and was inconsistent compared to the start of the race, ending early at 10 laps before finishing the full race distance.

**Overall analysis:**

**Which race did Empress have a better performance in and why?**

Empress performed better in Race 1.

In Race 1, Empress completed 11 laps and placed 16th, maintaining a consistent speed of around 3.4 - 3.6 m/s for 7 of the first 8 laps. In Race 2, the speed dropped much earlier (by lap 5), suffered a massive 32-minute delay on lap 8, only completed 10 laps, and resulted in a disqualification.

Furthermore, because the average lap speed across the whole 90-minute window is skewed by the car stopping early at around 45 minutes with flat batteries, looking at the individual lap consistency shows Race 1 was much smoother. 

**What was the cause of reduction in speed in both races?**

Based on the team's post-race notes, the main cause of the reduction in speed and early retirement in both races was massive battery management issues, where the 40Amp batteries lasted only about 45 minutes instead of the full 90-minute race duration. The team suspects this rapid battery drain was caused by high current draw from rust in the motor or an issue with the electrics/porter box. 

Additionally, as noted in previous race reflections, the car's overall speed is also limited by its heavy chassis (from excess resin) and aerodynamics, which puts extra load on the motor and drains the batteries faster.

**Next steps:**

After consulting with the team, here are some next steps we would like to move forward with. 

- Strip and test the electrics: Remove the electrical components from Empress to test the motor and porter box, checking specifically for rust in the motor that may be causing excessive resistance and draining the 40Amp batteries in 45 minutes.
  
- Data logging: Fit or check the eChook data logger before the next season so we can monitor voltage and current draw in real time and catch battery drain before the car dies on track.

**Extra notes:**

- Confirm Race 2 anomalies: Check with the team members who attended Goodwood to confirm what caused the disqualification in Race 2 and the reason behind the 32-minute lap time spike on lap 8.
