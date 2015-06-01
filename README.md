# 2000-2015 HPCA/ISCA/MICRO Co-author Graph

## Description

This network graph shows the co-author relationships between researchers who published papers in top conferences in the field of computer architecture. Each node represents an author, and a tie between two authors represents a co-author relationship: that is, a tie is present only on the graph if two authors' names appear in the same publication . The nodes are positioned according to a force-directed algorithm to move highly connected nodes close together and less connected nodes further apart. The colours represent different communities found by a standard community detection algorithm.<br/>

## Data and Visualization

Data was collected from DBLP dataset and laid out using R and Gephi. The interactive display is created with the Sigma.js library, JavaScipt, and CSS based on the template provided by the Oxford Internet Institure. The visualization is part of the UCLA CS246: Web Information Management project to visualize the co-author graph of computer architecture research.<br/>Please note that this is an experimental visualization that may not work on all browsers. It has been tested to work on Firefox 12, Chrome 18, Android Ice Cream Sandwich and Jelly Bean, and iPad 2.<br/>The data was collected by Diyu Zhou and Jiayao Li and the visualization produced by <a href=\"http://www.cs.ucla.edu/~haoyc\">Yuchen Hao</a>.

The following link showcases the visualization effect. <br/>
http://www.cs.ucla.edu/~haoyc/coauthor-vis/

Template provided by InteractiveVis project
http://blogs.oii.ox.ac.uk/vis/ <br/>
https://github.com/oxfordinternetinstitute/InteractiveVis/

