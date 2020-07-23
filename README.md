# Reyes-94870-Portfolio
Victoriano Reye's Profolio Telling Stories with Data Summer 2020 at Carnegie Mellon University. 

# About Me
My name is Vic, my pronouns are he/him, and I am in the Arts Management Program at Heinz. I previously worked at the Thomas Merton Center doing data management. I'm currently a volunteer with SistersPGH, Covaid.co, and Pittsburgh Mutual Aid doing case management and fundraising. My plans after graduation are to begin working at Allies for Health + Wellbeing, publish comics and video games, and to get a cat. 

# What I Hope To Learn
I don't have much formal teaching on data visualization so I am excited to learn most anything since it is pretty new to me. I mostly hope to learn better design techniques for communicating complex information as well as simple data visualization software techniques. 

# Portfolio
*Assignment: Visualizing Government Debt*

All these charts use the same data from OECD.org which has the debt-to-GDP ratio of countries all over the world over time. The debt-to-GDP ratio is described on the website as "Debt is calculated as the sum of the following liability categories (as applicable): currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable." Some data is missing for some years inlcuding 2019 in which some has not been collected yet. Despite all charts using the same data, the three charts bellow comunicate diffrent things and have diffrent uses.

As shown in the Visual Vocabulary document from FT graphic, bar graphs comunicate a ranking. In this case the ranking is of countries have the most debt. This chart is the esiest to understand of the three. It gives us a clear line up and uses a simple color palet with enough contrast to clearly see diffrent elements. The list of countries is hard to read because it is slanted and cramped but, the mouse over tabs clear up information so this didn't confuse me too much.
<iframe src="https://data.oecd.org/chart/61Ls" width="950" height="713" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/61Ls" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2015</a></iframe>

The secound chart is the hardest to read for me. It is a complilation of multiple charts smushed into one. It is useful in giving a picture of the paterns of each countires debt. It is also taking the extra step from the firt graph and comunicating debt overtime. It is hard to get a hold of at fist but, it is comunicating a lot of information and is the best at ephisizing the each indevidual countries debt and probably would be best for predicting the future debt of a country. However, it would be hard to read if you wented to compare countries two eachother for a given year, like done in the first graph.
<div class="flourish-embed flourish-chart" data-src="visualisation/3178225" data-url="https://flo.uri.sh/visualisation/3178225/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

In my third graph I atempted to make a graph that comunicated the information of the secound graph while also showing a country ranking from year to year. I created a dot graph wich also contains a time lapse. I also added a color gradeint so it would be easier to see changes that where drastic overtime. I was trying to comunicate a lot in this graph. It does not illustrate paterns of indivisual countries over time as the fist one does. However, I think it is successful showing broad shifts in countries while still being able to easlily compare them over the years. It is definalty not as clear as the first graph but, it has the added benifit of showing shifts overtime.
<div class="flourish-embed flourish-scatter" data-src="visualisation/3186746" data-url="https://flo.uri.sh/visualisation/3186746/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

All Gaphs could use some rewoking in terms of labeling and decription. What the Debt-to-GDP and Total % of GDP could be explained or phrased more clearly for the average viewer. The title could also do a better job at illustrating why we are looking at the graph in the first place and why it is important or intresting.

*Assignment: Critique by Design*

<img src="https://c0.piktochart.com/v2/uploads/4ff5230e-f2eb-4016-9187-64a2e6ef86d3/6eeebab7684f656d9d7f3fc005c5f43bbd98d575_original.png?1569845676=" alt="It's not about crime">

I choose to redesing the It's not about crime plot from the website https://mappingpoliceviolence.org/. I choose this graph because, I think this website is an incredibly clear and acessible way to get information on police violence data but, this graph was th hardest for me to understand. The statement is clear, that there is no corilation between violent crimes and killings by police. However, the choice to do a 3 way axis with a limited number of cities confused me and made it harder to understand the chart. Additionally the rate for police killings and the rate for violent crime where not calculated the same way and while one had an axis of 0-20, the other had a axis od 0-12. I felt that the chart could be seen as miss leading to a viewer who was on the fence about these topics and I felt the chart could comunicate the same infromation while being less manipulated.

In my first wire frames I atempted to make the chart as simple as possible and tested diffrent varaibles that could comunicate the same information. I put only two variable and ploted the axies to better show the corilation (or lack there of) between violent crime and the number of police killings. I felt this proved the point about the lack of relationship better then ploting each indevidual city twice.
<img src="https://user-images.githubusercontent.com/14946947/88243898-e38f4c00-cc5f-11ea-9b8d-80fc3c169ed8.png" alt="sketch 1">
<img src="https://user-images.githubusercontent.com/14946947/88243892-df632e80-cc5f-11ea-883d-506a2ae7892e.png" alt="sketch 2">

I showed these sketches to two of my housemates (one is a nerouscientist and the other is an artist) and the beigest insights I got was that:
1. While they could easily tell what they graph was trying to say to them, they stuggled to understand the scope of the data and what each point was. 
2. The Xs where confusing and it would be better for me to use circles.
3. I shouldn't use one variable that is mearued by rate and one that is measured by raw number as this is still being deciving. 
I took these insights into consideration and made a second wire frame that would be the guide for my final visualization. In this version I adjusted the rate of average crime so that it was by population per 1M to match the rate of police killing. I also added the information about the rate into the the axis tittles as done in the original graph. Addionaly, I added more decription into the subheadings to specify that each data point is a police department.
<img src="https://user-images.githubusercontent.com/14946947/88243888-db371100-cc5f-11ea-9a25-c1c1a6e6bc51.png" alt="sketch 3">

The first step to creating this graph was making minor adjustments to how rate was calculated in the data. However, when I did this the numbers for crime rate where much higher then even just the raw number. I did not want to portray the data this way becasue I felt it would misslead people on how much crime there actually is. I tried to adjust the rate of killings by police to per population of 1K but when doing that many of the number droped to less than 0. I felt like this rate would make the killings rate to abstract and would be harder to read the graph. I tried to then just graph the plot by raw numbers but the graph turned out to make a much less effective visual. Additionaly I realized that using raw number was not as menaingful without context of population.
<img src="https://user-images.githubusercontent.com/14946947/88243756-78457a00-cc5f-11ea-8de6-af7c6d5cd9ce.png" alt="first try">

The final design did not end up being as diffrent as the original as I had initially imagined. However, I think it is still more sucessful at illustration a lack of relationship. After this exercise I have a better apriciation for the original as I struggled for hours trying out diffrent varaibles and couldn't come up with a deisgn that was much diffrent.
<img src="https://user-images.githubusercontent.com/14946947/88246235-e7bf6780-cc67-11ea-913f-cc62b94b2cb1.png" alt="it's not about crime redesign">


