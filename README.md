# Graph_components
an algorithm that separates graph into groups based on conectivity
 if u have graph like this : A-B-C   D-F   G-Q-W , (a graph with three ailent) it will return this  [A,B,C],[D,F],[Q,W,G] .
 the Graph must be in a file like this : (head,tail,relation)  . ( this format is for Knowledge Graphs)
 the return array is stored in "graph_bfs" variable
 time complexity is n^4

# how to run :
step 1 : make a file that contains tripples (head,tail,rel)
step 2 : run the code like its said on jupyter notebook
step 3 : the result saved on graph_bfs (variable) , u can do what ever u want (counting how many node exist in each ailents or removing small ailents and ect)

## i will be happy if u make this to c++ for its speed
## the numbers produses in the code is the number of ailents that exist in that time , it converge from #node to #ailents (need time)
