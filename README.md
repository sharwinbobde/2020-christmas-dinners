# 2020-christmas-dinners

The COVID19 crisis has posed many problems in 2020. One of these problems is some of my first year Master's mentees not being able to go back to their countries during the Holidays. As TU Delft students we have had to go though a lot in these 2 quarters. Lets find the optimal way to organise these dinners.

## Relevent COVID19 restrictions in the Netherlands during Christmas
1. Only upto 3 guests are allowed at a time.
2. Guests should be able to maintain 1.5m distance.

## Data Collected from mentees
1. Name
2. Preferrences for dates with rankings
3. If they can cook
4. For what course would they be willing to cook/bring food along.
5. dietary restrictions.
6. drinks preference

## Objectives
1. All mentees should be able to attend and not resampled on the same day (no clones available).
2. Should get their preferred date according to ranking.
3. Should be willing to cook/bring along for different courses

**Not considered**:

1. dietary restrictions, because there weren't a lot.
2. drinks preference, because it was easy to acomodate.
3. ability to cook, because many cooks were available.


## Approach
We will contruct and solve this Many Objective Optimization (MOO) problem using an evolutionary algorithm called *NSGA-II*.

We will use the [**pymoo**](https://pymoo.org/) library to make the evolutionary strategy simpler.


## Usage
1. make a virtual environment using `python -m venv ./christmas_dinner-venv`
2. select the environment using `source ./christmas_dinner-venv/bin/activate`
3. install the dependencies `pip install -r requirements.txt`
4. run thee notebook `./christmas-dinner.ipynb` using an IDE or jupyter server.