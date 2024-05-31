Now, i wanna talk a little about something that i consider pretty interesting: 
the complexity of this algorithm.

# NOTE ABOUT THE COMPLEXITY

Now, the complexity of this basic algorithm is pretty awful: we can clearly see (even without calculating it) that the time needed for the procedure to computer the k clusters is extremely high increasing the number of points. While writing it i thought it would be an O(n^3) or O(n^4). We could try to calculate precisely it but it's not this the case. I just wanna point out some ideas i had to decrease the complexity: 
1. Using a min-heap to store the distances should decrease a lot the time we need to each time finding the min_distance.
2. We could just store, for each point, only the min_distance from every other point. We must give more information in this case, but it should save both time and space.
3. We should think about a way to compute more efficently the centroid in each cluster. Well, i think there are some way to do it, so yeah, i should check out. 

Said that, i don't know if i'm gonna implement all of this stuff because i'm working on something more interesting right now, but feel free to take the idea and make them yours.



