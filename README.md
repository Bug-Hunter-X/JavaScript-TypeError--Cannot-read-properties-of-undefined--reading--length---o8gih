# JavaScript TypeError Bug

This repository demonstrates a common JavaScript error: a TypeError when attempting to access the 'length' property of an undefined variable.  The bug and its solution are provided.

## Bug Description

The `foo` function attempts to return the length of an input. If the input is `null`, it correctly handles this case. However, if the input is `undefined`, it throws a TypeError because `undefined` does not have a 'length' property. 

## Solution

The solution adds an explicit check for `undefined` before attempting to access the `length` property.