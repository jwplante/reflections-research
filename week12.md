# Reflection Week 12
For this week, I was taking a look at some papers relating to how to represent our final project and became interested in flow maps after
reading the paper I will be describing by Phan et al. The main purpose of the paper is to describe an algorithmic way to create flow networks
while having the same structure to be able to lay on top of each other while minimizing "edge crossings", meaning whenever the branches of the
flow graph intersect. From what I understand it uses a technique called hirearchical clustering to find nodes that are close to each other, then
creates a binary tree based on this clustering. Additional clustering is then applied to base the network on a specific root node (or source) which
can be done for any root while still keeping the structure of the graph. The authors also provide a pretty simple and easy-to understand algorithm for
preventing edge crossings, which I found interesting. 

Citation:  
Doantam Phan, Ling Xiao, R. Yeh and P. Hanrahan, "Flow map layout," IEEE Symposium on Information Visualization, 2005. INFOVIS 2005., 2005, pp. 219-224, doi: 10.1109/INFVIS.2005.1532150.
