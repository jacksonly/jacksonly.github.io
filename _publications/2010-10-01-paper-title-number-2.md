---
title: "Collaborative Learning between Cloud and End Devices: An Empirical Study on Location Prediction"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-2
date: 2019-11-7
venue: 'The Fourth ACM/IEEE Symposium on Edge Computing (SEC'19)'
paperurl: 'http://jacksonly.github.io/files/COLLA.pdf'
---
## Abstract
Over the years, numerous learning methods have been put forward to model and predict different user behaviors on end devices (eg, ads click, location change, app launch). While the learn-then-deploy approaches achieve promising results in many scenarios, data heterogeneity and variability throw impediment in the way of deploying pre-learned models to a large cluster of end devices. On the other hand, learning on devices like smartphones suffers from limited data, computing power and energy budget. This paper proposes Colla, a collaborative learning approach for behavior prediction that allows cloud and devices to learn collectively and continuously. Colla finds a middle ground to build tailored model for each device, leveraging local data and computation resources to update the model, while at the same time exploits cloud to aggregate and transfer device-learned knowledge across the network to solve the cold-start problem and prevent overfitting. We fully implemented Colla with a multi-feature RNN model on both smartphones and in cloud, and applied it to predict user locations. Evaluation results based on large-scale real data show that compared with training using centralized data, Colla improves prediction accuracy by 21%. Our experiments also validate the efficiency of Colla, showing that one overnight training on a commodity smartphone can process one-year data from a typical smartphone, at the cost of 2000mWh and few hundreds KB communication overhead.
[PDF](http://jacksonly.github.io/files/COLLA.pdf)
