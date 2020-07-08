# Investigating Fandango Movie Ratings
In this project we will analyze more recent movie ratings data whether there has been any change in Fandango's rating system after Walt Hickey's analysis (https://fivethirtyeight.com/features/fandango-movies-ratings/).

Hickey found that there's a significant discrepancy between the number of stars displayed to users and the actual rating, which he was able to find in the HTML of the page. He was able to find that:

* The actual rating was almost always rounded up to the nearest half-star. For instance, a 4.1 movie would be rounded off to 4.5 stars, not to 4 stars, as you may expect.

* In the case of 8% of the ratings analyzed, the rounding up was done to the nearest whole star. For instance, a 4.5 rating would be rounded off to 5 stars.

* For one movie rating, the rounding off was completely bizarre: from a rating of 4 in the HTML of the page to a displayed rating of 5 stars.

Walt Hickey made the data he analyzed publicly available on GitHub. We'll use the data he collected to analyze the characteristics of Fandango's rating system previous to his analysis. (https://github.com/fivethirtyeight/data/tree/master/fandango)

### Goal
We will analyze more recent movie ratings data to determine whether there has been any change in Fandango's rating system after Hickey's analysis.


### Acknowledgement
This is a guided project proposed by Dataquest Labs, as part of the training in the data analysis specialization path.
