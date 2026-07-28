# Notes

## Quick notes

In LISP compound procedures can be created with *define* keyword:
```Scheme
(define (<name> <paratemers>)
    <body>)
```

With this a **square** procedure can be expresses as this:
```Scheme
(define (square x) (* x x))
```

Than defined procedures can be used in another procedure bodies:
```Scheme
(define (sum-of-squares x y)
    (+ (square x) (square y)))
```
