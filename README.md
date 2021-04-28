Build the neural network prediction model on the Audiobook sales dataset. The data is collected from the particular audiobook company over the two-year period, and it contains 
10 features and 14,084 values, and the target is whether the existing customer will make the purchase in the future. 

The original dataset is unlabeled, thus the pandas dataframe is provided to better understand the data. To ensure the authenticity and reliability of the model, the data being 
considered is shuffled twice to eliminate the possible unaware influences and relations at the initial order, and is reduced to the 4,474 values between the two shuffles in order to have the equal amounts of target values (0 and 1) to fit the model.

Implement the neural network model with TensorFlow. Combine the three activation functions of ReLu, Tanh and Sigmoid for 3 hidden layers, apply the Adam optimizer.
and set the early stopping with the paitence of 3. The training runs for 16 epochs. 

Reach the 83.21% accuracy rate on training set, and 80.13% accuracy rate on test set. 
