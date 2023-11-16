#Data Visualization Redesign Challenge

For a course assignment, I chose a data visualization and redesigned it with a twist. The idea was to take an existing visualization, review it, redesign it, and improve it iteratively using feedback from peers.

## Step 1: Choosing a visualization
The visualization I chose to review and redesign is [Who do we spend time with across our lifetimes?](https://ourworldindata.org/time-use#who-do-we-spend-time-with-across-our-lifetime),
created by Esteban Ortiz-Ospina, Charlie Giattino and Max Roser for Our World in Data. I chose this visualization because it has interesting observations about who average Americans spend time with throughout their lives, with companionship diminishing as they get older. So, for my resdesign, i wanted to focus this aspect.
## Step 2: critique the data visualization
To evaluate the visualization, I used [Stephen Few's Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf). Moving through the evaluation metrics, I gained the following insights into how the visualization could be improved:
1) The visualization used similar colours for all the variables, making them indistinguishable from each other.
2) It failed to tell a story or convey a message, even though the information could have been used to highlight one or several interesting takeaways.
3) even thought the original data measured time spent in minutes per day, I felt that converting it into hours would make it more relatable and intuitive for the audience.
4) I felt that the "joints" or dots at in the line graphs for every age created noise and did not add any value to the visualization.
##Step 3: Create a sketch of the resdesigned visualization
The insights helped me sketch a new version of the graph that highlights the feature that stuck out the most for me - that Americans spend an increasing amount of time by themselves as they grow older. I highlighted this category with a distinct red color, removed the “joints” in all graphs to create smoother lines, and converted the minutes to hours to make it easier for my audience to imagine time spent.
 
![](https://github.com/fmisbah/Telling-Stories-with-Data/blob/main/time%20spent.png?raw=true)
 

##Step 4: User Feedback
I interviewed two of my peers at Heinz College, both of whom are between the ages of 25 and 30, and work with data on a day-to-day basis. I asked them the following questions and recorded their answers below.
Q1: Can you tell me in a few lines what you’re looking at?
Student 1: It represents who we typically spend time with throughout are lives in the form of hours spent per day.
Student 2: This is a line graph showing the progression of our time spent with different groups of people (including self) over our lifetimes, starting from age 15.
Q2:  Is there anything you find, interesting,  surprising or confusing?
Student 1: I find it fascinating and perhaps a bit sad that the time spent with family other than children stays pretty much the same from age 25 to 80. That’s most of our adult lives.
One thing that’s not clear is who was surveyed for the data. Because who people spend their time with varies from culture to culture, country to country.
Student 2: I find it oddly surprising that the other categories either eventually plateau or go up and down, but “alone” is the only one going up constantly after age 25.
Q3: Who do you think is the intended audience for this?
Student 1: Humans in general.
Student 2: Researchers in various fields of social sciences.
Q4: Is there anything you would change or do differently?
Student 1: 
(a)There are too many small peaks and valleys along the lines; removing some redundant data points to capture the “big picture” trends would make the visual much more engaging.
(b) The colors for “family (not children)” and coworkers are too similar. I would assign them distinct colors or group some similar variables together to reduce the number of overlapping lines.
(c) I would add information about who was surveyed for the data to provide context to the visualization.
Student 2:
(a) Perhaps it would be better if the time spent with each category of people represented a proportion of the day instead of absolute numbers of hours.
(b) I would design a more obvious legend, with boxes for symbols instead of lines. That would help reduce the time it takes to refer to the legend to interpret the graph.
Q5: What’s something you like about the graph?
Student 1: I like how the visualization is titled; it prepares you for what you’re about to learn from it.
Student 2: The fact that the trend line for “alone” is more prominent than others, as it makes the message trying to be conveyed very clear.

Thoughts and Insights: Conducting user feedback interviews made me realize my design could use significant improvement. I genuinely appreciate the constructive feedback I got and believe that the critique made a lot of sense. First and foremost, I knew I had to mention the population that was surveyed for the information to provide context.
I also agree with the remark that the network of intersecting lines creates clutter and doesn’t really add value to the visualization when I thought about it.  This prompted me to remove the lines altogether and convert the graph into an area chart.
The feedback also motivated me to remove some color, especially since my objective was to highlight the upward trend of the time people spend alone. Needless to say, the final redesign looks a lot different from the intermediate sketches.


<div class='tableauPlaceholder' id='viz1700100979869' style='position: relative'><noscript><a href='#'><img alt='From adolescence to old age: are Americans lacking companionship as they get older?Average time spent with others is shown in hours per day and shown by the age of the respondent. This is based on averages from surveys taken from US residents between 200 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wh&#47;WhoAmericansspendtheirtimewith_17000985411740&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WhoAmericansspendtheirtimewith_17000985411740&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wh&#47;WhoAmericansspendtheirtimewith_17000985411740&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1700100979869');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

In my final attempt at redesigning the graph, I converted the original line graph into a stacked area graph, with the number of hours spent per day stacked (summed) along the y-axis. Most notably, I used color to highlight the time people spend alone and how that time progressively increases with age. This is something that stuck out to me in the original visualization, and I want the audience to think about aging and its potential correlation with companionship when they look at this graph. 
I feel that the stacked area graph helps represent the proportion of each category of people that we spend time with in a full day. Additionally,  it neatly separates each category while maintaining the information that is being presented. This method, in my opinion, is much better than using lots of intersecting line graphs to present the same data.
I also updated the title and description to mention that the data was collected from US residents, and I hope that provides the audience with some regional and cultural context about who Americans typically spend their time with. 
I removed the legend and labelled each category on the graph. This may not look that visually pleasing but it helped me use the same shade of grey for all categories and separate them using borders. 
Although my attempt at redesigning the graph is far from perfect, I think it does a good job of conveying a message and telling a story.

