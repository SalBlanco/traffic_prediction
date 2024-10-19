# Traffic Prediction

Time is the most valuable non-renewable resource humans have. Technologies such as full self-driving (FSD) are meant to provide us with the ability to multi-task or bypass mundane chores that interrupt our productivity. While FSD can circumvent the monotony of driving itself, there is one huge issue it cannot fix—traffic. According to a study conducted by the transportation company Inrix, nearly 10% of all traffic delays are caused by poor signal timing at intersections, with some states reporting this can be as high as 25%! Today, traffic signal scheduling is determined by set timers, sometimes influenced by sensors that measure relative traffic density. This is especially true in larger cities where traffic does not considerably subside throughout the day.

This project explores the efficacy of Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and Graph Neural Networks (GNNs) for predicting traffic density within a network of sensor locations. Deep learning methods are particularly suited for detecting complex relationships between features, which is a significant improvement over static models. When it comes to traffic, it is imperative to consider both the spatial and temporal factors involved in modeling population changes over time.

We utilize data from the state of California, specifically the METR-LA dataset, which contains over 10,000 samples of traffic density at 207 sensor locations. Results show that encoding both spatial and temporal features produces a robust model that accounts for the volatility of the data.

