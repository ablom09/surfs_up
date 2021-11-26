**OVERVIEW:**

Our friend, W. Avy is considering opening a surf shop in the near future. Before making this decision, however, they have asked us to compile temperature data for the months of June and December in the town of Oahu. Using a combination of Python, Pandas, and SQLAlchemy, we compiled our data into a readable data frame before passing them off along with our analysis. As part of our process, we also created some baseline summary statistics using the df.describe() function in order to help with W. Avy’s analysis.

![image](https://user-images.githubusercontent.com/91284661/143625476-b3301295-1098-40bb-8910-a8811bbdf777.png)

**RESULTS:**

After compiling our information into a data frame, we ended up with these results for the temperature data of June and December respectively:

![image](https://user-images.githubusercontent.com/91284661/143625496-ad529d72-58f8-4dce-8aa8-d542fd472f9e.png)

**June**

![image](https://user-images.githubusercontent.com/91284661/143625506-85feea52-8310-4efd-9a03-c8a0621f2b63.png)
 
**December**

After looking over our results from both months, several points of interest stand out:
•	The first thing to spot is the relative count and standard deviation within our data. Despite having 183 more counts total for the month of June, June also has a lowered standard deviation compared to December (3.26 compared with 3.75). This indicates that the month of December has higher variance in its temperature.
•	The second thing that jumps out is the general array of temperatures between both months. To be more precise, June seems to have higher temperatures for when reviewing the data. It’s minimum 64.00 is 8.00 degrees higher than December’s minimum and its’ maximum temperature of 85 is exactly 2.00 degrees higher than December’s.
•	The final thing that sticks upon inspection would be the relative skew of our data. The both months skew right, or in other words, bias towards higher temperatures the month of June would appear to have less degree of this bias. This can be found by observing the relative differences of both months’ mean and median temperature values, the median being synonymous with the 50% indicator in the data.

**SUMMARY:**

To close our analysis, and after compiling this information, a large-scale trend begins to show itself: June experiences higher temperatures compared to December, consistently. Not only does the data captured often show values compared to the December, but the lower standard deviation and higher volume of data captured give us greater statistical insight into the consistency and validity of this claim.

Though this temperature data would certainly be relevant for our friend, W. Avy and their interest in opening a surf shop in Oahu, our information might not be enough to give a solid recommendation on whether this occurs or not. Two points in particular I would recommend for further analysis would be:

1)	Widening the scope of our analysis. Temperature may be a good indicator for the likeliness of individuals willing to surf, but other weather factors that also impact this decision have been left out of our analysis altogether. In particular, I would run several other queries on factors such as rain, storms, wind patterns, etc.
2)	Oahu likely holds several beach areas that would be suitable for a surf shop to succeed economically. Still, some locations may be better suited than others, and a larger query regarding population density involving visual mappings are certainly worth considering taking into consideration. A surf shop may be a good idea to invest in, but if it is far removed from potential traffic it won’t necessarily matter how good the weather is if no one is likely to run into it.
