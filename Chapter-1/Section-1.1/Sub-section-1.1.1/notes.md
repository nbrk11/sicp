# Notes

## Quick notes

Core mechanisms of programming languages:
- primitive expressions
- combination of primitives into compound
- abstraction

*Note: procedure ~ data*

Primitives can be combined by simple operators to form compound expression

*Note: to display something on screen **(display (text))** can be used*

Regardless of complexity of expressions the interpreter always runs a *read-eval-print loop* (REPL)

Scheme offers primitive procedures such ass +, -, * and /.
For all procedures Scheme (and Lisp overall) uses a prefix notation, which means, that + procedure will look like this:
```Scheme
(+ 34 35)
```

The compound expressions can be easily nested and there is no maximum depth to it (apart from the degrading readability):
```Scheme
(- (+ (* 3 2) (- 15 7)) (/ 8 4))
```
