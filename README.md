If you run the file rnn_train.py it will train the neural network, I have preset the variables to those that produced the best songs. I've also included a dataset in the folder labelled "Shakespeare"

Once the program has finished training it will save a checkpoint file in the checkpoint folder (It will also save them as the program runs)

In the rnn_play.py folder there's a variable on line 26 called author, replace the author file with the checkpoint file saved from the previous file. Then run rnn_play.py file and the file will write song lyrics. They probably won't be perfect, variables are the optimum that I found, but the dataset is not identical.

Also set the variable "new saver" to the same checkpointfile but .meta, this doesn't need to be done after the first time unless you are watching the training graphs, which I did not do.
