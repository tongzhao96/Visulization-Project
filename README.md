# Visulization-Project
Interactive Visualization of Co2
Data
                                                                                                    
Our dataset is a subset of data from Our World in Data, which is an organization dedicated to
centralizing data and research on global issues of poverty, disease, climate change, and hunger.
The dataset we are working with in particular is the CO2 and Greenhouse Gas Emissions
Country Profiles. This dataset contains 207 countries and a number of variables tracking yearover-year emissions. The JSON file we are using for our visualization is a subset of metrics
pulled from multiple datasets hosted on Our World in Data (GitHub repo). A few of the
variables included are total Co2, coal, and oil emissions. Each of these are broken down by the
individual country, share of global emissions, by gdp, per capita, and shared global cumulative.
These simple categories complicated by the country-specific variables make for a dataset that has
regional and temporal components that can complicate discussions on emissions.
For our visualizations, we wanted to pose the question of how eras of industrialization have
affected the output of emissions. The structure of the JSON file was complex and large. Isolating
one country proved difficult as JS doesn’t iterate over objects. Due to this, we decided to focus
on one country, Australia. Australia has faced an incredible amount of intense weather events,
recently including hurricanes and wildfires. Just this week they are experiencing major flooding.
As a colonized country in the southern hemisphere, we thought it would make an interesting case 
study for our overarching question. We chose the variables time, total Co2 emissions, Co2
emissions per capita, and shared global Co2 emissions for our two visualizations.
Design & Visualization Message
To allow our users to investigate the relationship between eras of industrialization and emissions,
we decided on two visualizations. Given the static nature, we wanted the ability to scroll to act as
context building. The first is a simple and clear relationship of time versus total emissions
output. The mark for this visualization is a line. The channels are aligned positions. We
chose a line for a few reasons. First, dots make the trend difficult to track. This isn’t a scatterplot,
so there is only one point that moves from left-to-right that is supposed to reveal some trend over
time. Second, there are a wealth of visualizations, for example in news journalism, that use line
charts to express similar data. Lastly, we needed to integrate a visual element to show a
distinction between industrial eras. We found that a line chart clearly showed the data trend,
while not overloading the user with our icons. From this chart, we hope the user sees that
emissions have been increasing rapidly and that different eras have different effects on this
increase. One trade-off that we have is the icon legend. Leaning on less user stimulation, we
decided to place the icon legend at the top and just use icons in our charts. This could make the
user come back to the legend for definitions, which isn’t ideal.
The second visualization builds on the first. The marks are the same. We add the channel of hue
to distinguish between different lines. We are hoping that the context and goal of the first will be
apparent and inform the reading of the second. Not only are eras of industrialization important,
but they are informed by greater global context. By breaking down the total Co2 emissions by
per capita and share of global emissions, the user will have added context as to what role this
country plays in the grand scheme of emissions issues. To accomplish this, we added lines for
per capita and global share, with the total Co2 as a line for reference.
Both charts use a logarithmic scale. Tonnes of emissions is a huge number. Emissions
themselves are hard to make tangible. Due to this, we chose to use a logarithmic scale as we felt its best represent
its trend.
