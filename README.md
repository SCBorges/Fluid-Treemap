## Fluid Treemap Interactions ##

There has been significant work on interactive systems for analyzing hierarchical data using treemap visualizations, and much of it has focused on advanced filtering and querying. Less work has been done on developing more intuitive interactions that allow users to more fluidly browse the data shown by treemaps. We present two techniques that leverage direct manipulation to help users compare nodes and investigate hierarchy relationships. While dragging a node above others, users receive immediate visual feedback about the difference between the dragged node and the nodes below. This allows efficient investigation of relationships for a number of target regions. The second technique, inspired by relief shearing, aids users in understanding hierarchical relationships in a treemap. When dragging a region, the levels of the treemap shear to better show the depth and groupings of the elements. We have conducted a preliminary user study to evaluate these ideas, and its analysis suggests possibilities for future research.

### Example ###

An [example](https://scborges.github.io/Fluid-Treemap/) is available. Currently, drag comparisons work by dragging a node across other nodes. To enable shearing, hold the mouse until the parent node becomes padded. To shear larger regions, hold the mouse until the region is padded. Then drag to shear.

### Video ###

A short [video](https://scborges.github.io/Fluid-Treemap/video.mp4) is also available.
