# Computational Graph Theory
This week we will focus on topological sort, Dijkstra, and A* algorithm. You can watch videos 15,16,17,18,19 for topological sort and Dijkstra from here [William Fiset's Playlist](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsDGO4--qE8yH72HFL1Km93P) and see the implementation in C++ of topological sort and Dijsktra from step 15 Lecture 3 and 4 [Strivers](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2). For A\* search, you can look at the pdf uploaded in week_3 and implementation from [Geeksforgeeks](https://www.geeksforgeeks.org/a-search-algorithm/)  

## Problems  
### Topological sort  
1. [Longest Path](https://atcoder.jp/contests/dp/tasks/dp_g)
2. [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/description/)  

### Dijkstra
1. [Dijkstra Problem List](https://leetcode.com/problem-list/53js48ke/): You can solve any 3-4 problems from this list.    
2. Complete the three questions given below and make a pdf file for it.    
a. Make an example of directed weighted graph (3 vertices), where Dijkstra algorithm does not produce correct shortest paths, when some weights are negative.  
b. Make an example of directed weighted graph (3 vertices), where Dijkstra algorithm does produce correct shortest paths, even though there are negative weights.   
c. A strategy to deal with negatives could be to shift them all. We find the smallest weight in the graph say it is M and add M to each edge weight. It is easy to see that all weights are now non-negative. Make a small example of graph, where even after doing this shifting, Dijkstra's algorithm doesn't output correct shortest paths.   

### A* search  
1. You are given any n\*n grid in the form of a matrix where 0 represents no obstacle and 1 represents an obstacle. A start point and a goal point has been given. You can move in any four directions. Write a code for finding the shortest path using A\* search algorithm.
2. In the above question replace the grid with an undirected graph where weights might be negative. Write a code for finding the shortest path using A\* search algorithm.
3. [Open the Lock](https://leetcode.com/problems/open-the-lock/description/)
