Seattle Band Map Redesign
===================

Susanne Hsu, Chase Wu {sueshoe, chenhung}@uw.edu

We began the project by discussing design ideas with out sponsor, Noah Illinsky. Unfortunately, the data to implement
those ideas was not available so we had to rethink and scope down our idea to a proof of concept. We
did research into numerous different techniques for visualizing large networks, looked at many examples of music
visualizations, and spent a fair amount of time looking into sources for additional data.

We worked together on mockups for design ideas, and narrowing in on what type of metadata we wanted to collect. After deciding on a design, Chase went through multiple iterations of the force-directed graph to find the best layout, and dealt with various data quality issues along the way. Susanne was responsible for data collection and preparation, the poster and the paper. Chase built the visualization, including coming up with the equation to calculate the force between the nodes and adding all the interactvity. 

Parts of the design (the filters) are still under construction but we present a proof of concept for a new way to experience and explore the Seattle Band Map.

____________
![Overview] (https://raw.githubusercontent.com/CSE512-14W/fp-sueshoe-chenhung/gh-pages/summary.png)

Paper Abstract: We propose a redesign of the Seattle Band Map (seattlebandmap.com), a visualization of crowd-sourced data about Pacific Northwest bands and the connections between them.  The current visualization is difficult to navigate and is not organized in a way that supports exploration or discovery. Our redesign began by rethinking the process of how users explore the graph. We focused on clustering the bands in meaningful ways to generate points of interest on the graph, adding interaction to guide the exploration experience, and enhancing the dataset to create a rich, multimedia experience. We created a proof of concept that allows users to listen to audio samples, filter bands by date range or genre, and view relationships between bands based on different characteristics. For our project, we used a subset of 521 bands. 

Many music discovery and artist collaboration visualizations effectively reduce large networks by having the user input a band or song and generating a graph of related data points. Rather than having the user input a starting point, we use the shape of the network to prompt exploration and allow for broader discovery. This challenged us to find new ways to organize the data and to give users enough control to navigate the global view as well as identify and focus in on points or areas of interest. 

[Poster](https://raw.githubusercontent.com/CSE512-14W/fp-sueshoe-chenhung/gh-pages/final/poster-sueshoe-chenhung.png),
[Paper](https://github.com/CSE512-14W/fp-sueshoe-chenhung/blob/gh-pages/final/paper-sueshoe-chenhung.pdf)

## Running Instructions

Our visualization can be viewed at http://cse512-14w.github.io/fp-sueshoe-chenhung/
