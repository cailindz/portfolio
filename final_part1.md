### Site Navigation
[Link to portfolio main page](/README.md)

# Final Project Part 1
### Cailin De Zeeuw
*Due 11/22*

## Summary
For my final project, I want to explore the UN Sustainable Development Goals (SDGs), zooming in from an international framework to local implementation. This project is targeted toward organizational leaders in the U.S. who operate at a local scale. 
**Main Message: The UN Sustainable Development Goals are a framework that can and should be employed across all sectors and levels to create wide-reaching, long-lasting change.**

My project will provide visualizations representing self-assessment across the SDGs. First, the international rankings of countries. Then, trends within the United States only. Zooming in further, I will illustrate the SDGs at the city level. Finally, I will zoom in once more to highlight SDGs on an organizational level. 

By beginning with the international framework and zooming in to a local level, I aim to connect the SDGs, which are ambitious and broad, with tangible actions and progress. Because I'm creating this project with organizational leaders in mind, I intend to highlight the processes that an organization might use to implement SDGs. 

Finally, I hope to reframe the SDGs for my audience, so that they are not only viewed as international goals set by the United Nations, but also as guidelines for how every organization, city, state, and country can strive for a better future that includes everyone. And a better future for every city will propel change toward a better world. 

## Outline & Initial Sketches

### Sustainable Development Goals: An International Framework
![E_SDG_logo_without_UN_emblem_horizontal_Transparent_WEB](https://user-images.githubusercontent.com/117120584/203669938-42a7eb59-c384-4e7c-a0ef-edde56b3c993.png)

I will begin my project by giving an overview of the UN Sustainable Development Goals as a framework adopted by many countries. I will include the official SDG graphics, which are available for use according to these official [guidelines](https://www.un.org/sustainabledevelopment/wp-content/uploads/2019/01/SDG_Guidelines_AUG_2019_Final.pdf). The overview will include highlights of some of the specific goals and the metrics used to assess progress toward those goals. All the SDGs are captured in this official graphic:
![E SDG Poster 2019_without UN emblem_WEB](https://user-images.githubusercontent.com/117120584/203670801-44842558-22b1-4ca9-8aa4-ebf6aa36d937.png)
***Consider: Is it okay to include graphics I did not design, if they are central to the story?***

To summarize the overview of the SDGs, I can include an infographic-type visual calling out specific numbers:
- 17 goals
- 169 targets
- by 2030
- number of countries actively reporting SDG progress

Next, I will illustrate the international nature of the SDG framework while highlighting the United States. Here, I will include a dataviz illustrating how a number of countries are ranked along each of the 17 SDGs:![Untitled (Draft)-1](https://user-images.githubusercontent.com/117120584/203673359-a70e02eb-8999-4070-aa38-0554c9a7d16e.jpg)

### U.S. Progress on Sustainable Development Goals
In this section, I will focus on how the U.S. specifically has made progress on the SDGs, and where there is room for improvement. I will start with a simple (and boring) line chart illustrating the slight progress on the cumulative SDG Index Score since 2000:
![Untitled (Draft)-1 2](https://user-images.githubusercontent.com/117120584/203674380-05db2d7e-5a29-42a3-9234-5dcf1c2d2db5.jpg)

Next, I might highlight a few key areas where the U.S. is noticeably behind. The [State of the Sustainable Development Goals in the United States](https://www.brookings.edu/wp-content/uploads/2022/03/2022_Brookings_State-of-SDGs-in-the-US.pdf)<sup>1</sup> is a report published by Brookings that gives some insight. Based on their classification system of which SDGs are "on track" versus "breakthrough needed" or even "moving backward" I can color-code the U.S. progress in a dataviz:
![Untitled (Draft)-2](https://user-images.githubusercontent.com/117120584/203676178-c896d78c-f7f4-459c-9beb-8dcd0c282981.jpg)

I might also add a dataviz to illustrate how many people are affected by the U.S. falling short of an SDG even by a little bit. One fact highlighted in the Brookings report is that 6.6 million people did not have access to safe sanitation in 2019, which is approximately equal to the population of the state of Indiana.<sup>2</sup> I could use this fact or a different shortcoming in the U.S. and a unit chart to display how individual people in the U.S. are affected.

### SDGs on the Local Level
This section will highlight how cities apply the SDG Framework. [Pittsburgh and the Sustainable Development Goals: A Voluntary Local Review of Progress](https://sdgs.un.org/sites/default/files/2020-12/Pittsburgh%20VLR%202020%20Final%20Draft.pdf) is a report on how the City of Pittsburgh perceives themselves aligning with the SDGs as of 2020.<sup>3</sup> The report provides a small amount of data that can be used in a bar chart:

  ![Untitled (Draft)-3](https://user-images.githubusercontent.com/117120584/203681086-582a0f0e-b6c3-4aeb-af1c-9134d8d6d519.jpg)

If extra detail is needed, I could also reference local SDG analysis from Los Angeles, California. The [LA Voluntary Local Review](https://sdg.lamayor.org/2021VLR) was a leader in local SDG reporting. Useful data can be found on their public website.

### SDGs on the Organizational Level
This section will be the most "zoomed in" I will go in terms of SDG action. The Carnegie Mellon University [2020 Voluntary Review of the Sustainable Development Goals](https://www.cmu.edu/leadership/the-provost/provost-priorities/sustainability-initiative/cmu-vur-2020.pdf) is a report detailing SDG alignment across CMU. I can use data visualizations to report out on how CMU is doing on meeting various SDGs, and also on how they conducted their evaluation. 

The evaluation process can be visualized using a flow chart. The following prototype captures a few of the steps, but will be further built out in a future iteration:
  ![Untitled (Draft)-4](https://user-images.githubusercontent.com/117120584/203684300-69e4a4b1-0f36-4937-9d23-681ef294569a.jpg)

The report breaks down all of CMU's activities into the categories Education, Research, and Practice. The SDG evaluation then indicates what percentage of each category is connected with each specific SDG. The analysis was subjective and not entirely comprehensive. So, to visualize this data as a snapshot, a series of stacked bar charts could be useful. To further understand the data, plotting each percentage in order or rank helps visualize which goals are most prioritized at CMU:
![Untitled (Draft)-5](https://user-images.githubusercontent.com/117120584/203689057-221f3f55-52b6-4c59-a8ec-b9692faeb1f6.jpg)
However, this chart will require some refining. Specifically, I need to fix the overlapping data points. Additionally, I will add two other bars to represent other CMU activities as they relate to SDGs. 
  
### Local Action Drives Global Impact
I will conclude my data story by emphasizing the connection between local action and international change. To achieve the international Sustainable Development Goals by 2030, every country will have to do its part. In the United States, that change will rely on implementation at the city and organizational level. 

## Data
The main data source for my project comes from the [Sustainable Development Report](https://dashboards.sdgindex.org/downloads), which provides data on many countries, SDG indicators and goals, over many years. This excel datasheet can be imported into the dataviz tool of my choice, and filtered to the data I'm interested in. I intend to prioritize data for the United States, and maybe 5-9 other countries for comparison. As noted in my outline, I intend to look at broad SDG indexes over years, as well as zoom in to view more specific indicators for recent years. I also intend to use the dataset to rank the U.S. against other countries in terms of SDG accomplishments. 

To supplement the dataset above, I have found several reports with relevant information to be included. As mentioned in my outline, I will reference data from:
  - the Brookings report [State of the Sustainable Development Goals in the United States](https://www.brookings.edu/wp-content/uploads/2022/03/2022_Brookings_State-of-SDGs-in-the-US.pdf)
  - the City of Pittsburgh report [Pittsburgh and the Sustainable Development Goals: A Voluntary Local Review of Progress](https://sdgs.un.org/sites/default/files/2020-12/Pittsburgh%20VLR%202020%20Final%20Draft.pdf) 
  - the [LA Voluntary Local Review](https://sdg.lamayor.org/2021VLR)
  - The Carnegie Mellon University report [2020 Voluntary Review of the Sustainable Development Goals](https://www.cmu.edu/leadership/the-provost/provost-priorities/sustainability-initiative/cmu-vur-2020.pdf)
  
## Methods
I plan to build out this story using the tool Shorthand. I intend to create two versions: one version will be simplified for the 1-minute presentation, and the long version will contain more details. To create the data visualizations, I plan to use Tableau. However, I might end up also using Flourish. I expect to use a variety of other online tools during the design process, for example [Adobe Color](https://color.adobe.com/create/color-wheel) or [ColorBrewer 2.0](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3).

I will also be referencing the book *Good Charts* by Scott Berinato.
  
### References
<sub> [1] Pipa, A.F., Rasmussen, K., & Pendrak, K. (n.d.). State of the Sustainable Development Goals in the United States. Brookings.</sub>
  
<sub> [2] Pipa, Rasmussen, & Pendrak. </sub>
  
<sub>[3] Pendrak, K. & Viljaste, T. (2020). Pittsburgh and the Sustainable Development Goals: A Voluntary Local Review of Progress. United Nations.</sub>  

