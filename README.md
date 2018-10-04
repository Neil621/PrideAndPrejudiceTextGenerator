# PrideAndPrejudiceTextGenerator
Keras based Pride and Prejudice Character Level Text Generator with LSTM. Further discussion and information available from: https://www.datadistilled.co.uk/posts/pride-and-prejudice-text-generating-lst-neuralnet.

# Aim?
Train a Long-Short-Term-Memory (LSTM) Neural Network to generate short stories in style of Pride and Prejudice using Keras based at the character level.

# What was the outcome?
A LSTM model with a categorical cross entropy loss of 1.62 (in a test set) that creates Pride and Prejudice endings to user input.

# Where did the data come from?
The original Pride and Prejudice text was retrieved from Gutenberg.org.

# Preprocessing
Chapter headings and non-text characters removed with select words intended for deletion added to a "delete" list.

# Model
LSTM with softmax output function. Optimiser used was RMSProp.
