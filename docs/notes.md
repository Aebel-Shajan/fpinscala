

## 1: What is functional programming?

* A function has a side effect if it does something other than simply return a result
* A function f with input type A and output type B (written in Scala as a single type: A => B, pronounced “A to B” or “A arrow B”) is a computation that relates every value a of type A to exactly one value b of type B such that b is determined solely by the value of a.


## 2: Getting started with functional programming in Scala
* The object keyword creates a new singleton type, which is like a class that only has a single named instance.
* (signature) (=) (definition)
* Use `:load` to load package into repl
* We can bring all of an object’s (nonprivate) members into scope by using the underscore syntax: `import MyModule._`
* we can define functions inside any block, including within another function definition.
* We can write while loops by hand in Scala, but it’s rarely necessary and considered bad form since it hinders good compositional style.
