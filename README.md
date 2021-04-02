# Deep-Learning-Project-about-resources-and-time-optimisation-of-Neural-Networks
Hello there, welcome!
This is project I've worked on during the first semester of my final year at Ecole Centrale Marseille. We were 2 students working on that. 
As said in the title, this project focuses on optimisation of time and resources of Neural Networks. The methodoly used was to try hybridation methods of neural network with machine learning algorithms such as K-Nearest Neighbor. 
The database used was the Street View House Number(SVHN) data. The idea was to conceive a deep neural network (NN) that will perform well on this data and then build a k-nearest Neighbor that will use the different outputs of hidden layers of the NN as input and compare its performance to the NN's one. The hope was to obtain a good performance with KNN using only the first hidden layers of the NN.

So, in the first time we built  several deep neural network models  and tested them on our data. After this step, we maintened only those who performed well (only two).
we conceived then our simple K-NN model first. But the results were not too good. The best performance were only observed using the output of  the last hidden layer of NN. 
Then, we thought about another technics such us modifying the output of the hidden layers by modifying their structure (pooling, and softmax). It leaded then to two new models: 
-The first one was based on the modification of the pooling layers. Instead of using simple pooling, we used General pooling system and then extracted the new outputs. --The second one was based on the modification of sotfmax function of the NN. 
The new results were quite satisfaying when compared to the first model but didn't outperform the NN on the first hidden layers. For some neighbors (k), the latest model outperform the NN on the last hidden layer. 

Finally, we observed some trends related to the effect of hidden layers output on the KNN's performance, the effect of the performance of the NN on the KNN's one.
According to what was the purpose of the project and the results we obtained, we realised it was almost impossible to have the same performance of the NN for the KNN using only the first hidden layers. And the time was not shorter neither. 
As we've observed trends, we could possibly try another technics of hybridation with another Machine learning models to see if we could obtained different and satisfying results.
