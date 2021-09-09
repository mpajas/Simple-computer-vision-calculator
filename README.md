# Simple computer vision calculator
For the purposes of this projects I'm using a popular MNIST database of handwritten digits in order to simulate a possible application of machine learning. For example a calculator that can read handwritten digits and then give us the answer. The database can be imported using scikit-learn package.

Since I didn't have a dataset of mathematical symbols I wanted to explore artificial training set expansion by augmenting a few self made photos. For each mathematical operation that is considered by the program I made 6 handwritten symbols after which they undergone series of rotations and translations until there was about 1000 of each symbol ready to be added to the training set. The model is performing really well with symbols.

At the end I present a few random examples from data. Should there be a need for a simple calculator that reads digits from MNIST dataset this one performs pretty OK and easily expandable by changing and carefully training any model in the future.
