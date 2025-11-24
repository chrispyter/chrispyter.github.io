---
title: "Facebook Network Analysis"
date: 2024-11-24
---

## Visualizations

### Plot 1: Histogram
This histogram shows the frequency distribution of node degress in Facebook's social network. This shows how many connections, or friends, that every person has in the network. For my design choices, I utilized bar encoding that has node degrees on the x-axis and a count of the nodes on the y-axis. All of the bars are colored blue to make it not too visually overwhelming. For the data transformations, I calculated the node degrees by counting the number of times a node appeared in the edge list.

As for the interactivity, I used hover tooltips, which lets users select a bar and see the number of respective nodes. This allows someone to see exactly how many nodes are within a certain degree range, instead of having to estimate based on the bar's height.
### Plot 2: Scatter Plot  
This scatter plot shows each node's degree category. For my design choices, I used positional encoding with node IDs on the x-axis and the degree values on the y-axis. I also used the Viridis color scheme since it has a wide variety of similar colors that are different in shade, which helps to show similarity but also separation amongst the degree ranges. For the data transformations, I put the degrees into ranges, or binned them, which allowed me to use color coding and effectively group nodes.

## Links
[The Data](https://snap.stanford.edu/data/ego-Facebook.html)
[The Analysis](https://github.com/chrispyter/chrispyter.github.io/blob/main/Workbook.ipynb)
