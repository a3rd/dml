# Data Model

## Nodes

NODE - DATA
nodeA
nodeB
lconn
rconn
xch
ych

NODES - JSON
id
exp[1:5]
shape
color
width
height
parentNode
imagePath
hideLabel
x
y

[NODE - DATA| nodeA; nodeB; lconn; rconn; xch; ych]-[NODES - JSON|id;exp(1..5);shape;color;width;height;parentNode;imagePath;hideLabel;x;y],

## Edges


EDGE - DATA
edgeAStyle
edgeBStyle
edgeALabel
edgeBLabel
lineStyle
lineLabel

EDGES - JSON
id1
id2
color
width
type
hideLabel

[EDGE - DATA|edgeAStyle;edgeBStyle;edgeALabel;edgeBLabel;lineStyle;lineLabel]-[EDGE - JSON|id1;id2;color;width;type;hideLabel]





