# Non-Profit-Crowdfunding-Recommendation-System

In this project we have built 2 recommendation systems (content and collaborative filtering) to recommend new projects to existing donors based on their donation history. Ypu can take a quick look at the powerpoint summary with the results and conclusions. For a detailed report and analysis please refer to python notebook.

**Content Based Filtering** - We used TF-IDF scores and Cosine similarities on project titles and project descriptons to identify new projects which are similar to past projects to which a donor has donated. Overall we found that content based filtering tends to work better when we have more variety of projects donated by a donor. This helps us better understand their interests and likes/dislikes, eventually helping us provide individual recommendations. We recommended projects with an average precision of 54% and recall of 51% on top 1000 donors. 

**Collaborative Filetring** - We used Singular Value Decomposition to find new projects for a donor based on their   



Below are the contents of this Analysis

1. Background
2. Key Business Questions
3. Data Overview
4. Exploratory Data Analysis
5. Data Pre-processing
6. Recommendation Systems

    i. Content Based Recommendation System
  
    ii. Collaborative Recommendation System
  
7. Conclusions
8. Next Steps
