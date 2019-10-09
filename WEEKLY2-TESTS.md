# Weekly Assignment 2 Test Cases#


## Testing Pattern-to-list functions
  (Credit Troy)

```"$PatternToList" (TuplePat([VariablePat "x", VariablePat "y"]))```

Returns  ``-> ["x", "y"]``



`"Your Pattern To list function" (TuplePat([TuplePat([VariablePat "x", VariablePat "y"]), TuplePat([VariablePat "x", VariablePat "z"])]))`

`- > ["x", "y", "x", "z"]`

# checkPat TESTS #

  `checkPat (TuplePat([TuplePat([VariablePat "x", VariablePat "y"]), TuplePat([VariablePat "x", VariablePat "z"])]))`

   `- > False`

   (Credit Troy)




# map TESTS  #

`match (Constructor("Square", Tuple[Constant 5, Constant 10]), ConstructorPat("Square", TuplePat([VariablePat "x", VariablePat "y"])))`

`-> Just [("x", Constant 5),("y", Constant 10)]`

`match (Tuple[Constant 6, Constant 8], TuplePat([VariablePat "x", VariablePat "y"])) `

`-> Just[("x",Constant 6), ("y",Constant 8)]`

(Both credit to Troy)





-- Markdown by Joseph --
