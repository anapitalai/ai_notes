# Understanding Mean and Standard Deviation in Drone Data

When working with drone data (like altitude, temperature, speed, or images collected during a flight), two important concepts help us understand the data better: **mean** and **standard deviation**.

## Mean

- The **mean** is just the average of a set of numbers.
- For drone data, imagine your drone records its altitude every second during a flight. To find the mean altitude, you add up all the altitude readings and divide by the number of readings.
- **Example:**  
  If your drone recorded altitudes of 10m, 12m, 15m, and 13m, the mean altitude is (10 + 12 + 15 + 13) / 4 = 12.5 meters.

## Standard Deviation

- The **standard deviation** tells you how spread out the data is from the mean.
- If your drone’s altitude readings are all close to the mean, the standard deviation is low (the drone flew steadily).
- If the readings vary a lot (the drone went up and down a lot), the standard deviation is higher.
- **Example:**  
  If your drone’s altitude readings are 10m, 11m, 12m, and 13m, the standard deviation is small (the flight was steady).
  If the readings are 5m, 20m, 8m, and 18m, the standard deviation is large (the flight had lots of ups and downs).

## Why It Matters

- **Mean** helps you understand the typical value in your drone data (like average altitude).
- **Standard deviation** shows you how much the data varies, which helps identify if there were steady or unstable conditions during the flight.

These concepts can be applied to any kind of drone data, like temperature, speed, or signal strength, to understand both the average value and how much it changes during the flight.