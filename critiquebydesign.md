# Assignment: Critique by Design
### *Due 11/15*
[Link to portfolio main page](/README.md)

## Selecting a data visualization for critique and redesign

I chose to critique and re-design one of many figures found in a report focusing on suburban-metro regions:
### [Overlooked Suburbs: The Changing Metropolitan Geography of Poverty in the Western United States<sup>1</sup>](https://www.frbsf.org/community-development/publications/community-development-research-briefs/2022/january/overlooked-suburbs-changing-metropolitan-geography-of-poverty-western-us/)

This report uses many data visualizations to help answer the motivating research questions. The report compares similar characteristics across different geographic regions, using separate but similar visualizations for each region, as well as several summarizing visualizations. The authors use figures to illustrate changing demographics and trends across time and in different geographic types. I chose to look closer at this report because of my interest in how the suburban context is changing. Changes in characteristics such as racial demographics and poverty have implications for planning and public policy in these areas. Within the report, I decided to focus on the figures depicting changing racial demographics, because I was interested in improving how multiple comparisons can be emphasized within one figure.

I chose to critique and redesign one of the figures specific to the Los Angeles metro region, which illustrates changes in racial demographics between 1990 and 2014-2018. A similar figure comparing racial demographics between these time periods is given for each metro region, for example Boise, Las Vegas, and Phoenix. Therefore, these critiques and suggestions could also apply to the other figures found in the report for different regions. 

<img width="1241" alt="Screen Shot 2022-11-16 at 11 09 18 PM" src="https://user-images.githubusercontent.com/117120584/202353774-3bbaf65e-ff22-4952-b17b-239601834737.png">

<sub> [1] Mattiuzzi, Elizabeth, and Margaret Weir. 2022. “Overlooked Suburbs: The Changing Metropolitan Geography of Poverty in the Western United States.” Federal Reserve Bank of San Francisco Community Development Research Brief 2022-1. doi: 10.24148/cdrb2022-1)</sub>

## Critiquing the Data Visualization

While the data visualization above isn't bad, I thought that I would be able to improve upon it. One of the issues that stood out to me was the challenge presented to the user when trying to compare data from the same year across different geographic types. Another issue I noticed was how the change in one color block affects the height of other color blocks, which can distort the pereception of changes in area of the bar, given only a change in placement along the bar. 

## Sketching Possible Alternatives
To address these issues, I thought about other chart types that could potentially be used to visualize the data. I proceeded with sketches of three different charts:
1. Overlapping histograms
2. Tree-map type charts
3. A grid of line charts

Please note that the sketches below are intended to convey design choices, not accurate data representation. Because each of these data visualization sketches uses repeated charts, some of the repeated elements are not entirely filled in, or the data used is a duplicate of a different geographic area. This was done only in the sketching phase, where I was most interested in design choices. 

![Week 3-1](https://user-images.githubusercontent.com/117120584/202338332-aa1cc17c-22be-4f32-9b30-db1ba73cbdbb.jpg)
![Week 3-2](https://user-images.githubusercontent.com/117120584/202338731-6c830929-31bc-4fc0-a1b7-96a123e1f320.jpg)

**Option 1:**
For the first option, I chose to try overlapping histograms. This data visualization is made up of six elements in a grid. Each element depicts a specific geographic type, for example "Largest city." Each element contains six spaces for bars -- one for each demographic race represented. However, each space was given two overlapping bars that represent values at different points in time. The overlapping characteristic meant that any visible color on top is the year that race had the highest representation, and anywhere the colors are mixed indicates overlap. 

**Option 2:**
For the second option, I chose represent the population proportion visually within a square, in a type of tree map diagram. For the sketch, I drew six of the needed 12 squares for a complete grid. Each square was 10 x 10 units, so there were 100 spaces within each square. These spaces were filled in with color-coded area based on racial demographics of each geographic type for a specific point in time. I chose to represent the data this way to emphasize how different races made up parts of the whole population. I chose to use squares within a square so that visual comparisons could be made more easily than if the representative area was illustrated with circles or with a pie chart.

**Option 3:**
For the third option, I chose to illustrate the change over time of racial demographics using a line chart. When sketching, I considered the possibility of finding more data points for other points in time between the given 1990 and 2014-2018. I thought that this chart type would better illustrate the trends of demographics over time for different geographic types. It also presented the option to highlight the largest changes using color, while changing other lines to gray. While this isn't reflected in my sketch, it is something I considered. 

## Testing Alternatives with User Feedback

After creating the three sketches above, I proceeded with interviewing peers to gain feedback on the sketches. I showed all three sketches to each user and asked them the following questions:
*Seeing re-designs ONLY:*
1. Can you describe to me what this is telling you?
2. Is there anything you find surprising or confusing?
3. Who do you think is the intended audience for this?
*After seeing original:*
4. How does the original compare to the re-designs? 
5. Is there anything you would change or do differently?

### Feedback from User 1
*Option 1:*
They understood what it was showing and were curious to see data on the suburb geographic type, which was not detailed in my sketch. They also noted that the visualization seems useful for a government report that can inform policy for different demographics or understand an area's representation.

*Option 2:*
They understood the main idea. They also suggested that the data be represented with a landscape layout to fit into a report better. Another suggestion was to delineate the grid within each square, so a user can count up the proportion themselves.

*Option 3:*
The user knew what the visualization was communicating, but they also noted that it was slightly misleading and simplifying. It's possible that there were other up and down trends over time that are skipped over by only including data for two points in time with that large of a gap in between.

### Feedback from User 2 
"I think all of them get the job done."

*Option 1:*
#1 is a little confusing to me because it automatically shows the highest value, which changes for some demographics going up or down.

*Option 2:*
#2 is a little confusing because you need twice as many “elements” to show the data, and it also is harder to see small changes (such as 8 to 12), although larger changes (such as 20 to 30) are easy to see. 

*Option 3:*
#3 is good because it lays it out and is easier to see trends. But I’m an engineer so I like trend lines more than your average person probably!

Given the conflict between how Users 1 and 2 perceived Option 3, I had to weigh my own judgement of their feedback. I agree with User 1: I think the trend lines are overly simplistic. However, I do think I would prefer Option 3 if I had more data to work with. 

I decide to take Option 2 to the computer to iterate using software and the actual data set.

## My Final Solution
  
Based on the reactions and feedback from my surveyed users, as well as my own opinions, I decide to attempt to create Option 2, a tree-map, using software. This iteration did not make the trends in demographic changes more visually apparent than the original. In fact, having the high number of elements in the grid seemed to provide too much information and visual overwhelm. The same could be said for an alternative grid of bar charts I considered after moving away from the tree-map idea. After several more iterations of changing the rows, columns, and chart types in the software, I went back to trying a categorized bar chart like the original. To my surprise, I liked it! What was different about it was the orientation: the horiziontal bars made it easier to compare down across each geographic type within each point in time. I also enjoyed that, compared to some of my previous iterations, there were not too many elements in a grid. While there are still twelve bars, their orientation in two columns decreases the visual overwhelem as opposed to the visual stimulation of having a large, colorful grid. Ultimately, after a long process with many iterations, my chart closely resembles the original. While I do believe my revisions are useful, I recognize now that the original data visualization was better than I gave it credit for. The issue I had with the stacked bars adjusting placement rather than area of color still perists, and I am now more confident that there isn't a better way to display this information. 
<div class="flourish-embed flourish-chart" data-src="visualisation/11849793"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
