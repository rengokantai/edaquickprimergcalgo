# edaquickprimergcalgo

## Mark Sweep Collection
an automatic memory management system has two key responsibilities:
- Allocate space for new objects
- Reclaim space from dead objects  
An object is considered dead if none of the program's execution paths can reach it.

 Typically, language runtimes trigger GC when they find that the heap is exhausted and 
 there's no more memory available to satisfy a memory allocation request by a mutator thread.
