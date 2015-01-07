# MTP

(1) The input format for the temporal graph G: (1) the first line consists of two integers, "n" and "M", the first integer "n" is the number of vertices in G, the second integer "M" is the number of edges in G; (2) "M" lines are followed, each line denotes one temporal edge and consisits of four integers in the format "u v t lambda". The "M" lines are sorted in the order of their starting time, that is, in the ascending order of "t"; (3) the vertex IDs are ordered from 0 to n-1. 

example.txt
3 4 
0 1 0 1 
2 1 0 1 
1 2 1 1 
0 2 2 1 

(2) two parameters: argv[1]: option (choose from "earliest latest shortest fastest"); argv[2]: the input graph. 

Example:
./tempath earliest example.txt
 
