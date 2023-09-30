We determine the efficiency of an algorithm by measuring its complexity, where we measure:
- the time complexity (time it takes to run/execute)
- the space complexity (memory it needs to run/execute)

The process of measuring the complexity of algorithms is called the ==analysis of algorithms==

It is not always easy to compute actual time for an algorithm
- Therefore we ususally measure worst-case time

- The running time of [[Algorithms]] typically grows with the size of the input dataset
- Average case time is often difficult to determine
- We focus on worst-case time
	- Easier to analyze
	- Crucial to applications such as games, finance and robotics

### Limitations of Experimental Strategy
- Limitation:
	- Sometime, implementation is language dependent.
	- Results may not be indicative of the running time on the data items other than the experimental ones
	- In order to compare two algorithms, the same hardware and software enviroments must be used
- Strategy that allows the analysis of an algorithm (independent of the hardware/software enviroment)
	- Focus on the [[Pseudo-Code]] of the algorithm instead of an implementation
	- Characterize running time as a function of the input size, n
	- Consider all possible inputs

## Big O Notation
![[Big O Notation]]
