# Market-Segmentation
An advertising firm, NutrientH20, needs help segmenting their target audience. We have a data set of their twitter follower's activity, and using k-means clustering we'll help them segment their audience and provide insights around their follower's interest. 

To begin, we start with data pre-processing - understanding the data and removing any nulls. There are 36 different categories where each tweet of each of the followers has been labeled to help us identify their user's interest.  

Users may vary widely in their number of posts, so the next step taken was to normalize the data. This helps ensures that are analysis isn't skewed by a few highly active users.  Next, we also scale the data so that we ensure fairness across the interest categories. 

In order to break down these users into segments, we'll use K-means clustering. Using the elbow method, we can identify the optimal number of clusters to break the users into. From the chart, we see that the "elbow", or where the graph starts to flatten noticeably, appears around 4 clusters. This means our model does not substantially improve by adding any more clusters.

# Conclusion

Providing our cluster summary analysis to ChatGPT allows us to quickly identify and summarize our themes within each cluster and ultimately provide NutrientH20 with a detailed analysis of their social-media audience that consists of these four different market segments: 

**Cluster/ Market Segment 1 - Health and Nutrition Enthusiasts**\ 
- Health & Nutrition: (20.5%) - A significant portion of activity revolves around health and wellness, making this the defining interest of Cluster 1.\ 
- Cooking: (5.8%) - Reflects an interest in culinary topics, possibly tied to health and nutrition.\ 
- Personal Fitness: (11%) - Strong engagement with fitness-related content, aligning with the health-focused theme.\ 

**Cluster/ Market Segment 2 - Social Sharers**\ 
- Chatter: (15.4%) - Highly conversational and engaged in general discussions.\ 
- Photo Sharing: (9.2%) - Visual content sharing is a prominent activity.\ 
- College/University: (5%) - Significant engagement with education-related topics.\ 
- Shopping: (3.7%) - Active in discussing or sharing shopping-related content.\ 
- Health & Nutrition: (4.7%) - While not the defining characteristic, health still resonates with this group.\ 

**Cluster/ Market Segment 3 - Politically Engaged and Outdoor Enthusiasts**\ 
- Politics: (14%) - Political discussions dominate this cluster, making it the defining feature.\ 
- Travel: (8.6%) - A secondary focus on exploration and travel-related topics.\ 
- Outdoors: (4.8%) - Engaged in outdoor and nature-related discussions.\ 

**Cluster/ Market Segment 4 - Family-Focused and Beauty Enthusiasts**\ 
- Family: (7.9%) - Strong interest in family-related content, suggesting a family-oriented audience.\ 
- Beauty: (8.8%) - High engagement with beauty-related topics, a defining characteristic of this cluster.\ 
- Cooking: (6.8%) - Culinary interests align with family and home-oriented themes.\ 
