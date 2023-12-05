Here we explore migration between states in the United States. As people move from one state to another for a variety of reasons, this migration not only reflects individual choices but also reflects and influences the economic, social, and political fabric of each state. Understanding the patterns and drivers of interstate migration is crucial in deciphering the ever-evolving fabric of American society. Where are people leaving and going, why do people relocate, and what factors make a state desirable or not? Whether driven by economic opportunities, politics, or other factors, the movement of people within the U.S. is a compelling narrative that merits exploration.

Our migration data comes from the US Census, and we use a variety of other sources for election results, unemployment rates, region classification, and more. Links can be found at the bottom of this page. <b>Note that the Census data was missing for 2020, likely due to the pandemic, so to keep our temporal visualizations reasonable, we filled it in by averaging the population number for each state in 2019 and 2021 which most likely are not aligned with the trends at that time as 2020 was a special year.<b>

<h1 style="text-align: center;">Migration Overview</h1>

First, let’s look at what’s happening currently in the country--which states have a net influx of new residents and which have a net outflux? The map below shows each state’s net migration, normalized by its total population, in 2022.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/WhosGainingLosingPopulationRelative2022/WhosGainingLosingMap2022?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '850' height = '650' scrolling='yes' style="display: block; margin: auto;"></iframe>

We see strong growth in the Southeast and Southwest, and declines in the West Coast and Northeast. Major states like Texas, Florida, New York, and California get the most attention, not just because they have huge absolute numbers of in and out movement, but also the sharpest changes--New York has the highest relative net outflux, and Florida has the highest net influx absolutely and relatively.

Now lets look at a comprehensive overview of population shifts for all the states from 2018 to 2022. Through the control widgets, we can see both totals and percentage changes relative to the total population, as well as sort them by Influx, Outflux, and Alphabetically by state. A year slider is provided to look at different years.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/PopulationMigration_17017506894240/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '850' height = '650' scrolling='yes' style="display: block; margin: auto;"></iframe>

The first thing to note is the large outflux of people from California, especially in 2021. There is also a sizable influx into Florida during all years. Starting in 2021, there is a major shift for New York, as the number of people leaving jumps from 450k to nearly 600k. Sorting by influx, we can see that there is a pattern of people moving into southeastern states such as North Carolina, Georgia, and Virginia. 

Now, if we change it up and show the migration changes as a percentage of population, we can see that the influx and outflux percentage wise is higher in less populated states such as Wyoming, North Dakota, Alaska, and Delaware. Most states have around a 4-5% influx and outflux rate; however, Washington DC in all years notably has over double the percentage changes of most other states. The non-mainland states of Alaska and Hawaii are also note-worthy for having high Outflux rates.


<h1 style="text-align: center;">Where did people go</h1>

Now we know which states are gaining and losing people, but where are they coming from and going? In other words, which states have a strong relationship in terms of migration between them?

We have some chord diagrams below show for each state, the amount of new residents coming from every other state. 

![largediagram](/assets/imgs/chord_all.png)
This first chord diagram covers all states, and see large connections between New York and Florida, New York and California, California and Texas, New York and Texas, Virginia and Maryland, New York and Connecticut, and more.

Let's also highlight and go over the large states we have already noted like California, Florida, New York, and Texas. We can also look at the trends for a couple more states, mainly North Carolina and Georgia as we see that they are seeing a high influx of people.

<h3>California</h3>
![largediagram](/assets/imgs/chord_california.png)
Here, we see where new California residents are coming from. Major states include Texas, Florida, and New York, plus nearby Washington, Arizona, and Nevada.

<h3>Florida</h3>
![largediagram](/assets/imgs/chord_florida.png)
New Floridians are coming mainly from New York, some from California, and some from nearby Georgia.

<h3>New York</h3>
![largediagram](/assets/imgs/chord_newyork.png)
In New York, many people are coming from Florida and California, as well as nearby Connecticut, Pennsylvania, and New Jersey.

<h3>Texas</h3>
![largediagram](/assets/imgs/chord_texas.png)
Texas has huge migration from California, some from Florida and New York, and some from nearby states like Oklahoma.

<h3>North Carolina</h3>
![largediagram](/assets/imgs/chord_northcarolina.png)
North Carolina has a lot of people coming from other Southern states--Georgia, Florida, and Virginia--plus some from New York, and California.

<h3>Georgia</h3>
![largediagram](/assets/imgs/chord_georgia.png)
Finally, Georgia has a lot of new residents from Florida, and nearby Southern states like Tennessee, Alabama, and North Carolina. Some New Yorkers and Californians are also moving there.

Overall, we see that new residents for any given state come from a variety of other states. However, there are still some patterns. A lot of new residents come from nearby states, and a lot come from large states, especially heavy-outflux states like CA and NY, but even heavy-influx states like FL and TX. Major stand-out relationships include New York/Florida, and Texas/California. Notably, migration between these pairs is strong in both directions, even though in each pair one state is growing and the other is declining. For example, many people move from Florida to New York, even though the opposite is also true, and Florida has strong net influx and New York has strong net outflux.

We can also look at these changes geographically on a map and compare certain states. We have mainly picked out comparing California and Florida as well as New York and Texas.

<h2 style="text-align: center;">California vs. Florida</h2>

<iframe seamless frameborder="0" src="https://public.tableau.com/views/Project2_17017442470190/CABoard?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '900' height = '700' scrolling='yes' style="display: block; margin: auto;"></iframe>

California, historically known for its robust population growth, has been a beacon for those seeking opportunities in the tech industry, diverse job markets, and cultural richness. 

However, we can see that there is currently a decline now. From the map, we see that only 7 states saw more people moving to California than leaving it. For all the states that saw an influx of people from California, Texas emerged as the top destination for Californians, while for the states seeing an outflux to California, New Jersey notably saw the most people relocating to California than vice versa.

Meanwhile, Florida has become increasingly attractive for people to move to. We can see that there is a net influx of people to Florida from many states all over the US except for the ones mainly in the South Eastern region and Texas. For all the states with a net influx to Flordia, we can note that New York is the largest state where people move to Florida from.

In the case of both these states, Florida saw a lot more influx from all states than California, but for them both, the states where the outflux to other states resulted in a net loss were states closer to them geographically. 

<iframe seamless frameborder="0" src="https://public.tableau.com/views/Project2_17017442470190/FLBoard?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '900' height = '700' scrolling='yes' style="display: block; margin: auto;"></iframe>

<h2 style="text-align: center;">New York vs. Texas</h2>

New York State, often perceived as struggling to retain and attract residents due to high living and housing costs, along with tax considerations, showed a more positive trend in 2022. 

Migration data reveals that 14 states had a net movement of residents to New York, with the largest influx coming from California.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/Project2_17017442470190/NYBoard?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '900' height = '700' scrolling='yes' style="display: block; margin: auto;"></iframe>

Texas, known for its lower cost of living, low state-tax, and a business-friendly environment, continued to attract newcomers in 2022. Major cities like Austin and Dallas have become magnets for tech professionals and corporations. 

The state welcomed residents from 41 other states, with only 9 states having a net gain of Texans. California, once again, was the primary source state for new Texans.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/Project2_17017442470190/TXBoard?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '900' height = '700' scrolling='yes' style="display: block; margin: auto;"></iframe>

In conclusion, states traditionally considered population strongholds, like California and New York, experienced a net loss of residents to other states. Conversely, states such as Texas and Florida saw an influx of people from across the nation.


<h1 style="text-align: center;">Migration Correlated with other Factors</h1>
Now that we have looked at some migration patterns, we should ask a question about why. What could be causing these migration patterns as well as population changes? Below, we have taken a look at political party, regions, as well as unemployment to see if there are any relations with migrations and population change.

<h2 style="text-align: center;"> Political Party Influence</h2>

Perhaps political party is causing it, or at least correlating with it. This could be due to Republican/Democratic policies or common characteristics of Republican/Democratic-led states.

The below graph charts year-over-year population change for every state, colored by political party. The party in each year is determined by the most recent presidential election results, ignoring all else. For example, you can see how Georgia turned blue in 2020. 2020 Census data was also missing, so each state was given a population value interpolated between 2019 and 2021.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/OverTimeGrowthRatebyPoliticalParty/OverTimeGrowthbyParty?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '850' height = '650' scrolling='yes' style="display: block; margin: auto;"></iframe>

On the extremes, we see that most high-growth states have been red, and the most declining states have been blue. There are exceptions to this rule, clearly, such as Delaware’s high growth and Louisiana’s decline. Looking at the lines from 2021 to 2022, many red states had a spike in growth and many blue states had a sharp decline, explaining the current migration patterns we saw before. This is likely due to the COVID-19 pandemic. We can’t say exactly why this is the case--perhaps a desire to live in rural/suburban areas, looser lockdown restrictions, more remote work, lower cost of living, or other factors caused the growth in red states. 

However, this growth in red states in not a sudden or recent phenomenon. Looking at the trend lines, red states were growing more than blue states from 2011-2017, were similar for a few years, and are now growing much faster once again post-pandemic. And though Texas and Florida have gotten lots of attention recently due to their high growth and large total population, smaller (also red) states like Idaho have been growing fast and steadily for many years.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/LargeStates-OverTimeGrowthRatebyPoliticalParty/OverTimeGrowthbyParty?:language=en-US&:display_count=n&:origin=viz_share_link&:embed=yes&:showVizHome=no" width = '850' height = '650' scrolling='yes' style="display: block; margin: auto;"></iframe>

Looking at a select few large states, we see the gap between red and blue even more clearly. Large red states have been outgrowing large blue states since 2011. Interestingly though, two of them, Florida and Georgia, have flipped parties in this time window, from blue to red and red to blue, respectively (though both have Republican governors). It’s hard to attribute any change in growth numbers to these party changes--both have been consistently growing. After all, presidential election results are more a reflection of the state’s situation than any new policy that would suddenly change growth. On another interesting note, Georgia has seen neither a sharp increase nor decrease since COVID, like the other red and blue states on this graph--does being an in-between state politically lead to in-between growth in migration? It’s hard to say for sure. 

Despite the differences in the trends between red and blue states, the broad shape of their trend lines is similar in both graphs; the local minimums and maximums occur at similar times. This indicates periods of lower vs. higher growth that affect all states nationwide, regardless of party.

We can see the current situation in 2022 in more detail with this Sankey diagram:

![](/assets/imgs/2022MigrationByPartySankey.png)

Overall, blue states have higher movement in both directions, but red states clearly make up a larger proportion of influx, relative to their outflux (shown by the shift in the central pool of all people moving in 2022).

<h2 style="text-align: center;">Regions</h2>
Another idea we can look into is that the geographical region of a state has an effect on the movement of people. We have split the US into 5 regions and looked at the migration of people by focusing on those regions: North East, South East, South West, Mid West, and West. 


![](/assets/imgs/Chord_all_regions.png)

Looking at the chord diagram of the migration of the regions, we can see that the South East has the largest influx of people from all the other regions. But mainly, we can note that almost half of the migration into Southeastern states come from other Southeastern states. Furthermore, looking at all the influx values for other regions, all regions have a large amount of migration within states in their region except for the Southwest region. For states in that region, it seems like there is a large influx from states in the South East and the West. 

If we look at each individual region, we can see that different regions have different distribution of influx from the other regions. Let’s go through the different regions discounting the internal movement within the regions, as we have seen that is the main influx type movement we see for most regions. 

![](/assets/imgs/Selected_regions_chord.png)

Starting with the North East, we see that states in the region as a whole see a larger influx from states in the South East. And this larger influx is significantly larger than the other regions. Next, we can look at the South East, and unlike the North East, the influx from other regions are very similar in value with the exception of the South West being a smaller proportion. For the West, we see that the largest influx is from the South West and East with the least amount coming from the North East region. Now for the South West, we see that the largest influx is from the South East and the West. The Midwest sees its main influx from the South East and the West.

Overall, there is significant movement out of the South East, but also movement into the area. It seems like that region in general is seeing a lot of influx and outflux from other regions, but also internally within its own states. Interestingly, the people from other regions coming into the region are rather uniform as to what region they came from which is really different from other regions as other regions seem to have one or two main regions their influx comes from.

We can also see there is movement from the West to the South West and Midwest, the two regions that are closest to it. Overall, we can actually see this trend for most regions except for the South East. Most of the largest influxes for each region come from a neighboring region. The one exception is the large influx to the West from the South East and the overall uniform influx for the Southeastern region.

Next, we can also just look at the general year over year change for each region to see how things may have changed with time. The graphs below show the region trends, but also the trends for states within a selected region. To select a region, click on the line in the graph.

<iframe seamless frameborder="0" src="https://public.tableau.com/views/RegionalStatePopulationChanges/Regionandchanges?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link&:showVizHome=no&:embed=true" width = '1100' height = '850' scrolling='yes' style="display: block; margin: auto;"></iframe>

Looking at the year over year percent change of each region from 2011-2022 in the graph, we can quickly see that between 2020-2021, there were almost no changes from the way we calculated 2020 values. The most notable thing is highlighted in the year to year percent change values for the North Eastern region of the US. From the graph, it is easy to see that there was a large increase from 2019 to 2020. Then the COVID-19 lockdown happens. About a year after, we can see a drastic decrease in this region. 

Similarly, we can see this trend for midwestern and western states although to a lesser degree. When looking at the graph for midwestern states, surprisingly, there is a large peak in 2013, and upon further investigation for the percent changes for the states in the region, we can see that North Dakota had a large spike in growth that year. We can note that some regions have a general trend like in the North East and Midwest while other regions like the South East don’t really have a trend between the different states within it.

Now when looking at the states within a region, the graph on the bottom also encodes the color of the political party of the state. We can also note that some regions also correlate with political party. As we look at the states in the North Eastern region, we can see that they are all essentially blue states, so a large decrease in these states affect the overall trend for blue states. Similarly, we can see that in the Midwest, most of the states are red states with a decline in year to year change from 2021 to 2022. However, there are some regions where this is not the case. Looking at the South East, we can see that there is a mix of blue and red states in the region. Within the different political parties there is no trend like the previous two regions we looked at. From this we can also note that some regions are highly dominated by one political party while others have a mix. 

<h2 style="text-align: center;">Unemployment</h2>

Let’s also take a look at unemployment and see if that would affect the migration of people. We can look at the employment rate as well as the year over year percent change for some states. The states we have chosen to look at are the ones with the largest economies of each region with the addition of Georgia as that is the state Georgia Tech is located in. 

<iframe seamless frameborder="0" src="https://public.tableau.com/views/ConnectedScatterplotsYOYandunemployment/TopstatesforeachRegionGA?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link&:showVizHome=no&:embed=true" width = '1100' height = '1200' scrolling='yes' style="display: block; margin: auto;"></iframe>

At first glance, the first thing that points itself out is the general jump in unemployment for the year 2020. This was the year of the COVID lockdown. 

The next most notable thing is the range of YoY change for different states, mainly the southern ones compared to the other states. We can see that Georgia, Florida, and Texas have all their points clustered towards the right of their graph, showing their higher YoY change compared to the other states. This aligns with what we have seen earlier about regions as well as the states’ migration influx and outflux values as well. 

The first pattern that stands out is again within Florida, Georgia, and Texas. We can see that over time, the unemployment rate drops while the Year over year change oscillates back and forth with the exception of the peaking of unemployment during the year of COVID. For these three states, we can see a peak in year over year change in the years 2015, 2017, and 2022. As of 2022, we can see that the YoY change has been increasing. This aligns with the values we have seen previously when looking at states and regions. These three states from the Southern regions have very similar patterns in terms of unemployment and population change over time. We can also note that the graphs for Florida and Georgia, the Southeastern states, are more than similar with each other.

Next, we can see that California has a trend of decreasing unemployment overtime with the exception of the spike in 2020, but unlike the southern states, its YoY change generally drops over the years with sudden peaks in 2014 and 2017.

Now, looking at the northern states, Illinois and New York, we can see there is a huge jump in YoY change for 2020 and 2021. This is different from the other states that generally had a decrease in year over year change or just a small slight increase. Otherwise overall, unemployment is decreasing like the other states. We can also see that over the years, these states’ YoY change is fluctuating back and forth like the southern states with some peaks at 2017 and 2021, but like California, it is in decline as of 2022.

Surprisingly, when just looking at unemployment and year over year change there isn’t much of a correlation between the two as one would expect people to be moving away from states with high unemployment. We see that depending on the state, the values are scattered around differently for each state.

When looking at unemployment with year over year changes, we can see that the states with larger economies see a general decrease in unemployment over the years with the exception of 2020. We also see that in general the year over year change fluctuates with different peaks for states in different areas, but for all the selected states, there was a peak in year over year change in 2017.


<h1 style="text-align: center;"> Conclusion</h1>

Let’s do a quick recap on everything we looked at. When going through the migration data, we found that some of the larger states in terms of population had a large net outflux value, but in terms of population percent, they were not necessarily the states that saw the most outflux. We also saw that when people moved there was a large amount of movement from one state or region to nearby areas. 

In general, we see that republican states seem to be growing faster than democratic states, especially since COVID-19. We also saw this trend mainly in the North Eastern region that almost entirely consisted of democratic states which could correlate with the trend we see in the political parties. The North East was not the only region that saw a crash after COVID-19. We also saw this population crash in the midwest and west regions as well. Controversy, we saw a huge influx of people into the southeastern region of the US as well as just movement within the region. 

We can also see these trends when looking at unemployment, while, we found that unemployment itself didn’t seem to have a direct correlation with YoY change across the board, we found that for specific regions or states that were close, there was a general trend among them. When focusing on the states with the largest economies, we could see that over the years, there is a general decrease in unemployment except for the spike in 2020, the COVID-19 lockdown year.

In conclusion, we have found that overall there are a lot of different migration patterns for all the states, but there are some patterns that hold in relation to location, region, parties and unemployment.

<h2> Check out a state of your choosing</h2>
Take a look at all the data, and click on a state on the map that you would like to get more insight on!
<iframe seamless frameborder="0" src="https://public.tableau.com/views/ConnectedScatterplotsYOYandunemployment/Dashboard2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link&:showVizHome=no&:embed=true" width = '1100' height = '1200' scrolling='yes' style="display: block; margin: auto;"></iframe>

<h1 style="text-align: center;">The Data</h1>
[Census Migration Data](https://www.census.gov/data/tables/time-series/demo/geographic-mobility/state-to-state-migration.html)

[Region Classifications](https://education.nationalgeographic.org/resource/united-states-regions/)

[Political Party Classifications](https://www.270towin.com/historical-presidential-elections/)

[Unemployment Data](https://www.icip.iastate.edu/tables/employment/unemployment-states)
