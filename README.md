# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

--------------------------------------------------------------------------------

Definition of little-o:
$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

Definition of big-O:
$f(n)\in O(g(n) \iff \exists c, n_0, \forall n\ge n_0: f(n) < c g(n)$

These two definitions are fairly similar however there is a key difference.  Little-o uses for all constants "c" while big-O uses there exists a constant "c" so only one constant c needs to exist for the function f(n) to be in big-O

Proof:

Assume that a function $f(n)$ belongs to $o(g(n))$ if for all positive constants, c, there exists an $n_0$ such that for all $n \ge n_0$: $f(n) < c g(n)$

Then since the definition states that a function $f(n)$ belongs to $O(g(n))$ if there exists _any_ constant $c$ it follows that if a function $f(n)$ is apart of $o(n)$ then it is also apart of $O(g(n))$


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice




