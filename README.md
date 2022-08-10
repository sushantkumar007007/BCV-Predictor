BCV-Predictor: A bug count vector predictor of a successive version of the software system
The repository consis all the dataset along withe Python codes. 

Predicting the number of bugs in a software system intensifies the software quality and turns down the
testing effort required in software development. It reduces the overall cost of software development.
The evolution of hardware, platform, and user requirements leads to develop the next version of a
software system. In this article, we formulate a problem and its novel solution, i.e., we are considering
the prediction of the bug count vector of a successive version of a software system. After predicting the
bug count vector in the next version of a software, the developer team leader can adequately allocate
the developers in respective fault dense modules, in a more faulty dense module, more number of
developers required. We have conducted our experiment over seven PROMISE repository datasets of
different versions. We build metadata using a concatenation of different versions of the same software
system for conducting experiments. We proposed a novel architecture using deep learning called BCV-
Predictor. BCV-Predictor predicts the bug count vector of the next version software system; it is trained
using metadata. To the best of our knowledge, no such work has been done in these aspects. We also
address overfitting and class imbalance problem using random oversampling method and dropout
regularization techniques. We conclude that BCV-Predictor is conducive to predicting the bug count
vector of the next version of the software. We found five out of seven meta datasets reaches to more
than 80% accuracy. In all seven meta datasets, Mean Squared Error (MSE) lies from 0.71 to 4.715, Mean
Absolute Error (MAE) lies from 0.22 to 1.679, MSE and MAE over validation set lie between 0.84 to
4.865, and 0.22 to 1.709 respectively. We also compared the performance of BCV-Predictor with eleven
baselines techniques and found the proposed approach outperform on most of the meta-datasets

This work is published at https://www.sciencedirect.com/science/article/pii/S0950705120302604
