
DESCRITPION:

- The purpose of python notebook is to generate a csv for tableau.  
- Use that csv to load to Tableau then follow the instruction at the below link to build the network work graph in tableau. 

http://www.clearlyandsimply.com/clearly_and_simply/2012/12/build-network-graphs-in-tableau.html 


TEST IT:
- Make sure the network graph of tableau is the same of python networkX graph.
- You can change different graph types in networkx to generate a different look of network to see what fits our project.

pos=nx.spring_layout(G, k=0.04, iterations=10, scale=100)
#pos=nx.shell_layout(G)
#pos=nx.spectral_layout(G)
#pos=nx.random_layout(G)


THE END GOAL:
The end goal is to break our dataset of nodes to 2 csv files as the input of python code in these lines.

inputedges = pd.read_csv('./data/edges.csv')
inputnodes = pd.read_csv('./data/nodes.csv')

Then we can build network graph for our final project.



