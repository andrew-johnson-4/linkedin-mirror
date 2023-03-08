# Generational Garbage Collection

Generational Garbage Collection is a GC strategy that divides objects into different generations based on their age. 
Newly allocated objects are placed in the youngest generation, and objects that survive garbage collection are moved up to an older generation. 
This strategy can be very efficient since most objects are short-lived and can be deallocated quickly.

Generational GC is particularly useful when it is known that an entire generation of objects will need to be collected quickly after use.
