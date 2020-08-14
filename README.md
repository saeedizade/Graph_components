# Graph_components
![alt text](https://raw.githubusercontent.com/saeedizade/Graph_components/master/example.png?raw=true "Example of what it dose")

an algorithm that separates graph into groups based on conectivity <br />
 if u have graph like this : A-B-C   D-F   G-Q-W , (a graph with three ailent) it will return this  [A,B,C],[D,F],[Q,W,G] . <br />
 the Graph must be in a file like this : (head,tail,relation)  . ( this format is for Knowledge Graphs) <br />
 the return array is stored in "graph_bfs" variable <br />
 time complexity is n^4 <br />

# how to run :
step 1 : make a file that contains tripples (head,tail,rel) <br />
step 2 : run the code like its said on jupyter notebook <br />
step 3 : the result saved on graph_bfs (variable) , u can do what ever u want (counting how many node exist in each ailents or removing small ailents and ect) <br />

## i will be happy if u make this to c++ for its speed
## the numbers produses in the code is the number of ailents that exist in that time , it converge from #node to #ailents (need time)
