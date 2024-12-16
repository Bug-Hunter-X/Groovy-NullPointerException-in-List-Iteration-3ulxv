# Groovy NullPointerException in List Iteration

This repository demonstrates a common NullPointerException in Groovy when working with lists.  The `myMethod` function iterates over a list and prints each element in uppercase. However, if a `null` list is passed, a `NullPointerException` occurs because the `each` method cannot iterate over null.

## Bug
The bug is in `bug.groovy`. The `myMethod` function throws a `NullPointerException` if a `null` List is passed as an argument. 

## Solution
The solution is provided in `bugSolution.groovy`. The solution adds a null check before iterating over the list, preventing the `NullPointerException`. 