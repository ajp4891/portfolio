# Critique By Design:

## Introduction:
After going through 40-50 visualizations online, and with some really beautiful and well-structured charts that are having proper dataset TO some charts with many bad elements that could have been improved but have no dataset TO some good data which doesn’t have any charts online, I had shortlisted a few viz to critique and redesign. After failing to recreate the expected visualization based on the correction/critique/feedback for 4 of the other visualization, below viz is what I have selected finally to critique. Using my experience from the other 4 (partially completed) viz, I understood the changes that this viz requires. Additionally, I have found more data in a different spreadsheet online for the same topic to add more weightage to this chart. The original chart shows only average US differences while I have added furthermore regions, having Most and Least Cost Counties. I have additionally changed Colors to show more impact on the numbers.

### Step 1: Find a Data Visualization (with data you can use!)

I Selected the below visualization that was originally posted on the Twitter and could be improved. I searched for further data to look for further information to add to the story. I found the original source KFF which had further data but distributed amongst different data sources/topics. I collected those to add into the understanding of the user and give a broader picture. Before selecting the below one, I had identified and worked on 4 others viz with larger dataset. While other 4 had many elements to work on and make it better, I found this viz to be simpler and could be improved if more data is to be added to the chart. This just gives a simple idea but mainly for the audience with some understanding in the field, however it can be elaborated and made further simpler for novice who would like to understand how they are affected due AHCA change in 2020. What are their plans for future, and how it could have benefitted you or not?

![Graph](/HealthCare_CritiqueByDesign_OG.png)


### Step 2: Critique the Visualization
The visualization is quite straightforward giving information in the sleek design. Provides appropriate number of dimensions for conveying the message, e.g., age, salaries, and difference of ACA and AHCA i.e., the impact of AHCA. 

It has one x-axis that has the entire story. This chart is trying to give the 3 different perspectives for the audience, one with the specific age, one who is in the specific salary range, and the last one is for overall picture of the US average (all data combined). Although, this x-axis gives a feel of Timeline as there is not Y-axis, while looking at the viz rapidly, which means the user may interpret the viz's meaning wrong, sensing the data presented from left to right as a timeline. Additionally, the X-axis has two dimensions overlapped, this could have been separated in X and Y axes combination, age being on the Y axis while salary on the X or vice-versa.

Even though this viz is simple, it lacks many elements to it, which could have improved viz's purpose. This Viz would only attract those audience who has prior understanding in the field as this doesn’t give many details about what the ratio of the difference is, whether the difference is minor, major, or negligible compare to the original value. It also doesn’t mention for which region, and whether if it’s a difference of an average or the sum.

Colors are also minimal, which is good, however could be improved by assigning the gradient of colors to show the impact visually for the audience who would like to have a brief look. 


### Step 3: Wireframe a Solution

### Step 4: Test the Solution





### Step 5: Build Your Solution

##### Viz 1: AHCA Impact on Different Salaried and Age Group. USA Average vs Most-Cost vs Low-Cost.


While I looked at the original graph, my first thought was why the graph is so simple and minimalistic (obviously in a good way, I like the minimalistic and simple viz). Then I tried to understand without the context, and I barely understood the viz. I realized this graph needs a touch up. I looked at the header and I started partly understanding the purpose of the graph, although not entirely that for e.g., how to read it precisely, what is the comparison, whether the difference is huge or less, whether the difference is specific to a state or a region or a county, and so on.

While going further in critiquing, I realized I may have to build the similar graph but slightly differently. Not only re-designing is required but more data/information is required that would provide additional context and comparable viz that adds to the understanding of not only experts but also novice audience. I, then, began to look for the original data source (I found originally from Twitter and so an URL to graph in Excel). Once I found KFF (data source), I looked for more relevant data and found additional details that helps me understand why Age and Salary mattered. I then started to anticipate the idea of my design. Age seemed quite better when put it on the Y-axis instead when merged with Salary on the X-axis. This gave quite a clear picture at first for the purpose of introducing Age and Salary in the graph. While going further, the difference made more sense when I started comparing with Counties that had Most and Least Cost in the state. This gave an idea where the US Average resides, and where each county could be placed, visually, if have to place mentally.

Last thing I believed the color looks solid on the original graph, but that could be improved by introducing gradient for showing happy and sad effect on the AHCA impact compare to ACA. These two colors and the shade of these two, based on their lower/higher values, provides an overall idea to the audience that where more impact of the difference is. The columns of salary group, a vertical line keeps the visualization clean by segregating the salary range. Similarly for horizontal line separates region and US average for better understanding why original viz did not.

Additionally, the average is kept in the middle so most and least cost counties can be compared easily, and gives a gradient effect on values of bars from top to bottom (high to low). The bar labels provides the difference value next to it, which is in termso of $1000. The fraction provides simpler and less congested viz.


<div><div class='tableauPlaceholder' id='viz1636417525087' style='position: relative'><noscript><a href='#'><img alt='American Health Care Act Impact on Salaried Employee - 2020 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;v1&#47;v1_Healthcare&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='v1_Healthcare&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;v1&#47;v1_Healthcare&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1636417525087');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1350px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1350px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script></div>






##### Viz 2: Projection of ACA vs AHCA - 3 Years, 5 Years, 10 Years

Once the above graph was built, and post feedback and critiquing, I realized we needed furthermore details on the values and impact of these changes in the future. User gets a better idea if they can see the projection that the possibility of the impact over time. The prediction shows simple two-line graph and the shaded region between these two lines highlighting the difference between these two region in the chart.

<div class="flourish-embed flourish-chart" data-src="visualisation/7778756"><script src="https://public.flourish.studio/resources/embed.js"></script></div>






##### Viz 3: ACA vs AHCA Tax Credit Comparison

Finally, the we come back to the main point that I identifiedi while critiquing, which is - "whether the difference is minor, major, or negligible compare to the original value", this below chart gives values, the original, for different salaried range. This gives a general idea. Additionally I have found details of ACA and AHCA values for each state (originally it was county wise in each state, which is now the average amongst all the counties for that state). This is a simple bar graph for each state in the United States. Along with the graph, there is filter to add/remove specific salaried group, or use to compare two or more specific salary group for ACA or AHCA. Note AHCA is same for all salary range below $75000. While displaying, I noticed salary range $75000 has all Zeros, hence removed the column for simiplicity.

The bar is grayed out for ACA, while it is blue for AHCA for easy eyeing to avoid making a mistake (due to only 1 column of AHCA and rest ACA). It is also sorted based on high to low value, on average. It is mainly grayed so that this graph can be kept as an optional for the user, if he may want to check out the actual credit value and not the difference. However, due to lack of data for each age group, I was able to display only the age 60's values.

Additionally header for x axis is given on top so that user dont have to scroll all the way down, along with values next to each bin. Slight grayed background for bookish touch for the viewers, as of sticked chart.

<div class="flourish-embed flourish-chart" data-src="visualisation/7781322"><script src="https://public.flourish.studio/resources/embed.js"></script></div>






#### Data Source:
Image source: [Download XLSX](http://policyviz.com/wp-content/uploads/2017/03/ACA-ACHA-comparison.xlsx) (Sheet 2)
https://twitter.com/cynthiaccox/status/838950883622801408
https://public.tableau.com/app/profile/ajay.patel6510/viz/v1_Healthcare/Dashboard1?publish=yes
https://www.kff.org/health-reform/issue-brief/how-affordable-care-act-repeal-and-replace-plans-might-shift-health-insurance-tax-credits/
https://www.kff.org/health-reform/press-release/health-insurance-premiums-under-the-aca-vs-ahca-county-level-data/
https://www.kff.org/interactive/tax-credits-under-the-affordable-care-act-vs-replacement-proposal-interactive-map/
https://twitter.com/cynthiaccox/status/838950883622801408





Go Back to [Home Page](/README.md)
