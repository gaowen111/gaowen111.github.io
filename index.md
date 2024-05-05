---
layout: default
---

Written by *Wen Gao, Yuming Zhang, Zheng Dong* on *2024-05-07*.

# Consistently High Traffic Crash Numbers in San Francisco: Unveiling Patterns and Solutions

> San Francisco's government data underscores a persistent trend of high traffic crash counts, averaging at 3000 crashes annually. While a notable decline in 2020 was attributed to the Covid-19 situation<sup id="fnref1"><a href="#fn1">[1]</a></sup>, subsequent years witnessed a gradual resurgence, bringing the numbers back to their typical levels. This overview sets the stage for a comprehensive exploration of the reasons and patterns underlying traffic crashes in San Francisco from 2005 to 2023, with the aim of identifying potential strategies to address this ongoing challenge.

## Timelines and Journeys: A Chronicle of San Francisco Traffic Accidents
#### Public Holidays vs. Workdays: Uncovering the Peaks

> In bustling San Francisco, public holidays typically mean relaxation and celebration, but what impact do they have on traffic safety? The left chart shows a higher incidence of traffic accidents during holidays compared to sampled workdays, with July 4th and November 23rd having notably high numbers. This difference between holidays and workdays might be due to increased travel, alcohol consumption, and distractions during celebrations.

#### Daily Rush Hours: The High-Risk Windows

> After comparing holidays and workdays, we notice that public holidays have a higher accident rate, but how do accidents distribute over a day and across the week? The heatmap reveals distinct patterns, showing that weekdays, especially Thursday and Tuesday, see a surge in crashes during morning and evening rush hours. This pattern aligns with typical commute times, highlighting the elevated risks of rush hours.

#### Interactive Visualization: Exploring Yearly Patterns

> By selecting different years, the interactive heatmap allows viewers to explore how traffic accident patterns have shifted annually based on accident type and day of the week. Rear-end collisions and broadside accidents dominate weekdays, particularly Thursday and Friday. On weekends, accidents involving pedestrians and cyclists increase, showing their greater vulnerability. Midweek patterns reveal fewer incidents on Monday and Tuesday compared to the late-week surge.
<br>

## Navigating the Bustling and Hazardous Southern District
> A distribution map reveals the stark reality of the "most dangerous" districts in San Francisco for driving, biking, or walking. Notably, the highest traffic crash incidents are concentrated in the **"Southern"**, **"Northern"** and **"Mission"** districts during the year from 2005 to 2023. In contrast, **"Park"** and **"Tenderloin"** experience the least traffic crashes, with "Park" demonstrating a similar geographic size to the top-affected districts.

{% include district_map_traffic_crash.html %}

> But why? Why does the "Southern" district, despite being similar in size to "Park" experience a significantly higher frequency of traffic crashes? We investigated further and did a more detailed analysis based on the OpenStreetMap, and found some intriguing insights.


<iframe src="{{ site.baseurl }}/assets/detailed_map_traffic_crash.html" style="width:900px; height:500px;"></iframe>

> As you manipulate the map, zooming in and out, an intriguing pattern emerges: the north-eastern part of San Francisco features an abundance of **yellow roads**, indicating secondary primary roads linking towns<sup id="fnref2"><a href="#fn2">[2]</a></sup>, whereas the remaining areas are characterized by fewer yellow roads and a preponderance of **white roads** (tertiary roads linking smaller towns and villages.<sup id="fnref2"><a href="#fn2">[2]</a></sup>). The prevalence of yellow roads signifies a higher volume of vehicles, generally traveling at increased speeds, consequently elevating the risk of traffic crashes. This pattern is notably exemplified by the "Southern" district. Conversely, areas with fewer cars and more tranquil surroundings, such as the "Park" district, experience fewer traffic crashes. Concluding that, we would like to recommend the drivers conciously pay more attention while driving fast, and while there are many cars.

> Our research findings are substantiated by additional online sources<sup id="fnref3"><a href="#fn3">[3]</a></sup><sup id="fnref4"><a href="#fn4">[4]</a></sup>, which highlight specific intersections known for their heightened risk of traffic crashes. Notably, the top three intersections identified as **"5th and Market**", **"Market and Octavia"** and **"6th and Market"** are all situated within the SOUTHERN district, further reinforcing our data-driven observations. These reports advocate for governmental intervention, proposing a comprehensive investigation and potential redevelopment of these high-risk intersections to proactively mitigate future traffic crashes.

> We strongly advise that drivers maintain a heightened sense of vigilance, especially when driving at higher speeds and in areas with a significant volume of traffic, with the aim of reducing traffic crashes. Furthermore, if the govenment could allocate additional resources towards the investigation and reconstruction of the top three traffic-crash intersections, it would significantly contribute to further enhancing safety measures.

## Analyzing Traffic Collision Patterns and Severity in San Francisco: Insights into Participant Interactions and Accident Causes
> By analyzing the relationships between different participant types in traffic accidents in San Francisco, we have discovered the main interaction patterns. **Pedestrians**, **drivers**, and **cyclists** are the most common participant types. Pedestrians have the highest frequency of interactions with other types, which indicates that pedestrians are the most vulnerable to threats from the streets.
<br>


{% include Accident_Network_Graph.html %}

> Between 2005 and 2023, We've noticed some major patterns and causes of accidents. **Broadside**, **rear end**, and **vehicle-pedestrian** collisions are the most common types, leading to many injuries and fatalities. This means it's crucial for us as drivers to stay alert to vehicles approaching from the side and rear and to yield to pedestrians promptly.

> Furthermore, We've also observed that pain accounts for most of the severity in many accident types. However, due to the fragility of the human body, the number and proportion of severe injuries and fatalities in vehicle-pedestrian collisions are visibly higher than in other types. In 2021, out of 45 victims in 44 accidents in San Francisco, 40% were pedestrians <sup id="fnref5"><a href="#fn5">[5]</a></sup>. We believe this might be related to the legalization of jaywalking in California in 2018 <sup id="fnref6"><a href="#fn6">[6]</a></sup>. The unpredictability and chaos of jaywalking and random crossings could be positively correlated with the incidence of accidents and the increased likelihood of injury to pedestrians.

> Acknowledging the prevalence of broadside collisions, we strongly advocate for the integration of robust safety features in modern vehicles, including side-impact airbags, reinforced side structures, and side-curtain airbags and so on. Furthermore, advancements in traffic management, such as the implementation of roundabouts and other intersection designs, are essential in diminishing the probability of these specific types of crashes.
<br>

{% include Collision_Type_and_Severity_Analysis.html %}
<br>










---
**Reference**
<ol>
  <li id="fn1">
    Bay Area Highway Deaths Drop In 2020, Reflecting Decline In Traffic During Pandemic <a href="https://www.cbsnews.com/sanfrancisco/news/bay-area-highway-deaths-drop-in-2020-reflecting-decline-in-traffic-during-pandemic/" target="_blank" rel="noopener noreferrer">https://www.cbsnews.com/sanfrancisco/news/bay-area-highway-deaths-drop-in-2020-reflecting-decline-in-traffic-during-pandemic/</a> <a href="#fnref1" title="Return to article">↩</a>
  </li>
  <li id="fn2">
    OpenStreetMap Wiki <a href="https://wiki.openstreetmap.org/wiki/Key:highway#Roads" target="_blank" rel="noopener noreferrer">https://wiki.openstreetmap.org/wiki/Key:highway#Roads</a> <a href="#fnref2" title="Return to article">↩</a>
  </li>
  <li id="fn3">
    CAR ACCIDENTS IN SAN FRANCISCO COUNTY: STATISTICS, INTERSECTION DATA, AND MORE <a href="https://www.rmdlaw.com/personal-injury-blog/car-accidents-in-san-francisco-statistics-intersection-data-and-more/" target="_blank" rel="noopener noreferrer">https://www.rmdlaw.com/personal-injury-blog/car-accidents-in-san-francisco-statistics-intersection-data-and-more/</a> <a href="#fnref3" title="Return to article">↩</a>
  </li>
  <li id="fn4">
    The San Francisco streets where you’re most likely to be hit by a car <a href="https://sfstandard.com/2022/09/21/the-san-francisco-streets-youre-most-likely-to-be-hit-by-a-car-on/" target="_blank" rel="noopener noreferrer">https://sfstandard.com/2022/09/21/the-san-francisco-streets-youre-most-likely-to-be-hit-by-a-car-on/</a> <a href="#fnref4" title="Return to article">↩</a>
  </li>
    <li id="fn6">
    Dangerous San Jose intersection to see safety upgrade after fatal hit-and-runs <a href="https://abc7news.com/san-jose-sj-hit-and-runs-dangerous-intersection-in-monterey-road/11036761/" target="_blank" rel="noopener noreferrer">https://abc7news.com/san-jose-sj-hit-and-runs-dangerous-intersection-in-monterey-road/11036761/</a> <a href="#fnref5" title="Return to article">↩</a>
  </li>
    <li id="fn1">
    Californians will soon be able to jaywalk - as long as it's safe - without getting a ticket <a href="https://abc7news.com/jaywalking-california-new-law-legal/12291007/" target="_blank" rel="noopener noreferrer">https://abc7news.com/jaywalking-california-new-law-legal/12291007/</a> <a href="#fnref6" title="Return to article">↩</a>
  </li>
</ol>



<br>
<br>
