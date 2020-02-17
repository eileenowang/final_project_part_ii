# Development from Part I
The goal of this page is to flesh out the structure and necessary parts to execute my final project for Storytelling With Data. It is also to validate and test the logic behind my data storytelling, understand areas of improvement, and iterate before going into Part III.  

One of the biggest challenge coming from [Part I of my final project](https://eileenowang.github.io/final_project_eileenwang/) was that I thought there were so many oppportunities to expand upon, and I couldn't decide on an angle to focus on. I knew I was interested in helping individuals find tangible ways to pursue happiness, but with the dataset I had (which was a overview of happiness ranking by country), it was hard to dig deeper and find a more personal connection. With further research in the happiness domain, I finally decided to tell a story about how individuals could help elders they care about access resources they need to increase their happiness. To realize this story, I will be introducing [a second data source](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6056407/) into my final project.  

# Storyboard / Wireframe 
Below, I will outline how I will tell the story on [Shorthand](https://shorthand.com/). The key findings I want to illustrate in my storyboard are: 

1) Most nations saw social support as the primary driver of happiness. 

2) It is found that 25% of variability in happiness is explained by social support. But social support could mean a lot of things (and this still feels vague). 

3) Digging deeper, there are 2 most impactful kinds of social support- Informational Support and Emotional Support (they will be defined in detail in final product) that contribute to happiness. Now these 2 kinds of support are something we can actively shape and access. 

# My first storyboard
This is what I used to show and gather feedback in my user research:

![initialwireframe](partiiwireframe_1.png)

# Revised storyboard after collecting feedback from user research

For information on the feedback that inspired the changes, please refer to the "Feedback from Users" section:
![wireframes](partiiwireframe_2.png)

Here are some data visualizations I've created for the first half of the storyboard: 

<div class='tableauPlaceholder' id='viz1581897749733' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ha&#47;Happinessworkbook_15818915524550&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Happinessworkbook_15818915524550&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ha&#47;Happinessworkbook_15818915524550&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1581897749733');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1027px';} var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# User research protocol 
*Target audience:* 
Individuals who have elderly people they care about. 

*Approach to identifying representative individuals to interview:*
I plan on interviewing both my friends abroad and individuals on the CMU campus. I imagine most people have elderly figures they care about, so it should not be too difficult to find individuals that represent my target audience. 

*Interview script:*

Introduction: Many of us, no matter who we are or where we are, have elderly figures whom we care about. Our reasons for caring about their happiness may vary- they may be our grandparents or neighbors. Today, I'm looking to share a story about identifying the key factors that drive happiness, and focusing on ones that can help us help elderly people obtain happiness. My storytelling approach will go from big picture to specific details, and end with actionable items at the end. The recommended actions will hopefully inspire individuals with some ideas on how they can help elderly people be more happy. Could you take a look at my storyboard (without me explaining further)?

*Questions:*    
- Are you able to explain the flow of information to me?
- What conclusions were you able to draw from the storyboard? 
- Do you feel like the findings are relevant and compelling enough to inspire individuals like you to take action in the end? 

# Feedback from users
*Feedback from User 1, a friend that lives in NY*
- I think the subject is really interesting, could have so many approaches. I like how you first broke it down into 6 factors.  
- In addition to having a general map of the happiness ranking across countries, another visualization for what drives the happiness rank for each country would be really helpful. It would serve as an intermediate layer in the funnel to identify factors that contributes to happiness. 

*Feedback from User 2, a CMU alumnus*
- I think it's not immediately clear how the storyboard jumps from identifying the factors and then to this chart with "highest contributing factor". I want to see a "big picture" view of the dataset here. 
- Before seeing the storyboard I'm actually not sure what kind of support I'm currently giving my grandparents. 

*Feedback from User 3, my classmate at CMU*
- It might help to have some sort of visualization for the 25% data point. You said there are 2 social support types that account for 25% of variability in happiness, but I don't know what they are, and how they relate to the other social support types. 
- I've never thought of specifying the kind of support I can give my grandma. But after viewing this, it makes sense that I can be much more intentional than just giving her "grandson love". 

*Changes I implemented to my storyboars to address the issues identified:*
- Add a world map view where users can look at the driving factor of happiness for each nation. The map can be filtered by driving factor. 
- Add a data visualization to illustrate "25% of variability in happiness is explained by social support", where the 2 most important ones are informational support and emotional support. In my graph, I will draw both the informational and emotional support to be proportionally bigger than the other social supporting factors. 

# Resources & Links:

First data source: [World Happiness 2019 Report](https://www.kaggle.com/unsdsn/world-happiness#2019.csv)

Second data source:[The Association between Social Support and Happiness among Elderly in Iran](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6056407/)

Visualizations made from: [Tableau](https://www.tableau.com/)

Public link to [access this page](https://eileenowang.github.io/final_project_part_ii/)

[Return to part I of my final project](https://eileenowang.github.io/final_project_eileenwang/)

[Return my main Data Visualization page](https://eileenowang.github.io/data-visualization/)
