# Problem Statement

## Problem 1
- Data File: *problem_1.txt* 
- Each row represent a sequence
- Task: Visualize the sequences like *problem_1_result.png*, with the framework [here](https://bl.ocks.org/mbostock/ca9a0bb7ba204d12974bca90acc507c0)
- Hint: Transfer the data into the following format first
```
{	
	"nodes": [
	    {
	      "name": "A",
	      "node": 0
	    },
	    {
	      "name": "B",
	      "node": 1
	    },
    	...
    ],
	
	"links": [
		{
		  "source": 0,
		  "target": 1,
		  "value": 4
		}, 
		...
	]
``` 


## Problem 2
- Data File: *problem_2.txt*
- Compared with problem 1, there are repetitive nodes in the sequences
- Task: Visualize the sequences without self-loops, like *problem_2_result.png*