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
$f(n)\in O(g(n) \iff \exists c, n_0, \forall n\ge n_0: f(n) \leq c g(n)$

These two definitions are fairly similar however there are a couple differences.  First, Little-o uses $\forall c>0$ while big-O uses $/exists c$ so only one constant c needs to exist for the function f(n) to be in big-O.  Second, within little-O we have $f(n) < c g(n)$ while in big-O has $f(n) \leq c g(n)$ which just says that while in little-o f(n) must by srictly less than cg(n) in big-O it can also equal cg(n)

Proof:

Assume that a function $f(n)$ belongs to $o(g(n))$ if $\forall c>0$, $\exists$ an $n_0$ such that $\forall n \ge n_0$: $f(n) < c g(n)$

Then since the definition states that a function $f(n)$ belongs to $O(g(n))$ if $\exists c$ it follows that if a function $f(n)$ is apart of $o(n)$ then it is also apart of $O(g(n))$


I talked with Ali in lab and I had my big-O definition slightly off

I talked with Ali again because I was confused on how to write something 9/25

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice




