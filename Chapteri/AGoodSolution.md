## A Good Solution to a Problem that Occurs often and Requires a Rigorous Solution

is to copy somebody else's solution. Oftentimes you might not have the expertese or
time to write a good solution, and really need to get software shipping first. In
that case, just find a library or code snippet that does the work for you. Of course,
to balance this

## Rarely is the Best Solution is to Copy Somebody Else's

Oftentimes the code copied might not necessarily be the best solution for your
particular needs. Architecture, memory constraints, and nature of load factor
into what is the best solution, which is rarely accounted for in libraries.
Sometimes though specialists create libraries for this very purpose, such as
Intel's Thread Building Blocks library or [insert math library here], which
allow for greater expressiveness and better speed than what could reasonably
be coded by non-specialists.

## Writing your own

Of course, some problems are novel enough that they demand equally novel solutions.
Or maybe the libraries out there haven't been updated in forever, or are way too slow.
Then just write your own. This is why all libraries are written: to serve a need in a
way that can be reused later. Libraries can occur in all sorts of sizes, ranging from
single header libraries to an entire framework, depending on how big the problem is.
