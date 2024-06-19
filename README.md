## CSE 373 - P3

A set of programs implementing an ArrayHeap with defined methods and constraints

### Implementation

Heap ArrayList starts at the index indicated by START_INDEX.
Required runtimes (where n is the heap size):
-peekMin, contains, size and changePriority must run in O(logn) time. 
-add and removeMin must run in O(logn) time except for the rare resize operation.
-No built-in Java structures (ex. java.util.HashMap, TreeMap, ArrayList, etc.) imported during development of this code.

In addition to checking correctness, our tests also make sure your priority queue is backed by a proper min heap. At the minimum, it ensures that:

-The items field contains your heap. The first element starts at the index indicated by your START_INDEX field.
Every node must have a priority less than or equal to that of its children.
