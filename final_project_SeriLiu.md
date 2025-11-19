# Yelp Restaurant Landscape: What Drives Popularity, Visibility, and Ratings?
## 1. Topic Overview

For my final project, I will analyze the Yelp Open Dataset to understand what makes certain restaurants more visible, more frequently reviewed, or more highly rated than others. Yelp plays a central role in how consumers make dining decisions, and its large volume of crowdsourced reviews offers valuable insight into real-world restaurant performance.

My project focuses on identifying three key dimensions across restaurant categories:

1. Category prevalence — which restaurant types appear most frequently

2. Consumer engagement — which categories attract the most reviews

3. Rating dynamics — how review volume relates to average ratings

By comparing these three layers, I aim to answer a broader question:
“Are the most popular categories also the highest rated, or do niche cuisines quietly outperform mainstream ones?”

This topic is meaningful because it helps uncover biases in consumer visibility, platform engagement, and rating expectations. The story reveals not only how people dine, but also how online platforms shape our perception of quality.

## 2. Data Sources

I will use the publicly available Yelp Open Dataset, which provides business metadata, user reviews, and restaurant attributes.

Dataset URL: https://www.yelp.com/dataset

Files Used:

business.json – restaurant name, categories, rating, review count, price range, coordinates

Key Variables: business_id, categories, stars, review_count

I have successfully tested loading sample entries to confirm the data structure and feasibility.

## 3. First Sketches (Initial Visualization Plans)

Below are the visualizations I plan to include. I will refine these into polished versions in Part II.


### Figure 1 — Top 20 Restaurant Category DistributioGoal: Show which restaurant categories appear most frequently.
Field: Category_clean, COUNTD(business_id)
Story: Pizza, Mexican, Chinese, and American Traditional dominate the landscape—illustrating the core structure of U.S. dining patterns.

<img width="1146" height="776" alt="image" src="https://github.com/user-attachments/assets/9376e42a-9614-4833-ba86-5260fbf84af8" />


### Figure 2 — Category vs. Review Volume

Goal: Compare total or average review counts across categories.
Field: Category_clean, AVG(review_count)
Story: Mexican, Pizza, Burgers, and fast-casual cuisines receive the most reviews, indicating high traffic and visibility. In contrast, Vietnamese and Mediterranean cuisines receive fewer reviews despite having strong ratings.

<img width="1345" height="811" alt="image" src="https://github.com/user-attachments/assets/53ade7b9-f03b-487b-a45c-c5921ae3efa0" />


### Figure 3 — Review Count vs. Rating (Category Level)

Goal: Reveal the relationship between visibility and satisfaction.
Field: AVG(review_count), AVG(stars)
Story: More reviews ≠ better ratings. Popular categories tend to have average or lower ratings, while niche cuisines often maintain high satisfaction but low exposure.

<img width="1352" height="847" alt="image" src="https://github.com/user-attachments/assets/6fc31764-fd43-458e-b81a-14da4ac830e2" />



These three figures form the backbone of the narrative:
visibility, engagement, and perceived quality are not always aligned.

## 4. Method & Medium

I will use a combination of tools to analyze, visualize, and present the findings:

### Data Processing

Python (pandas, numpy) for cleaning and transforming the dataset; Exploding category strings into row-level Category_clean; Aggregating review counts, ratings, and category-level metrics

### Visualization Tools

Tableau

## 5. Project Outline
1. Introduction

Why Yelp reviews matter

How online platforms shape consumer perception

2. Dataset Overview

Data structure, variables, limitations

Cleaning steps and processing decisions

3. Visual Storytelling

Figure 1: Category distribution

Figure 2: Category vs. review engagement

Figure 3: Review volume vs. rating relationship

4. Insights & Interpretation

Which categories dominate the landscape

Which categories are high-traffic vs. low-traffic

Visibility vs. rating mismatch

Cultural and behavioral explanations

5. Conclusion

Key takeaways for consumers and restaurant owners

Suggestions for future research or platform improvements
