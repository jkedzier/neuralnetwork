# Neural Network Analysis

To predict the success rate for Alphabet Soup's investment portfolio, I created a neural network using the file created.  To define the network, I opted for 3 layers based upon the number of featues.  I opted to have a layer of neurons at the number of features (40), a second layer of 20 neurons and a third of 10.  This solution delivered an accuracy rate of 72.6 percent, which is near the target goal of 75%  To optimize performance, I adjusted the number of layers.  I found some benefit in the third layer.  However, all attempts returned results >70%.  Since there was no performance difference in the training time, I kept the layer count high. 

To ensure high performance, I needed to do a few steps to prepare the model
1-Remove columns that did not lend to a prediction, such as Name and EIN
2-Create Other category bins for some columns that had many values with a low count that could skew the results, such as Application Type and Classification
3-Encoded the results to prepare for the model
4-Scaled the model to ensure some metrics, such as Amount Asked did not skew the results either.

If I were to implement a different model, I would opt for a logistic regression model.  The logistic regression model would help evaluate if a investment is successful or not, and the understanding/interpretability of the model would be easier than the black box feeling of a neural network.
