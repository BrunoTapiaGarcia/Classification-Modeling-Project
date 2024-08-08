# Classification Modeling Project

### Unsupervised Machine Learning

**Project Overview**

In this academic project, I was tasked with analyzing social media content for a marketing consulting firm in Thailand, a market known for its active social media landscape. The primary objective was to investigate the impact of photo content on engagement across social media platforms, particularly Facebook. This analysis was crucial as the firm traditionally advised clients to prioritize photo posts, believing them to be the most engaging form of content.

**Objective**

The main goal was to assess the validity of the firm's strategy by comparing the engagement levels of photos with other content types. The project aimed to determine whether photos indeed lead in total engagement and specific reaction metrics, such as likes and loves. Additionally, the project involved exploring advanced data analysis techniques like Principal Component Analysis (PCA) and K-means clustering to uncover deeper insights into social media engagement patterns.

**Methodology**

Engagement Analysis: I began by conducting a detailed comparison of engagement metrics across different content types, focusing on the performance of photos. This involved analyzing reactions, comments, and shares to see if photos consistently outperformed other formats.

Principal Component Analysis (PCA): I utilized PCA to reduce the dimensionality of the social media metrics, identifying key components that capture the essence of the data. This step included creating a scree plot to determine the optimal number of components to retain and analyzing the factor loadings to interpret each principal component.

Clustering and Segmentation: Using the retained principal components, I applied K-means clustering to segment the social media content into distinct groups. This segmentation helped in understanding the different types of content strategies used by social media users and their associated engagement levels.

Logistic Regression Models: To further explore the relationship between content type and engagement, I developed three logistic regression models, each using different sets of features: original metrics, principal components, and clusters. The best model was selected based on accuracy and AUC scores, with a detailed explanation of the model's business implications.

**Outcomes**

The project provided actionable insights into the effectiveness of photo content in driving engagement on social media. The findings were proposed to refine the firm's content strategy recommendations, ensuring that clients could maximize their reach and interaction with their target audiences.
 

**Documents**

<a href="facebook_live_data.xlsx">Dataset</a>

<a href="Unsupervised_Analysis_Project.ipynb">Download Jupyter Notebook</a>

<a href="Unsupervised_Analysis_Project.html">View project in HTML</a>


