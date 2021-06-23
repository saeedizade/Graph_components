# Graph_components
![alt text](https://raw.githubusercontent.com/saeedizade/Graph_components/master/example.png?raw=true "Example of what it dose")

an algorithm that separates graph into groups based on conectivity <br />
 if u have graph like this : A-B-C   D-F   G-Q-W , (a graph with three ailent) it will return this  [A,B,C],[D,F],[Q,W,G] . <br />
 the Graph must be in a file like this : (head,tail,relation)  . ( this format is for Knowledge Graphs) <br />
 the return array is stored in "graph_bfs" variable <br />
 time complexity is n^4 <br />

# how to run :
step 1 : make a file that contains tripples (head,tail,rel) <br />
<b>carefull this format is for directed Graphs but we dont consider direction of graph.</b> <br />
step 2 : run the code like its said on jupyter notebook <br />
step 3 : the result saved on graph_bfs (variable) , u can do what ever u want (counting how many node exist in each ailents or removing small ailents and ect) <br />
<br>
the numbers produced in the code is the number of the island that exists in that time; it converges from #node to #island (need time)
