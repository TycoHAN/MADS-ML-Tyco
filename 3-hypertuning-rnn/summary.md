# Summary week 3
Hypothesis 1
By increasing the number of layers the model can capture more complex patterns

Designed mulitple experiments where first the num layers was 2, then 4 and lastly 8. I used 3 epochs for quick testing and kept similar amount of units (64) for isolated testing.

The results of these experiments gave an increase in accuracy for 2 and 4 layers, but didn't do much for 8 layers.

My conclusion was that by increasing the number of layers, the network gets slow but doesn't gain a large increase in performance. This can be the case when we increase the number of epochs, but for now 4 seems like a good start for the number of layers.


Hypothesis 2
By increasing the number of units the model can capture more patterns

Designed mulitple experiments with 64, 128, 256, 512 units while keeping the number of layers at 4 for isolated testing. Also for quick evaluation I kept the epochs at 3.

The results of these experiments showed that giving an increase in the number of units showed an increase in performance everytime.

My conclusion is that by increasing the units the model can capture more patterns and therefore classify the different gestures easier. The networks does get slower by increasing the number of units and therefore I kept it at 512 units for now to proceed for experimenting with other hyperparamters for an increase in performance.

Hypothesis 3
By increasing the number of epochs the model can optimise further because it can get stuck at a suboptimum if the number of epochs is too low.

Designed mulitple experiments by first setting the epochs to 20 and lastly at 50.

The results of the experiments showed that by increasing the number of epochs the performance improves further. Again the model is getting slower with an increase in the number of epochs. I got 99% accuracy with 50 epochs, 512 units and 4 layers.

My conclusion is that with these settings the model converges pretty fast (17 minutes) to a really good perfomance of 99%. This is good enough for predicting the 20 classes.