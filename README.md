# An_Approach_to_Internal_Threats_Detection_Based_on_Sentiment_Analysis_and_Network_Analysis
This is the source code and experiment results of An Approach to Internal Threats Detection Based on Sentiment Analysis Network Analysis. More information that support the findings of this study is available from us upon reasonable request.

The following file introductions are in the order of the first character of the file name.
94-week combination network: The first 94 weeks in the combination network are selected.
103-week combination network: The first 94 weeks in the combination network are selected.
Mapping of the centrality of feature vectors in the emotional network in the combined network: Comparing the differences in the centrality ranking of feature vectors in the emotional network and the combined network Anran email address after preprocessing: After preprocessing, the path of the feasible Anran data mail.
date_to_week: Converting days into weeks is not in units of 7 days, but in this file for reference, because emails are not continuous by day.
Based on the relationship before filtering the number of messages: The number of messages based on the relationship is a filtering measure taken to avoid sparse matrices.
Discretization accumulation matrix: In order to obtain the centrality of the feature vector, the combined network float data is converted into a matrix with 0.28 as the boundary point and 0,1.
Discretization addition matrix: In order to obtain the centrality of the feature vector, the emotional network float data is converted into a matrix with 0.28 as the boundary point and 0,1.
Eigenvector central_factory_dispersity: Data that combines the centrality of network feature vectors.
Email-based emotional score: the score data of each email.
Feature vector centrality_emotion_discrete: Feature vector centrality data of emotional network.
Filtered 2076 relationships: Relationships filtered according to the number of emails.
Mapping of the centrality of feature vectors in the emotional network in the combined network: the difference in the centrality ranking of the two network feature vectors.
Number of relationship-based messages: The number of messages in relationship units.
Original network: A matrix composed of filtered relationships and sorted time series and relationship-based emotional scores.
Original time series: The original time series is obtained according to the date in the email.
Restore Network_emotional accumulation: Restore the matrix of the network based on emotion.
Restore network_emotional accumulation_normalization: Restore the matrix of the network based on peak and singular values.
Singular value: A file that stores singular values.
Sorted mail time series: Sorted time series.
The original network is converted into weekly units: compresses the date of the original network from days to weeks, making it data-intensive.
