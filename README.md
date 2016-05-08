### Try it now at [git.io/math](http://git.io/math)!

-----

The [Formula Compiler](http://git.io/math) is a client-side compiler running on asm.js that finds mathematical formulas (involving only basic arithmetic and summation notation) for arbitrary computable functions written in pseudocode.

Quote from Sam:

> The formulas which the Compiler produces are so complicated that they are utterly useless. The point of this software is to drive a stake into the heart of every assertion that “there is no known formula for (insert familiar function here)”. Of course, there may still be some truth in these statements, but only if new qualifiers are added. For example, it might be true that “there is no known formula for the primes which allows the nth prime to be computed using O(1) arithmetic operations”, or some similar statement, but this is of course a much weaker assertion than “there is no known formula for the nth prime” (which is untrue).

> It is philosophically interesting to note that, although the formulas the compiler produces seem ridiculously over-complicated at first glance, their complexity is only polynomial in terms of the complexity of the user-entered program used to generate them. Program a function using n lines of code and depending on m parameters, and the compiler will spit out a formula whose complexity is O(P(n,m)). (By the complexity of the formula, I mean its complexity as a logical term, not its runtime complexity– its runtime complexity is infinite since it involves infinite series) Here P(n,m) is a fixed polynomial which could be nailed down more exactly by carefully doing the necessary back-substitution on the results produced by the compiler. Of course, none of this should surprise anybody familiar with Kleene’s Normal Form Theorem. To claim any kind of real mathematical progress, I would have to have published the compiler about 80-100 years earlier. Still, it is more explicit than the Normal Form Theorem.
