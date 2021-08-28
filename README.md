# java-hierarchy-tree-from-list

Create tree, Root Output:

Node [id=1, pid=null, name=One, children=[Node [id=2, pid=1, name=Two, children=[Node [id=3, pid=2, name=Three, children=[]], Node [id=4, pid=2, name=Four, children=[Node [id=5, pid=4, name=Five, children=[]]]]]]]]

List flattening, output:

List size = 5

[Node [id=3, pid=2, name=Three, children=[]], Node [id=4, pid=2, name=Four, children=[]], Node [id=2, pid=1, name=Two, children=[]], Node [id=5, pid=4, name=Five, children=[]], Node [id=1, pid=null, name=One, children=[]]]
