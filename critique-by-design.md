| [home page](https://nickhelms.github.io/nickhelms-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and redesign: Caffeine content in coffee
This assignment was a great opportunity to take a visualization and formulate my own opinions, then try my hand at redesigning it. I picked something near and dear to my heart - coffee.

## Step one: the visualization

Source: [https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S](https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S)

<img width="777" alt="Screenshot 2025-02-11 at 9 03 11 PM" src="https://github.com/user-attachments/assets/324210dd-a4db-4762-b048-68e27caf87b6" />

I selected this data visualization because I have a coffee problem and I wanted to learn about how a cup can vary from company to company. In seeing the visualization for the first time, I thought that it contained great information. However, I felt like the design aspect wasn't fully reaching its potential in communicating the message. The table format was helpful for seeing the numbers themselves, but didn't offer much in the way of comparison. I felt like this represented a good opportunity to use the same information, but depict it in a different way.

## Step two: the critique
Generally, I thought the visualization was okay, but not great. While it contained the important information, it was more of a data dump and less of a demonstration of what it means. I think the target audience was clear, which was excellent. However, on top of the relevant info being portrayed poorly, I felt that the visualization contained some unnecessary information, such as the size of each drink. This had little variance across companies and so it felt unnecessary to include when the real takeaway was the stark differences in caffeine content. All things considered, I found the visualization to be fine, but felt that it could be fine-tuned to meet its goals in a more effective way.

## Step three: Sketch a solution
I developed three rough visualizations in Tableau to have options for my final product:

<img width="1146" alt="Screenshot 2025-02-11 at 9 52 11 PM" src="https://github.com/user-attachments/assets/02160e9b-4138-4b28-bc9b-10ff05419e25" />
This visualization is closest to what I identified in my critique, which is a bar chart to show the caffeine content for each company's drinks. It provides an easy way to see the caffeine content and how it varies across companies and drinks.

<img width="1154" alt="Screenshot 2025-02-11 at 9 52 48 PM" src="https://github.com/user-attachments/assets/c62665cd-8346-4ca2-999f-63645d35e99e" />
This visualization shows the data in a similar way, but creates horizontal bars to show the caffeine content. I found it a little easier for comparing different drinks within the same company.

<img width="967" alt="Screenshot 2025-02-11 at 9 53 15 PM" src="https://github.com/user-attachments/assets/eabc6fa0-51ad-4537-af85-883fce57ac63" />
This visualization substitutes circles for the peak of each bar. I think it makes seeing extremes at each level quite obvious (high or low caffeine content), though it might make comparison a little more difficult.

## Step four: Test the solution

**Questions to ask**: 

- Can you describe to me what this is telling you?

- Which option do you prefer?

- Do color choices say anything to you?

- Are you surprised by anything you see?

- Is there anything you would change or do differently?

**Results**: 

The three people I interviewed are all students in their early-to-mid-20s. They come from the MSPPM program at Heinz College.


| Question | Interview 1 | Interview 2 | Interview 3 |
|----------|-------------|-------------|-------------|
|Can you describe to me what this is telling you?          |It is comparing coffee across companies.             |Agreed, maybe the price of coffee?             |I think it is showing the caffeine content in different types of drinks at different companies.             |
|Which option do you prefer?          |The bar chart.            |The bar chart.             |The bar chart.             |
|Do color choices say anything to you?          |They definitely represent coffee.             |I think they are varied enough that you can easily tell which is which.             |I'm also getting a strong picture of coffee from the colors.             |
|Are you surprised by anything you see?          |The variance is shocking, especially seeing how low Starbucks is in comparison.             |It's interesting that two companies seem to not serve lattes.             |The differences within and between companies are surprising.             |
|Is there anything you would change or do differently?          |Maybe add in information about the prices of each drink at each company.             |I'd give a descriptive title and label the axes more clearly.             |Nothing else to add!            |

**Synthesis**: 

It was interesting to see how they responded! I had forgotten to include the title and axis labels beforehand, so it was fascinating to hear that they thought it might represent price. I was not surprised to hear that the bar chart was the preferred style, as this was also my perception. I liked the comments about adding in pricing info and think that would be a cool comparison to see. I was glad to see a surprised response to the data itself; in seeing the original visualization, I didn't feel surprised, but the interviewees seemed shocked that certain companies (like Starbucks) were so low. It definitely gave me some ideas for continuing to refine the visualization.

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1739328667401' style='position: relative'><noscript><a href='#'><img alt='Caffeine amount varies greatly across coffee companiesSource: Which? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;Caffeine_17393277458000&#47;Final&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Caffeine_17393277458000&#47;Final' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;Caffeine_17393277458000&#47;Final&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>             
  var divElement = document.getElementById('viz1739328667401');              
  var vizElement = divElement.getElementsByTagName('object')[0];              
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';   
  var scriptElement = document.createElement('script');           
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';      
  vizElement.parentNode.insertBefore(scriptElement, vizElement);          
</script>


I made some minor stylistic adjustments after the testing process. Namely, I added a title and axis labels to characterize the information. I also adjusted some formatting (font size, boldness, tick marks) to make it a little easier to parse through the important information. I looked into adding pricing information, but couldn't get consistent prices from some companies. They didn't include prices on their website, leading me to believe that it might vary among franchise locations. I also decided that adding pricing would create an entirely new meaning, so I decided to forego that. Ultimately, I find the final visualization to be much more impactful than the original in communicating the different amounts of caffeine at various companies.

## References
Loth, Shefalee. "Caffeine levels in high street coffees vary significantly, Which? finds." Which?, January 31, 2023. https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S.

