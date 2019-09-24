# Generic Trees to use for 1-6 #

## Small Tree with 2 children (Credit Ryan)
```TriNode 1 (TriNode 2 (EmptyNode) (EmptyNode) (EmptyNode)) (TriNode 3 (EmptyNode) (EmptyNode) (EmptyNode)) (EmptyNode)```

## Larger Tree  (Credit Ryan) 
TriNode 1 (TriNode 2 (EmptyNode) (TriNode 7 (EmptyNode) (EmptyNode) (EmptyNode)) (EmptyNode)) (TriNode 3 (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode)) (TriNode 15 (EmptyNode) (EmptyNode) (EmptyNode))) (TriNode 96 (EmptyNode) (TriNode 71 (EmptyNode) (TriNode 33 (EmptyNode) (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode)))



# nodeValue TESTS #


## Big tree (Credit Ryan) 
nodeValue (TriNode 1 (TriNode 2 (EmptyNode) (TriNode 7 (EmptyNode) (EmptyNode) (EmptyNode)) (EmptyNode)) (TriNode 3 (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode)) (TriNode 15 (EmptyNode) (EmptyNode) (EmptyNode))) (TriNode 96 (EmptyNode) (TriNode 71 (EmptyNode) (TriNode 33 (EmptyNode) (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode))) (EmptyNode)) (EmptyNode)))

### Should return 1 (I think?) 




# inOrderMap TESTS #

## Increments all nodes by one  (Credit Ryan)
inOrderMap (+1) (TriNode 1 (TriNode 2 (EmptyNode) (TriNode 7 (EmptyNode) (EmptyNode) (EmptyNode)) (EmptyNode)) (TriNode 3 (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode)) (TriNode 15 (EmptyNode) (EmptyNode) (EmptyNode))) (TriNode 96 (EmptyNode) (TriNode 71 (EmptyNode) (TriNode 33 (EmptyNode) (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode))) (EmptyNode)) (EmptyNode)))

### Sample output: 
TriNode 2 (TriNode 3 EmptyNode (TriNode 8 EmptyNode EmptyNode EmptyNode) EmptyNode) (TriNode 4 EmptyNode (TriNode 7 EmptyNode EmptyNode EmptyNode) (TriNode 16 EmptyNode EmptyNode EmptyNode)) (TriNode 97 EmptyNode (TriNode 72 EmptyNode (TriNode 34 EmptyNode EmptyNode (TriNode 7 EmptyNode EmptyNode EmptyNode)) EmptyNode) EmptyNode)


# preOrderFold TESTS #

## Small adding fold (Credit Declan) 
preOrderFold (+) 0 (TriNode 1 (TriNode 2 EmptyNode EmptyNode EmptyNode) (TriNode 4 EmptyNode EmptyNode EmptyNode) (TriNode 3 EmptyNode EmptyNode EmptyNode))
### Returns 10 

## Larger adding fold (Credit Jacob) 
preOrderFold (+) 0 (TriNode 1 (TriNode 2 (EmptyNode) (TriNode 7 (EmptyNode) (EmptyNode) (EmptyNode)) (EmptyNode)) (TriNode 3 (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode)) (TriNode 15 (EmptyNode) (EmptyNode) (EmptyNode))) (TriNode 96 (EmptyNode) (TriNode 71 (EmptyNode) (TriNode 33 (EmptyNode) (EmptyNode) (TriNode 6 (EmptyNode) (EmptyNode) (EmptyNode))) (EmptyNode)) (EmptyNode)))
### Returns 240






