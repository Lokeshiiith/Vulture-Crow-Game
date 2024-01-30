Q1.
 1. It contains 3 files and 1 folder 
 2. Used d3.js so to work it offline d3 package is downloaded and imported in script.
 3. Used graph.js file to make a class Graph, which allow me to use constructor and use it same like the c++ data structure.
    It contains addVertex() function, addEdge(), getNeighbours(),printGraph 
    in order to push vertices and edges in adjacency list.
 4. Used event.js file to make EventEmitter class, which allow me to debug when taking a move.
 5. Used index.html where the code runs, for dragging a crow to a certain crows to pit {empty circle on star} , 
    I used area calcultion as only adjacent nodes are to be filled.
 6. Used svg tag to create lines, circles and event onstart_to_drag , during_draggged , when drag_ended ..
 7. Used vanilla.js for tilt
 8. I made changes in rule such as I allow crow to move in star even if all crows not sitted till then .
    I made it to make game as fair otherwise it becomes vulture-biased
 9. I applied colours on dragstarted to adjacent circles where it can able to move.Till now I made them white colour , otherwise it looks bias.
    It can be changed easily to other colours during assessment.   
 



 Q2.
    This doesnot require additional file as it is contained inside the Q1 itself to capture the eventfull drag
    successful  movements . i.e. kill , which crowid sit at which (pit)id i.e. the empty circles .
    note empty 
