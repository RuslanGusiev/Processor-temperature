Processor temperature

We have a temperature sensor in the processor of our company's server. We want to analyze the data provided to determinate whether we should change the cooling system for a better one. It is expensive and as a data analyst we cannot make decisions without a basis.

We provide the temperatures measured throughout the 24 hours of a day in a list-type data structure composed of 24 integers:

temperatures_C = [33,66,65,0,59,60,62,64,70,76,80,69,80,83,68,79,61,53,50,49,53,48,45,39]

Problem

If the sensor detects more than 4 hours with temperatures greater than or equal to 70ºC or any temperature above 80ºC or the average exceeds 65ºC throughout the day, we must give the order to change the cooling system to avoid damaging the processor.

We will guide you step by step so you can make the decision by calculating some intermediate steps:

Minimum temperature
Maximum temperature
Temperatures equal to or greater than 70ºC
Average temperatures throughout the day.
If there was a sensor failure at 03:00 and we did not capture the data, how would you estimate the value that we lack? Correct that value in the list of temperatures.
Bonus: Our maintenance staff is from the United States and does not understand the international metric system. Pass temperatures to Degrees Fahrenheit.
Formula: F = 1.8 * C + 32

Take the decision

Remember that if the sensor detects more than 4 hours with temperatures greater than or equal to 70ºC or any temperature higher than 80ºC or the average was higher than 65ºC throughout the day, we must give the order to change the cooling system to avoid the danger of damaging the equipment:

more than 4 hours with temperatures greater than or equal to 70ºC
some temperature higher than 80ºC
average was higher than 65ºC throughout the day If any of these three is met, the cooling system must be changed.

Future improvements

We want the hours (not the temperatures) whose temperature exceeds 70ºC
Condition that those hours are more than 4 consecutive and consecutive, not simply the sum of the whole set. Is this condition met?
Average of each of the lists (ºC and ºF). How they relate?
Standard deviation of each of the lists. How they relate?
