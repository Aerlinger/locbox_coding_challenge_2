# LocBox coding challenge


## Problem 2: A AirBnB JSON interface

### Part 1: Designing a Ruby interface to the JSON API

*Approach:* The AirBnB API is an abstraction. We'd like to build a very
simple query interface around this API. 

*Input:* A name of a given city as a string.
*Output:* A relation/cursor of availability
  - Columns: 7 day outlook, each day is a column
  - Rows: Host ID

The interface will look something like the following:

Airbnb = Airbnb.new(

As a first step, we'll need to wrap the JSON interface. We'll not worry about persistence at this stage.

