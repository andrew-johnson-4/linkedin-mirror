# Consistent Hash Algorithms

Consistent Hashing describes a class of hashing algorithms that work contrary to how most familiar hashing algorithms work. 
Normally it is important to avoid collisions, so small differences in input will be amplified to generate large differences in output. 
By contrast, consistent hashes will generate similar output for similar input.

Consistent hash functions are useful for load balancing and distributed computing where it can be expensive to recalculate a mapping. 
For example, dropping or introducing a node in a cluster should not be catastrophic.
