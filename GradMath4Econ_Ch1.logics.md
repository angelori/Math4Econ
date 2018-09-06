
# Logics

This lecture note is from Prof. Martin Osborne's (University of Toronto) [homepage](https://mjo.osborne.economics.utoronto.ca/index.php/tutorial/index/1/log/t).

## Basics

When making precise arguments, we often need to make conditional statements, like 

&nbsp;&nbsp;&nbsp;&nbsp;*if* the price of output increases *then* a competitive firm increases its output 

or 

&nbsp;&nbsp;&nbsp;&nbsp;*if* the demand for a good is a decreasing function of the price of the good and the supply of the good is an increasing function of the price *then* an increase in supply at every price decreases the equilibrium price.


These statements are instances of the statement

&nbsp;&nbsp;&nbsp;&nbsp;*if* A *then* B,

where A and B stand for statements. We may alternatively write this general statement as 

&nbsp;&nbsp;&nbsp;&nbsp;A *implies* B,

or, using a symbol, as

&nbsp;&nbsp;&nbsp;&nbsp;A $\Rightarrow$ B.

Yet two more ways in which we may write the same statement are

&nbsp;&nbsp;&nbsp;&nbsp;A is a **sufficient condition** for B,

and

&nbsp;&nbsp;&nbsp;&nbsp;B is a **necessary condition** for A.

(Note that B comes first in the second of these two statements!)

Important note: The statement A $\Rightarrow$ B does not make any claim about whether B is true if A is NOT true! It says only that if A is true, then B is true. 
While this point may seem obvious, it is sometimes a source of error, partly because in everyday communication we do not always adhere to the rules of logic. 
For example, when we say "if it's fine tomorrow then let's play tennis" we probably mean both "if it's fine tomorrow then let's play tennis" and "if it's not fine tomorrow then let's not play tennis" (and maybe also "if it's not clear whether the weather is good enough to play tennis tomorrow then I'll call you"). 
When we say "if you listen to the radio at 8 o'clock then you'll know the weather forecast", on the other hand, we do not mean also "if you don't listen to the radio at 8 o'clock then you won't know the weather forecast", because you might listen to the radio at 9 o'clock or check on the web, for example. 
The point is that the rules we use to attach meaning to statements in everyday language are subtle, while the rules we use in logical arguments are absolutely clear: when we make the logical statement "if A then B", that's exactly what we mean—no more, no less.

We may also use the symbol ''$\Leftarrow$'' to mean **"only if"** or "is implied by". Thus

&nbsp;&nbsp;&nbsp;&nbsp;B $\Leftarrow$ A

is equivalent to

&nbsp;&nbsp;&nbsp;&nbsp;A $\Rightarrow$ B.

Finally, the symbol "$\Leftrightarrow$" means "implies and is implied by", or **"if and only if"**. Thus

&nbsp;&nbsp;&nbsp;&nbsp; A $\Leftrightarrow$ B

is equivalent to

&nbsp;&nbsp;&nbsp;&nbsp;A $\Rightarrow$ B and A $\Leftarrow$ B.

If A is a statement, we write the claim that A is not true as

&nbsp;&nbsp;&nbsp;&nbsp;not(A).

Note that

&nbsp;&nbsp;&nbsp;&nbsp;not(not(A)) $\Leftrightarrow$ A.

If A and B are statements, and both are true, we write

&nbsp;&nbsp;&nbsp;&nbsp;A and B,

and if at least one of them is true we write

&nbsp;&nbsp;&nbsp;&nbsp;A or B.

Note, in particular, that writing "A or B" includes the possibility that both statements are true.

## Two rules

### Rule 1

If the statement

&nbsp;&nbsp;&nbsp;&nbsp;A $\Rightarrow$ B

is true, then so too is the statement

&nbsp;&nbsp;&nbsp;&nbsp; (not B) $\Rightarrow$ (not A).

The first statement says that whenever A is true, B is true. Thus if B is false, A must be false—hence the second statement.

### Rule 2

The statement

&nbsp;&nbsp;&nbsp;&nbsp;not(A and B)

is equivalent to the statement

&nbsp;&nbsp;&nbsp;&nbsp;(not A) or (not B).

Note the "or" in the second statement! 
If it is not the case that both A is true and B is true (the first statement), then either A is not true or B is not true.

## Quantifiers

We sometimes wish to make a statement that is true for all values of a variable. 
For example, denoting the total demand for tomatoes at the price p by D(p), it might be true that

$D(p) > 100$ for every price $p$ in the set $S$.

In this statement, "for every price" is a quantifier.
Important note: We may use any symbol for the price in this statement: "p" is a dummy variable. 
After having defined $D(p)$ to be the total demand for tomatoes at the price $p$, for example, we could write

$D(z) > 100$ for every price $z$ in the set $S$.

Given that we just used the notation $p$ for a price, switching to $z$ in this statement is a little odd, BUT there is absolutely nothing wrong with doing so! 
In this simple example, there is no reason to switch notation, but in some more complicated cases a switch is unavoidable (because of a clash with other notation) or convenient. 
The point is that *every* statement of the form

$A(x)$ for *every* $x$ in the set $Y$,

where $x$ is any symbol, has exactly the same content.
Another type of statement we sometimes need to make is

$A(x)$ for *some* $x$ in the set $Y$,

or, equivalently,

there exists $x$ in the set $Y$ such that $A(x)$.

"For some $x$" (alternatively "there exists $x$") is another quantifier, like "for every $x$".


```python

```
