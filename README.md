# Cognitive Theoretic AI

## Principles

- parents have children
- the best children are absorbed into a new parent and the process repeats
- concepts are embeddings
- there is gravity between them
- new concepts are formed if an input embedding does not match an existing concept
- the graph grows with unbounded fractal complexity
- operators are nodes on the graph
- maximize survival
- use gradient of survival proxy to determine action selection
- not linear hierarchy, instead some nodes stay on or off for longer durations before changing
- try to make it work with binary for efficiency

## Algorithm

- a node matches a set of free or bound variables
  - binary doesn't distinguish between free and bound variables
  - currently we have to explicity set if it is discreet or free
- subgraphs of more than one neighbor ring can be matched via hierarchical recursion

## Algo 2

