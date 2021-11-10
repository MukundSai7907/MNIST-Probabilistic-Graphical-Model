# MNIST-Probabilistic-Graphical-Model
A Probabilistic Graphical Model (PGM) relies on conditional independence assumption. For this particular case, the conditional independence assumption is as follows:

"A pixel in the image is independent of every other pixel in the image excpet the ones to the left and the top of it"

In other words, a pixel's parents in the PGM graph are the pixels to the immediate left and top of it. 

Note: Pixels on the left and top edges of the image are considered completly independent and simple Naive Bayes is implemented for them
