# Are Movie Lengths in Decline?
This mini-project is attempting to determine whether or not movie lengths have decreased over time. I will initally make use of some basic aggregates in the form of lists for the years 2011-2020. I will then move on to the larger Netflix dataset, which has nearly 8000 rows of data.

### Aggregate Tasks:
1. Turn basic aggregates into lists and the combine then into a dictionary
2. Convert dictionary into a DataFrame
3. Produce a graph detailing the trend of aggregate data

### Netflix Tasks:
1. Load in the full dataset as a DataFrame
2. Filter the DataFrame to represent only Movies
3. Create a subset of the DataFrame to exclude extraneous columns
4. Because we're now working with individual movies and not aggregates, a line plot is no longer suitable. Create a scatter plot
5. Many short movies have been released in the last two decades, and many of these are under an hour long. Filter the DataFrame for movies with a duration under 60 minutes to see what is pulling down the average
6. We can see that many of the films under 60 minutes are genres such as 'Children', 'Stand-up', and 'Documentaries'; which makes sense as these types of films are typically shorter than 90 minutes. Iterate through the DataFrame and create a colors list to mark each of these genres with a different color.
7. Plot the scatter plot again with the appropriate coloring


### Aggregate Conclusion
The above line chart clearly indicates that are time has progressed, movie duration has decreased, at least according to the aggregated data. However, this data sample is small we need the rest of the data to draw a conclusion.

## Conclusion
As suspected, non-typical genres such as children's movies and documentaries are clustered toward the bottom of the graph. In general it looks like movie duration has not gone down over time, but with this level of analysis the end result is inconclusive.
