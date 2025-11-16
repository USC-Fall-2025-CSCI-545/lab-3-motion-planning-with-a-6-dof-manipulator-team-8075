will add in overleaf after in person

Q5 Observations:

Q6 Answer:
If we only ever sample near the goal with probability = 1.0, the RRT stops exploring the rest of the configuration space. 
RRT works because it randomly grows the tree in lots of different directions, and eventually one of those branches finds a way around obstacles. 
But if every single sample is right next to the goal, the tree keeps trying to extend in almost the same direction over and over. 
All extensions will fail if anything blocks the straight path to the goal, and the tree will never grow outward enough to find an alternate route.
