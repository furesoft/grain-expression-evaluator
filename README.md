# Grain Expression Evaluator

An engine to evaluate mathematical expressions written in Grain

## Usage

```grain
Scope.setVariable("n", 5, Evaluator.rootScope)
Evaluator.eval("power(2,6) + pi - n")
``` 

## Defining functions

```grain
Evaluator.eval("f(n) = (n * (n - 1)) / 2")
```