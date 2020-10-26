# Description
This document is a holding place for ideas related to this project. 
It is a markdown file and as such allows for some formatting, but should also be quick and easy to edit when ideas strike.

# Model ideas
## wake combination
Wakes are typically combined using the square of the L2 norm. However, in a distribution perhaps we could use the ideas in 
Strang V.5 equation 10 for the weighted least squares.

## Basis
We've been discussing using something akin to radial basis functions.

Perhaps we could define a surface with only, say, 2 basis functions that would have peaks and valleys accordign tot eh locations of the turbines.

## Functional wind definition and matrices
I think that there may be some helpful matrix manipulations we could make if we are able to define the system with continuous wind rose definitions. Each wind turbine state should then become a linear combination of the other wind turbine states.

P(k+1) = Ax(k)

Ok, I actually don't think we'll get this down to linear, but I do think we should strive for a continuous wind rose representation.
