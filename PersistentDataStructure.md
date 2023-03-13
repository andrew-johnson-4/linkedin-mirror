# Persistent Data Structure

A persistent data structure in functional programming is a data structure that preserves the previous version of itself when it is modified. 
This means that when you perform an operation that changes the structure, such as adding or removing an element, 
a new version of the data structure is created that reflects the modification, 
while the old version remains unchanged and accessible.

Persistent data structures are important in functional programming because they allow for efficient and safe handling 
of data in a concurrent or distributed environment, 
where multiple processes or threads may be accessing and modifying the same data structure at the same time. 
By providing an immutable interface, persistent data structures can help ensure that different processes or 
threads do not interfere with each other's access to the data.
