| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# TSWD-portfolio-templates
These portfolio templates are for setting up your Telling Stories with Data site.  Edit these pages and add new ones as needed.   
It's always helpful to keep track of your web URL.  Consider putting that somewhere on your page for easy reference: 

- Web page URL: https://cmustudent.github.io/tswd-portfolio-templates/
- This repository: https://github.com/cmustudent/tswd-portfolio-templates/

# Portfolio
Come and see how I tell stories with data！

# About me
Hi! This is Seri. Actually, I’d like to tell you a bit more about my English name — Seri. It comes from a Korean drama where the heroine owns a company called Seri’s Choice. In the show, she once said, “Whether it’s a choice that depends on luck or one that depends on ability, I always make the right choice.” I really like that quote, and I hope that in my own life, I can also turn every choice I make into the right one.

# What I hope to learn
All the things - obviously. Maybe I want to make a list of all the things.  If so, I can do so in Markdown like this: 

1. how to turn complex datasets into clear visualization
2. how to identify the narrative structure behind data
3. how to balance accuracy with storytelling

Also, I want to work as a marketing analyst after graduation.

# Portfolio

# Makeover Monday Assignment #2  
## Redesign of “Christmas gifts most desired by UK consumers in 2024”

## 1. Original Visualization
Below is the original data visualization sourced from Statista:

https://www.statista.com/statistics/1084794/christmas-gifts-desired-by-uk-consumers/#statisticContainer

**Source:** Statista, “Most desired Christmas gifts in the UK (2024)”.


## 2. Critique Summary (Using Stephen Few’s Effectiveness Profile)

**Usefulness:**  
The chart is useful and communicates the basic ranking of gift preferences. However, the visualization is long and contains too many items without grouping, which increases reading effort.

**Completeness:**  
The visualization includes categories and percentages but lacks additional context such as sample size and methodology.

**Perceptibility:**  
While readable, the uniform blue color makes it difficult to distinguish types of gifts. Long vertical scanning increases cognitive load.

**Truthfulness:**  
The data appears accurate and is not misleading. No manipulation of the scale.

**Intuitiveness:**  
The horizontal bar chart format is familiar, but the large number of bars reduces intuitive readability.

**Aesthetics:**  
Clean but visually plain. No visual hierarchy, color variation, or storytelling components.

**Engagement:**  
Informative but not engaging. It doesn’t draw the viewer into exploring or noticing key insights.


## 3. Redesign Goals
Based on the critique, my redesign focused on:

1. **Reducing cognitive load** by grouping categories into logical gift types  
2. **Improving visual hierarchy** using color coding  
3. **Highlighting key insights** with annotations  
4. **Creating a more structured and intuitive layout**  
5. **Enhancing storytelling** without overwhelming the viewer  

## 4. Data Preparation
I cleaned and grouped the dataset into four meaningful categories:

- **Gift Items** (e.g., clothing, books, electronics)  
- **Monetary Gifts** (money, gift cards)  
- **Experience-Based Gifts** (food/drinks, travel, event tickets)  
- **Other / Non-Gift Responses** (don’t know, don’t want anything)

## 5. Wireframes
Before building the final version, I sketched several layout options.  
This helped determine grouping structure, color palette, and annotation placement.

## 6. User Feedback Summary
I shared my wireframes with a classmate and asked for quick feedback.  
Key takeaways:

- Grouping categories made the chart easier to follow  
- Adding colors for each group significantly improved clarity  
- The viewer wanted key insights highlighted instead of requiring them to scan the full chart   

This feedback helped shape the final design.

## 7. Final Redesigned Visualization (Tableau)
Here is my final version, redesigned in Tableau using grouped horizontal bar charts:
https://public.tableau.com/app/profile/shiyu.liu5683/viz/MostDesiredChristmasGiftsintheUK/Sheet1?publish=yes

### Key Improvements:
- Added **semantic grouping** for clarity  
- Applied **distinct color themes** per group (Gift Items, Monetary, Experience, Other)   
- Reduced scrolling and improved readability  
- Strengthened storytelling  

## 8. Key Insight
**Clothing remains the most desired Christmas gift in the UK (41%), followed closely by monetary gifts (39%), indicating strong consumer preference for flexibility.**


## Final project
Here it might be helpful to include a high-level description of your final project. 
[Part I](final-project-part-one)
[Part II](final-project-part-two)
Part III(final-project-part-three)

## Things you want to share most

## What you have learned from this class

### Changing text

You can change text, like this: 

**Here's some bold** text.  Here's some *italic* text. Here's some ~~strikethrough~~ text. 

### Creating tables

You can build tables like this: 

| Name         | Type of pet | Favority activity 1 | FA 2   | FA 3            | FA 4                                |
|--------------|-------------|---------------------|--------|-----------------|-------------------------------------|
| Eli          | cat         | Sleeping            | Eating | Being pet       | Plotting to overthow dog empire     |
| Howard       | dog         | You                 | You    | You             | Eating                              |
| Frankenstein | fish        | Swimming            | Eating | Blowing bubbles | Forgetting                          |

An easy-to-use template generator tool [can be found here](https://www.tablesgenerator.com/markdown_tables)

You can use different headings, like this: 

# Here's a large title (H1)
## Here's a subtitle (H2)
### ...and so on (H3)
You get the idea - just don't forget the space between the # and your title.  `#Title` won't work, but `# Title` will. 

### Adding images

Here's an example of how to add an image to my portfolio.  

![funny dog picture](funny-dog-unsplash.jpg)
> Photo by <a href="https://unsplash.com/pt-br/@charlesdeluvio?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">charlesdeluvio</a> on <a href="https://unsplash.com/photos/K4mSJ7kc0As?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

Alternately, you can set the size of the image using just a bit of HTML: 

<img src="funny-dog-unsplash.jpg" width="200"/>

Remember that you'll need to upload the image into your repository, or include a link to the image somewhere else.  

### Setting up a separate page

So here's the code you'll need to add to your own site to create a second page. 

1. First, create a new page in your repository (for example, dataviz1.md)
2. Next, add a link to that page by inserting the following into your readme.md page:

`[title](dataviz)` or `[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` or `[CMU](https://www.cmu.edu)`

Any of those formats will work. Here's some examples of working links: 

`[title](dataviz)` = [title](dataviz)  
`[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` = [dataviz](https://cmustudent.github.io/portfolio/dataviz.html)  
`[CMU](https://www.cmu.edu)` = [CMU](https://www.cmu.edu)   

Make sure to check these from your publicly accessible URL to make sure they're working correctly (not from the preview tab). 

Looking for more?  A nice Markdown guide [can be found here](https://www.markdownguide.org/cheat-sheet/)

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

