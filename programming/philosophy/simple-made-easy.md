## Simple Made Easy
[Reference](https://www.infoq.com/presentations/Simple-Made-Easy)

- "Easy" means approachable. "Complex" means being intertwined, being tied together.
- What matters in software: can the software do what it is supposed to do? Can we rely on it? Can problems be fixed along the way? Can requirements change over time?
- Benefits of simplicity: ease of understanding, ease of change, ease of debugging, flexibility.
- Complex constructs: state, object, methods, syntax, inheritance, switch/matching, vars, imperative loops, actors, conditionals.
- Simple constructs: values, functions, namespaces, data, polymorphism, managed refs, set functions, queues, declarative data manipulation, rules, consistency.
- Build simple systems by:
  - Abstracting: design by answering questions related to what, who, when, where, why, and how.
  - Choosing constructs that generate simple artifacts.
  - Simplify by encapsulation.
- Simple does not mean one of a kind. An interface does not have to have only one method to be simple. *Cardinality does not matter, what's important is to have interleaving of issues.*
- Easy: being near to understanding.
- All that is new is somewhat unfamiliar. Do not avoid it even if it is harder to grasp at at first.
- *Many times, developers say about some that is simple, but they mean easy, because  they mean it is something they are familiar with.*
- When evolving a system, making it more extensible and dynamic, it may become harder to understand and decide if it is correct.
- If one chooses easiness, things move fast but accumulated complexity will kill the project over time. If simplicity is chosen, the project starts slower because one has to think things over.
- We can't suddenly change our brain to grasp something complex. We need to simplify complexity so we can handle it.
- Constructs that generate complex artifacts
  - State: everything it touches
  - Object - state, identity, value
  - Methods - function and state, namespaces
  - Syntax - meaning, order
  - Inheritance - types
  - Switch/matching - multiple who/what pairs
  - Vars - value, time
  - Imperative loops - what/who
  - Actors - what/who
  - ORM - OMG
- Constructs that generate simpler artifacts
  - Values - use final, persistent collections
  - Functions - use stateless methods
  - Namespaces - use a language with good support for namespaces
  - Data - maps, arrays, sets, XML, JSON
  - Polymorphism - through protocols, type classes
  - Managed refs - Clojure, Haskell
  - Set functions - via libraries
  - Queues - via libraries
  - Declarative data manipulation - via SQL, LINQ, Datalog
  - Rules - via libraries or natively in Prolog