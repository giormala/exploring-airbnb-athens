# Exploring AirBnB in Athens

This project is an assignment that analyzes the impact of AirBnB on the city of Athens using data from [Inside AirBnB](http://insideairbnb.com). The goal is to explore various aspects of the listings, including neighborhood popularity, pricing, availability, and host statistics.

## Assignment Overview

In this Jupyter notebook, you will find the following analyses:

- Neighborhood listings in descending order
- Pricing statistics per neighborhood
- Availability trends over time
- Reviews and occupancy analysis
- Room type distribution
- Daily pricing insights
- Host listing statistics
- An interactive map of listings

Please ensure that the necessary data is downloaded from [Inside AirBnB](http://insideairbnb.com/get-the-data.html) before running the notebook.

## Submission Instructions

# Exploring AirBnB in Athens

A lot has been said and written about the effect of AirBnB in Athens. In
this assignment, you will use the data collected by [Inside
AirBnB](http://insideairbnb.com), so you can go ahead and download the
Athens data from <http://insideairbnb.com/get-the-data.html>.

Once you do that, spend some time familiarizing yourself with the data
and then go ahead and do the following tasks.
:::

## Neighbourhood Listings in Descending Order

Show the listings per neighbourghood, with the most popular
neighbourhoods first (that is, in decreasing neighbourhood popularity
order).
:::

## Neighbourhood Prices in Descending Order

Create a table with the prices per neighbourhood. The prices information
should contain:

-   median price per neighbourhood

-   mean price per neighbourhood

-   standard deviation per neighbourhood

-   number of listings per neighbourhood.

The contents of the table should be in descending median prices.
:::

## Availability per Day

Create a plot with the number of listings available per day, on the $y$
axis, and the date, on the $x$ axis.
:::

## Reviews, Occupacy per Listing, Average Income

Create a histogram showing the number of reviews per listing. The
histogram should bin the number of reviews, from the smallest amount of
reviews in a listing, to the maximum number of reviews in a listing
rounded up to the closest hundred.

Once you have done that, calculate the average occupacy per listing per
month. To calculate that, find the average reviews per month and assume
that half of the bookings result in reviews.

Then, assuming that each booking is for a three nights stay, calculate
the average income per month, using the average price charged throughout
all listings.
:::

## Listings per Room Type

Show the number of listings per room type, in absolute numbers, and also
in percentages (the percentage of listings for each particular room
type). Then, show the number of listings per neighrbourhood and room
type.
:::

## Prices per Day

Create a table with the average price per listing per day. Draw a graph
visualizing the table.
:::

## Listings per Host

Create a table with the number of listings per host, in descending
order. Create a graph that will show the distribution of listings per
host, as follows:

-   You will rank the host on a number of listings basis. So, the first
    host will be the one with the largest number of listings, the second
    host will be the one with the second largest number of listings,
    etc. If there is a number of hosts with the same listings, just add
    them in sequence. For instance, if there are 10 hosts with one
    listing each, add them in the ranking with any order between them.

-   On the $y$ axis you will have the number of listings.

That is, a point $(x, y)$ will mean that the $x$-th highest hosting host
has $y$ listings.

After you have drawn the plot, do another one, this time with the $x$
axis in *logarithmic* scale.
:::

## Visualize Listings

Draw an interactive map to show the listings ovelayed on Athens.

You can use the [folium](https://github.com/python-visualization/folium)
library to create your map; spend some time reading the documentation.

The map should show each listing and on clicking on top of it, the user
should see a short description of the listing.

Note that such a map is heavy on resources. You will probably *not* be
able to include it in a Jupyter notebook, so you should save it to an
external HTML file that can be opened by any browser. Also, to make
things easier, you make wish to limit the maximum zoom level from 12 to
15 (after you read folium\'s documentation you will know what this is).

Hint: be careful witht he description data, if they contain some
characters they may not be rendered in HTML and may destroy your output.
:::

## Submission Instructions

You must submit your assignment as a Jupyter notebook that will contain
the full code and documentation of how you solved the questions, plus
the HTML file containing the visualization of the last question. The
Jupyter notebook must be fully replicable: that is, somebody reading it
must be able to do exactly what you did and obtain the same results.

The documentation must be at the level where somebody that has some
Pandas and Python knowledge can understand exactly what you are doing
and why. Your output must be as user-friendly as possible. That means
that your output tables should not include zillions of columns that are
not needed for your analysis.
:::

## Honor Code

You understand that this is an individual assignment, and as such you
must carry it out alone. You may seek help on the Internet, by Googling
or searching in StackOverflow for general questions pertaining to the
use of Python and pandas libraries and idioms. However, it is not right
to ask direct questions that relate to the assignment and where people
will actually solve your problem by answering them. You may discuss with
your colleagues in order to better understand the questions, if they are
not clear enough, but you should not ask them to share their answers
with you, or to help you by giving specific advice.
:::
