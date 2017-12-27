# GoinDownhill
Exploring gradient descent
My first incursion into GitHib, aimed at exploring some ideas I have about speeding up gradient descent. I intend to start with some code taken Andrew Ng's Deep Learning course (hoping this doesn't infringe anybody's rights), and compare speeds for 'standard' descent methods with my own ideas. Basically I make significant adjustments in the learning rate with each iteration, depending on the change in cost. Initial tests I did in the context of the course showed much faster descent using my technique, but I expect this will trip up under duress.
I intend to use 'Unit Tests for Stochastic Optimization' by Tom Schaul et al to put my simple strategy to the test, and expect that adjustments will be necessary, perhaps checking random direction vectors for multidimensional situations.
