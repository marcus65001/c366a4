## **4. Plot and Discuss Results (3 Marks)**
### **Explain and discuss the results you have obtained. You should include the scatter plot in your answer.**
![](graph.png)

From the graph, we see that most of the time, backtracking with MRV is more time efficient. But for a few problems, MRV performed worse than FA. One reason may be when the problem has a shallow solution with FA selection order, i.e., when the domains of variables can be more efficiently reduced by sequentially assigning value from left-to-right and top-to-bottom, the MRV will still select the minimum remaining value first, and it had to backtrack a lot more than FA to find a solution.