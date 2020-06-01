# kingdom_connectivity_tests

##Task description

It has been a prosperous year for King Charles and he is rapidly expanding his empire. In fact, he recently invaded his neighboring country and set up a new kingdom! This kingdom has many cities connected by one-way roads. To ensure higher connectivity, two cities are sometimes directly linked by more than one road.

In the new kingdom, King Charles has made one of the cities his financial capital and another city his warfare capital. He wants a better connectivity between these two capitals. The connectivity of a pair of cities, a and b, is defined as the number of different paths from city a to city b.
. 

A path may use a road more than once if possible. Two paths are considered different if they do not use the same sequence of roads the same number of times.
There are n cities numbered 1 to n in the new kingdom and  one-way roads. . City 1 is the financial capital and city  is the warfare capital. Determine the number of different paths between cities 1 and n. Since the number may be large, print the result modulo 10^9 or 1000000000.

Note: Two roads may connect the same cities, but they are still considered distinct for path connections.

####Function Description

Complete the `countPaths` function. It should print your result, modulo 10^9 if there are limited paths or `INFINITE PATHS` if they are unlimited. There is no expected return value.

`countPaths` has the following parameters:
- `n`: the integer number of cities
- `edges`: a 2D integer array where `edges[i][0]` is the source city and `edges[i][1]` is the destination city for the directed road 

####Constraints
- `2 <= n <= 10^4`
- `1 <= m <= 10^5`
- `1 <= edges[i][0], edges[i][1] <= n`

####Output Format
    
Print the number of different paths from city  to city  modulo 10^9. If there are infinitely many different paths, print INFINITE PATHS.

##How to test?
1. Put your function to index.js

2. `npm install`

3. `npm test`

