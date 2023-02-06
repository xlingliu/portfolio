# Original data visualization
<p><b>Source:</b> https://www.climatewatchdata.org/sectors/agriculture?contextBy=indicator&contextMapIndicator=employment_agri_female&currentLocation=267&emissionsCountry=USA&indicator=1247&model=3&scenario=182%2C181%2C180%2C183&subcategory=93&tab=HISTORICAL_EMISSIONS#drivers-of-emissions</p>

<p>Climate Watch is an open data platform managed by World Resources Institute where I interned with last summer and my work greatly involved in manipulating datasets on backend and importing them to this platform for visualization.
<br>This platform brings together dozens of datasets to let users easily search, analyze and compare countries’ climate progress and commitments under the Paris Agreement.</p>

![emission_whole](https://user-images.githubusercontent.com/108026577/216832564-3b13b259-acee-4b1e-8d0f-1a17f2d71970.png)

# Critique the data visualization
<p>At the first glance of this visualization, I get informed on the data trend over years which is displayed in a very clear and eye-catching way without any redundant or unnecessary components around it distracting the audiences. Instead of static visualizations, this whole website is more of an interactive one which the audiences can play around with, that means the engagement from the audience may be higher. For example, when you mouse over each vertex on the trend line, it will show you the year as well as the amount of agriculture emission(i.e. time and data).</p>

![emission_small](https://user-images.githubusercontent.com/108026577/216833654-0536d06c-2dc5-47bc-a95c-00954026818d.png)

<p>To the right of the trend line, there is a paragraph with a pie chart showing more statistics about the agriculture emission and when you mouse over each section of the pie, it will let you know the specific data of that section. I like the color scheme of this pie chart too in which the only relevant section(i.e. Agriculture) is in blue color, while the rest are greyed out.</p>

![emission_pie](https://user-images.githubusercontent.com/108026577/216833757-9aad288b-3188-433c-901a-3167ee9876d3.png)

<p>I would say this visualization is pretty decent, but there are still a few things that can be improved. First, the number on the x-axis is not consistent. From 1961-2013, they are separated every 4 years. But when it comes to 2013-2019, there are no separation at all combining all 6 years together. Though people can still know the data of each year when they mouse over the specific time point, it makes the visualization less truthful and complete. If I were to modify this, I would stretch x-axis make sure there are enough space and fill up the missing year. Or, if there are indeed some constraints that make it impossible to insert one more slot, then maybe we could focus on more recent years and discard the least recent years which may of less importance.</p>

![Screenshot 2023-02-05 at 12 13 18](https://user-images.githubusercontent.com/108026577/216833891-753987f7-290d-470b-b528-ec9bad2e0573.png)

<p>Also, in this time line, if you mouse over the vertex and read the data, you can find that each data is an integer which is definitely be rounded and not the original true data. For example, the data of 2019 on the trend line is 390 while in the detailed paragraph right next to it says 382. So, I would like to change the numbers on trend line and make the data more truthful and consistent.</p>

![Screenshot 2023-02-05 at 12 15 53](https://user-images.githubusercontent.com/108026577/216834052-b99fb283-97f1-4b15-959a-2a79c475323f.png)

<p>About the pie chart, though it provides a sense of engagement by enabling the audience to only know the data when they mouse over, it is of less convenience and intuitiveness. When I was interacting with it, I always forget what is the section I just moused over and what is the data of that section. It would help a lot if they can just display the corresponding section name and statistic beside it. But there would be a trade-off between engagement and intuitiveness.</p>

<p>There's one more graph that I would like to talk about on this platform. Overall it is a good one, very informative and interesting to interact with as it will provide you with detailed information about each country when you mouse over to that country on map. But I think the color scheme of the map may be a little misleading. In the case of Female employment, it would make more sense to represent higher employment with green color and represent lower employment with blue colors.</p>

![Screenshot 2023-02-05 at 12 20 59](https://user-images.githubusercontent.com/108026577/216834213-99d77e9d-66a0-4831-88b4-cfbf4874197c.png)

# Sketch out a solution
<p>Based on the above critique, I sketched out the solution.</p>

![IMG_73073B6BF18A-1](https://user-images.githubusercontent.com/108026577/216837014-8c0e6fc4-7807-4b70-a706-0befe6318356.jpeg)

![IMG_9EA51D1A2A34-1](https://user-images.githubusercontent.com/108026577/216837048-f86e9227-a410-401f-963a-9edf15eaa124.jpeg)

![IMG_0A2F1AE700B4-1](https://user-images.githubusercontent.com/108026577/216837072-b4115e4b-a1fa-4989-bc50-0a7e73869d35.jpeg)

# Test the solution
<p>Here's the feedback from my interviewee:</p>
<p>In general, your critique makes sense, and the suggested changes could help improve the overall effectiveness and accuracy of these visualizations. However, without access to the original data and context, it's difficult to say for certain that these changes would be necessary or appropriate.</p>

# Build the solution
<p>I redesigned the visualization using Tableau.</p>

![Screenshot 2023-02-05 at 13 56 54](https://user-images.githubusercontent.com/108026577/216839916-4ed607fe-0ba8-4589-83cf-80c6d345edbe.png)

<iframe src="https://public.tableau.com/shared/TFTR5Z9NR?:display_count=n&:origin=viz_share_link" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">Employment Redesign</iframe>
