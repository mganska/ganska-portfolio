
# Data Visualization Assignment: Critique by Design 

<a href="https://mganska.github.io/ganska-portfolio/">Link to My Main Portfolio Page</a>

## **Summary**

For my second data visualization critique, I used a visualization from <a href="https://www.usatoday.com/in-depth/news/2020/07/20/protester-demands-police-policy-change-chokehold-ban/5357153002/" target="_blank">USA Today</a> that was focused on protester demands and recent police reform. Below is a screenshot of this visualization as well as three things that stood out to me as areas that could be improved for impact and understanding. Lastly, I have my visualizations of a way to share this data in an alternative way.

<img src="https://raw.githubusercontent.com/mganska/ganska-portfolio/master/screenshot%20from%20USA%20Today.jpg" alt="USA Today Screenshot" style="height:400px"/>

### **Visualization Areas of Opportunity for Improvement**

1. As the first data visualization in this story, the first thing I noticed was that there were four pages to scroll through of the city data. While this table seems to be designed to show the overall impact from protests, by not containing the impact on one page it would be easy for a reader to scroll past or miss the fact that there are many more cities and states hidden.

2. With the places, by listing all of these cities with no spatial relevance it is hard to picture exactly where someplace like Arcata is and if there are any trends to the changes that are happening. By moving this data to a comprehensive map, it would allow someone to more quickly see that reform is centered in certain cities or states.

3. My last initial reaction was in the overall negative space. Because there were nine reforms possible, and most places only implemented one or two (and none implemented all nine yet) it does give the idea that there is a lot to be done - but again, I thought this negative space would be better seen on a map since it could show that entire states or sections of the country have not addressed any of these issues. 

### **Wireframing and the Results**

I went back and forth between two wireframing options. One was on a map with dots that represented the total cumulative number of reforms in each city so far. The other was a packed bubble design to show overall the number of cities as well as the relative size based upon total number of reforms implemented. 

For both wireframes, I left a title off intentionally to see what the viewer was able to glean from it. In both cases they struggled, so then I gave three example titles I was considering for context. The two participants I had were my spouse as well as my brother. My brother also viewed it digitally and we talked on the phone since we are not in the same city, which I think was helpful because he couldn't see my face for any reactions.

The three example titles I was considering were:
1. Policing Changes Begin, but Protesters still Demand More
2. Police Reform in the Wake of George Floyd's Murder
3. Cities Taking Action are Few and Far Between

#### Wireframe #1 - Map Version

<img src="https://raw.githubusercontent.com/mganska/ganska-portfolio/master/wireframe%20sketches_Page_1.jpg" alt="First Wireframe Option" style="height:400px"/>

When I showed this version and gave the three title options for context, my brother and spouse both thought that this was a map of places that had either defunded the police (my spouse) or a map of cities that were doing things to reform policing (my brother). My spouse thought that the dark blue represented places that had already passed reform measures, and the lighter blue dots were places that were in the process or debating reform measures. My brother thought that the darker blue represented cities that were actually doing something and had done more or a better job. Both found it surprising to see cities in Texas, especially since they were darker blue. Both also liked the use of blue since it ties to cops and the police. My spouse thought the audience was liberal voters.

#### Wireframe #2 - Packed Bubble Version

<img src="https://raw.githubusercontent.com/mganska/ganska-portfolio/master/wireframe%20sketches_Page_2.jpg" alt="Second Wireframe Option" style="height:400px"/>

This version my brother really couldn't tell what it was trying to say. My spouse figured it was also representing the police reform from the title options, but overall while I think this looks impressive, because there is a lack of negative space it doesn't show all the places that reform still needs to occur.

I did test this in Tableau, and I think even after adjusting labeling and the caption it makes it seem like a high amount of reform has happened. Again, thinking back to the original table, the negative space shows just how much more there is to do, so while I think this looks kind of interesting, it really might mislead those who view it.

<div class='tableauPlaceholder' id='viz1595386293942' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-FinalVersion&#47;CitiesLeadingPoliceReformafterBlackLivesMatterProtests&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment3-FinalVersion&#47;CitiesLeadingPoliceReformafterBlackLivesMatterProtests' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-FinalVersion&#47;CitiesLeadingPoliceReformafterBlackLivesMatterProtests&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1595386293942');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

### **Redesigned Final Visualization**

<div class='tableauPlaceholder' id='viz1595386586356' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-FinalVersionofMapVisualization&#47;PolicingChangesBeginbutProtestersWantMore&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='views&#47;Assignment3-FinalVersionofMapVisualization&#47;PolicingChangesBeginbutProtestersWantMore?:language=en&amp;:embed=y&amp;:display_count=y&amp;publish=yes' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-FinalVersionofMapVisualization&#47;PolicingChangesBeginbutProtestersWantMore&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1595386586356');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                   
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                   
vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>

I definitely had some trouble actually getting this map working - I had really wanted to have this map have filters of the type of reform, but I ultimately am not advanced enough with Tableau to do that yet. I do, however, find it more effective than a table at showing the overall impact of protests in the wake of George Floyd's death. Additonally, I did think of the target audience (USA Today readers).
