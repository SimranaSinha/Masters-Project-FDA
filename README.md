**Project 1**
**[Urban Spatial Order: Street Network Orientation, Configuration, and Entropy](Simran_Sinha_Project_1_FDA.ipynb)**
[Dataset](UrbanSpatialOrder - UrbanSpatialOrder - UrbanSpatialOrder - UrbanSpatialOrder.csv)

The paper "Urban Spatial Order: Street Network Orientation, Configuration, and Entropy" by Geoff Boeing examines street network patterns across 100 global cities.It utilizes OpenStreetMap data and OSMnx software to analyze street orientations and configurations. The study focuses on the entropy of street bearings and other metrics like average street segment length, circuity, node degree, and proportions of intersections and dead-ends. It also introduces a new measure, orientation-order,to quantify a city's grid-like structure. Statisticalrelationships between street orientation-order and other spatial order indicators are explored, revealing distinctive patterns in different regions, particularly between U.S./Canadian and other cities.The research provides insights into urban design and planning, highlighting the complexity and patterns of urban transportation systems worldwide. 

**Tasks**
1. Reading the research paper and understand the method used in the work
2. Loading the urban navigation data set,Preprocess the data (if necessary), such as normalizing or scaling the features
3. Finding out why we need to maintain a uniform scale across the variables for K-means and Hierarchical clustering, Do we need to use scaling techniques for this dataset? 
4. Implementing K-means clustering to categorize the data into clusters
5. Using elbow method to determine number of clusters
6. Implementing Hierarchical clustering using an appropriate linkage method T
7. Trying all the linkage criteria
8. Plotting the dendogram for each criteria
9. For aforementioned methods generate the clustering solution.
10. The clustering solution simply groups the counties into different groups based on similarity and also Investigating and commenting on the clusters

_**Variable selection and scaling ,K-means clustering implementation ,Hierarchical clustering implementation ,Visualizations and Insights**_

**Dataset** UrbanSpatialOrder - UrbanSpatialOrder - UrbanSpatialOrder - 




**Project 2**

As an organization, Word aims to develop a mobile application leveragingaccelerometer data to detect instances of heavy drinking. The primary objective is to create a user-friendly and reliable tool that can accurately identify patterns associated with heavy alcohol consumption based on motion data captured by smartphones. This app will utilize advanced machine learning algorithms to analyze accelerometer readings and detect anomalies indicative of excessive drinking behavior. Additionally, the app will prioritize user privacy and data security, ensuring that sensitive information is handled with utmost confidentiality. The ultimate goal is to provide individuals with valuable insights into their drinking habits, promote responsible alcohol consumption, and potentially facilitate early intervention measures for those at risk of alcohol-related harm.

**Tasks**
1. Understanding the data provided for the project 
2. Investigating whether permutation entropy and complexity method is reliable in differentiating heavy drinking vs. sober cases

**Dataset** clean_tac-20240412T015857Z-001.zip
            https://archive.ics.uci.edu/dataset/515/bar+crawl+detecting+heavy+drinking _(Can download all_accelerometer_data_pids_13 folder from here)_




**Project 3** 
**Mapping the Landscape of Generative AI Research through Web of Science**

In the rapidly evolving field of generative artificial intelligence (AI), identifying key research themes and understanding their interconnections is crucial for academics, practitioners, and policy makers. This project aims to utilize the comprehensive Web of Science (WoS) database to search for publications related to generative AI. Through an analytical approach focused on keyword co-occurrence networks derived from author keywords, we will map the intellectual structure and identify the core themes and trends in generative AI research

**Tasks**
1. Comprehensive Literature Retrieval: Leverage the Web of Science database to systematically search for and retrieve publications related to generative AI. This will involve defining a set of search terms that effectively capture the scope of generative AI, including but not limited to terms like "generative adversarial networks", “generative AI”
2. Keyword Co-Occurrence Network Analysis: Build a keyword co-occurrence network from the author keywords associated with the retrieved publications. This network will visually represent how different research themes in generative AI are interconnected, highlighting the most frequently mentioned and central keywords.
3. Identification of Key Research Themes: Analyze the keyword co-occurrence network using the weighted network analysis. This will help in understanding the focus areas of current research and predicting future trends.
4. Use the “Web of Science ” Portal via Snell Library to collect data 

**Dataset** Project3_Keywords.csv
