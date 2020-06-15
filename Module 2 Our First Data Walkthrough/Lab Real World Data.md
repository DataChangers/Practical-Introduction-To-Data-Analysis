# A Practical Introduction to Data Analysis for Absolute Beginners

## Module 2 - Lab 1: Real World Data

## Learning Objectives

* Look at the basic anatomy of a data set with several variables.
* Sort that data according to one particular variable in Excel.

## Data Set

[Car data set](Module%202%20Lab%20Real%20World%20Data%20-%20car%20data.xlsx)
You can download this data set and store it so you can use it later on for the exercises.

## What You’ll Need

To complete the lab, you will need the online version of Microsoft Excel.

## Overview

In this lab, we’ll take a closer look at the car data we looked at in the videos. We’ll also see how to sort the data based on a specific variable/criteria, such as gas mileage.

### Exercise 1: Car Data

1; Go to Excel Online, and open the corresponding data using the "Upload and Open..." option. You should see several different variable columns for a group of car models. Please be aware of your local settings regarding the decimal separator and the thousand sign. Some countries use "," as a decimal separator, others use ".".

Here’s a snapshot of the data:

![Cars data set](img/2020-06-15-14-03-15.png)

2; Identify the variables. In this case, there are 12 different vertical columns . Here’s what they each
represent:

model = name of car model
mpg = gas mileage, in miles per (US) gallon
cyl = number of cylinders
disp = displacement, in cubic inches
hp = gross horsepower
drat = rear axle ratio
wt = weight, in thousands of pounds (1000 lb)
qsec = 1/4 mile time
vs = engine (0 = V-shaped, 1 = straight)
am = transmission (0 = automatic, 1 = manual)
gear = number of forward gears
carb = number of carburetors

Those are your variables, since they vary from car to car.

3; Identify the observations. Since each horizontal row corresponds to a single entry from each of the variable columns, each row must represent an individual car model. For example, take a look at the first car on the list: the Knight X gets 21 miles per gallon, has 6 cylinders, 110 horsepower,
etc.

![First row](img/2020-06-15-14-03-47.png)

4; You can also answer simple questions about the data. For instance, how much does the Clydesdale Turbo weigh? To find out, track down “Clydesdale Turbo” in the model column, then
look over at column G, the weight column.

![Clydesdale Turbo](img/2020-06-15-14-04-22.png)

Remember, the weight variable (“wt”) is given in thousands of pounds, so multiply 5.25 by 1,000 to find the car’s weight.

5.25 × 1,000 = 5,250

The Clydesdale Turbo weighs in at 5,250 pounds.

5; What kind of horsepower does the Apocalypse 100 get? To find out, find that car model in the column on the far left, then look at column E to see the horsepower (“hp”).

![Apocalypse 100](img/2020-06-15-14-06-18.png)

Nice. That particular model gets 66 horsepower. Actually…that’s not so nice.
