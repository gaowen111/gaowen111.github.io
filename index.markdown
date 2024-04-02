---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---

# Introduction

In the city of San Francisco, a story of resilience and strategy unfolds against the backdrop of urban crime. This tale, rooted in data and analysis, begins with a deep dive into the city's top 10 crime categories, illuminating the complex landscape of safety and security. The aim is to help the police to understand how they can reduce the crimes better by understanding for example when to add patrols and the crime trend throughout years, hence shaping the narrative of urban safety.

We chosed to only use top 10 crime categories as we think it should be the first focus, once the top 10 crime amount has been reduced and issue been solved, we can focus more on the rest of the smaller categories. From the visualization perspective, human brains' focus on the dashboard is limited, and we would like to avoid people loosing the attention to the most important part. Also it will be hard and tired for human to read, if it is more than 10 colors on the visualizations to indicate different categories.

By tackling these prevalent crimes, the city paves the way for a broader, more comprehensive approach to urban safety, setting the stage for a story of transformation.
<br>
<br>

# Visualization

## Echoes of Seasons: Unveiling the Pulse of Urban Crimes


Visualization plays a crucial role in this story, tailored to human cognitive limits to emphasize crucial data. The line chart not only makes the data accessible but also highlights the pivotal issues at the center of San Francisco's battle against crime. Here we would like to show and find out if there is a peak or low season for the crimes among the years.

![Crime Counts by Month for All Top 10 Crime Categories](./img/timeseries.png)

As the plot unfolds, we are introduced to "Echoes of Seasons", a chart that reveals the rhythmic patterns of urban delinquency. The fluctuations of crime rates, particularly the spike in thefts during summer and winter, hint at the interconnectedness of societal elements and crime. This seasonal rhythm serves as a reminder of the city's need to adapt its strategies in response to changing patterns.  Concurrently, the erratic fluctuations of drug/narcotics offenses and warrant cases mirror the intricate challenges law enforcement faces. A mid-year surge in burglaries serves as a reminder that preventative measures should evolve in step with seasonal shifts. Far from being mere statistics, these visual data narratives serve as a clarion call for the city's protectors to dynamically fine-tune their strategies.
<br>
<br>

## Number of crimes by District

Another pivotal figure in our narrative is the dynamic map visualization, a tool that artfully captures the shifting landscapes of crime distribution over time. Like frames from a film, these animations guide observers through the evolving storyline of crime hotspots and trends, unveiling the unique challenges that the Northeast faces in stark contrast to other regions.

![Map Image](./img/mapgif.gif)


This visualization, with its ability to chronicle changes in crime patterns through the lens of animated yearly frames, empowers observers to trace the ebb and flow of criminal activity with unparalleled clarity. Remarkably, the story told through these frames maintains a consistent thread across the years, with 2018 standing out as an aberration. This deviation is underscored by the absence of a full year's data for 2018, leaving us in suspense as to whether this represents a true drop in crime rates or merely a gap in our collective narrative.
<br>
<br>


## Crime frequency by Category and Day of Week
The story deepens with an analysis of crime frequency by category and day of the week, offering insights into the frequency of different types of crimes on each day of the week for the police. It reveals if certain crimes are more common on specific days. The filter by year shows the analysis of trends over time and shows if certain crimes are becoming more or less frequent. So that the police will know how to plan the schedule of the patrols better to reduce certain crimes.
<br>
_You can click and play with the filter of Year to see the difference._


{% include periodic.html %}

By choosing among the years filter we can see, that in general, only the category of Larceny/Theft has cases which the crime count for 1 day of week has exceeded 4,000, the rest categories are generally on a level of below 3,000. For different categories of the crime, the peak day of week can also vary. For example, the Larceny/Theft happened more on Friday and Saturday, while Assault tend to have similar amount among each day of week. We can also see after 2010, the amount of Larceny/Theft crimes have been increasing and has been very serious in 2017 (as 2018 doesn't have a full year's data so we cannot tell if there is a drop in 2018), which indicates that the police shall take focus on Larceny/Theft crimes, especially adding more patrols during Fridays and Saturdays.

Furthermore, when we look at this [news](https://www.sanfranciscopolice.org/news/sfpd-releases-2017-year-end-crime-statistics-18-032)<sup id="fnref1"><a href="#fn1">[1]</a></sup> it actually mentioned that the police highlighted that their first priority is always on reducing the violent crime, and they indeed did a great job on the violent crimes as we can see that they are not even within the top10 categories, and also hence has less focus on the theft. But they also has noticed the big increase of theft, so that they also took actions on the theft crimes in 2017. This balance of focus reflects a nuanced understanding of urban safety, where the reduction of violent crimes does not overshadow the need to combat prevalent non-violent crimes.
<br>
<br>


# Conclusion
The conclusion of our story is not an end but a reflection on the journey of understanding and combating urban crime in San Francisco. The strategic focus on major crime types has not only showcased areas in need of immediate action but also highlighted the effectiveness of police enforcement. The narrative reaffirms the necessity of a dynamic approach to urban safety, one that is adaptable and responsive to the ever-changing landscape of urban crime.

We can also see that due to the focus of police has been the violent crimes especially with guns, the rest categories of crimes have been increasing, and our page has concluded a few patterns for the police to refer to, so that the police can efficiently plan strategically both short-term and long-term. However due to the limitation of the length, there are actually a lot more perspectives can be valuable as well.

<!-- Later in the document, or at the bottom: -->
<br>
<br>

---
**Reference**
<ol>
  <li id="fn1">
    SFPD Releases 2017 Year-End Crime Statistics: <a href="https://www.sanfranciscopolice.org/news/sfpd-releases-2017-year-end-crime-statistics-18-032" target="_blank" rel="noopener noreferrer">https://www.sanfranciscopolice.org/news/sfpd-releases-2017-year-end-crime-statistics-18-032</a> <a href="#fnref1" title="Return to article">↩</a>
  </li>
</ol>

<br>
<br>

---
**Contributions**
<table align="left">
  <tr>
    <th style="text-align:left;">Assignment Part</th>
    <th style="text-align:left;">Develop</th>
    <th style="text-align:left;">Review</th>
  </tr>
  <tr>
    <td style="text-align:left;">Webpage framework</td>
    <td style="text-align:left;">Wen Gao, Yuming Zhang</td>
    <td style="text-align:left;">Zheng Dong</td>
  </tr>
  <tr>
    <td style="text-align:left;">Visualization time series/bar chart</td>
    <td style="text-align:left;">Yuming Zhang</td>
    <td style="text-align:left;">Zheng Dong, Wen Gao</td>
  </tr>
  <tr>
    <td style="text-align:left;">Visualization Map</td>
    <td style="text-align:left;">Zheng Dong</td>
    <td style="text-align:left;">Wen Gao, Yuming Zhang</td>
  </tr>
  <tr>
    <td style="text-align:left;">Visualization Interactive</td>
    <td style="text-align:left;">Wen Gao</td>
    <td style="text-align:left;">Yuming Zhang, Zheng Dong</td>
  </tr>
</table>

<table align="left">
  <tr>
    <th style="text-align:left;">Student Name</th>
    <th style="text-align:left;">Student Number</th>
  </tr>
  <tr>
    <td style="text-align:left;">Wen Gao</td>
    <td style="text-align:left;">s233366</td>
  </tr>
  <tr>
    <td style="text-align:left;">Yuming Zhang</td>
    <td style="text-align:left;">s232252</td>
  </tr>
  <tr>
    <td style="text-align:left;">Zheng Dong</td>
    <td style="text-align:left;">s232281</td>
  </tr>
</table>
