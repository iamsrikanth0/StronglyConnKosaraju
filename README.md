# StronglyConnKosaraju
SCC is a component in which we can reach every vertex of the component from every other vertex in that component. 
What does connection mean? Dependency. So Kosaraju says first get all the dependency between nodes(using topological sorting), then transpose the graph and then do DFS to get SCC
so three steps Topological sort(O(V+E)), Transpose graphO(V+E), DFS O(V+E). So total time Complexity O(V+E)
