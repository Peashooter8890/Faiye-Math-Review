# Fundamentals Elements of Basic Mathematics - Sets

This is the review of the very basic fundamentals of mathematics. Whether or not you have already mastered this or forgot some of the basics, it's probably a good short read so that we are on the same page. 

### Introduction to the Most Basic Element of Mathematics

The most basic elements of mathematics is arguably a set, denoted by brackets $\{\}$.

A set is a collection of mathematical objects. Anything can be a set. The air is a set of molecules, human is a set of various human parts which are in turn sets of even smaller components such as atoms. A list of groceries can be a set. Basically, the lesson is that you should think of everything as a set. 

As obvious as it is, sets can be represented using symbols. Suppose that there exists a set S given that S = \{1,2,3\}. This means that $S$ is a set that contains the three positive integers 1, 2, and 3.

One important fact is that sets cannot have duplicates. \{2,2\} = \{2\}. More on this on the set theory textbook that we will do in the future.

### Set Membership

Nothing in mathematics or even the world can truly be proven (are we in a simulation? Why is 1 + 1 = 2? This can't be "proven", according to philosophy). This means that everything in math has to come from axioms at some point. Axioms are rules that people agree upon, mostly because it seems to "make sense". We don't question axioms or try to prove it, unless that axiom was derived from other axioms (in which case, we can probably prove it). In general, rules derived from other axioms are called theorems, or smaller parts are called lemmas, or even smaller truths are called propositions, so on.

Axiomatically, since a set can exist and it is a collection of mathematical objects, the objects inside a set **belong** to that set. Recall the set S = \{1,2,3\}. Based on the axiom, it follows that $1$ belongs to set $S$. 

Mathematically, this is expressed as 

$1 \in S$.

Which is read "1 belongs to S", or "1 in S", etc. 

This is called a set membership symbol. 

### Arbitrary Membership

The definition of "arbitrary" can be best expressed with the word "something". We don't know what the value of the arbitrary thing is, but often times we have a set of rules that help us understand what it *might* be. 

For children, lots of math questions come in the following form such as if $x + 4 = 8$, what is $x$? 

In this case $x$ is not arbitrary since it's $4$. We clearly know what $x$ is, and it's not anonymous.

If the equation, however, was simply $x = x$, then $x$ is arbitrary since it can be 1, 2, 3, 4, 5, or pretty much anything that follows the rule "I am equal to myself".

If we define an arbitrary variable $s$, then we can establish an arbitrary membership. This can be done as:

$s \in S$. 

Suppose again that S = \{1,2,3\}. This means that we can infer that the value of $s$ is either 1, 2, or 3. We will never know which one the value of $s$ is and we don't **need** to know. We just know that $s$ is an anonymous member of set $S$. Later on we will be using this in beautiful ways to prove universal things.

### Set Operations

Suppose we have two sets $S_{1}$=\{1,2,3\} and $S_{2}$= \{3,4,5\}. 

The **union** of $S_1$ and $S_2$, denoted as $S_{1} \cup S_2$, combines the elements of both of the sets being united. Recall that sets cannot have duplicates. Therefore the union of $S_1$ and $S_2$ is \{1,2,3,4,5\}. 

The **intersection** of $S_1$ and $S_2$, denoted as $S_{1} \cap S_{2}$ only picks intersecting, or common elements from the intersecting sets. Notice how $3 \in S_{1} \hspace{0.15cm}\text{ and }\hspace{0.15cm} 3 \in S_2$, but no other elements. Therefore the intersection of $S_1$ and $S_2$ is \{3\}. 

The **difference** of $S_1$ and $S_2$ is all the elements that are in $S_1$ that is not in $S_2$. Sometimes it can be represented as $S_{1}-S_{2}$ while sometimes the formal notation is $S_{1}\setminus S_{2}$. We will stick to the more familiar subtraction sign for our example. 

$S_{1}-S_{2}$ = \{1,2\} and $S_{2}-S_{1}$ = \{4,5\}. 

### Subsets

Suppose that A = \{1,2,3\} and B = \{1,2\}.

All elements of $B$ are in $A$. 
This is expressed by saying that $B$ is a **subset** of $A$, denoted as $B \subseteq A$. 

Note that all elements are subsets of itself. All elements of **B** are in **B**, so $B \subseteq B$. Because of this, the strict subset sign $\subset$ exists - it only applies to sets that are subsets of something but not themselves. 

### Common Number Sets

Suppose that we talk about numbers. Because mathematics deals with different types of numbers, it quickly becomes pretty important to understand what type of numbers we are looking at. Numbers can be complex, real, rational, integers, etc. 

$\mathbb{R}$ is the set of all real numbers. Anything that's not complex or imaginary with $i$ is here.

$\mathbb{Q}$ is the set of all rational numbers, aka numbers that can be expressed as ratios of two integers.

$\mathbb{Z}$ is the set of all integers, positive AND negative. 

$\mathbb{N}$ is the set of all natural numbers, aka positive integers. It sparks great controversy and debate on whether or not $0 \in \mathbb{N}$ because $0$ is neither positive nor negative. 

Using the concept of subsets, it follows that $\mathbb{N} \subseteq \mathbb{Z} \subseteq \mathbb{Q} \subseteq \mathbb{R}$. 

Note that both irrational and imaginary sets can use the same symbol depending on the author, since both start with "I". If we use the fancy I symbol to represent Imaginary sets, Irrational numbers can be represented using $\mathbb{R} - \mathbb{Q}$. 

### Problem Sets

1. Rewrite \{4,5,5,5\} in the simplest form.
2. What is \{11,12\} $\cup$ \{1,2,3,4 ... 10\}? (The ... sign means that it is a natural series. While the series hasn't been rigorously defined, it is informally assumed that it means it's an integer sequence, so 5,6,7,8,9,10.)
3. What is \{100,99,98,...0\} $\cap$ \{-10,-9, ... 5\}? 
4. Construct any set whose subset is \{3,4\}.
5. Suppose that there exists two sets A = \{4,5\} and B = \{4,5\}.
	1. What is $A \cup B$?
	2. What is $A \cap B$? 
6. Explain why the statement $1 \in \mathbb{R} - \mathbb{Z}$ is false.
7. Explain why $\mathbb{Z} \not\subset \mathbb{N}$. 
8. Explain why the integer $8$ is a member of $\mathbb{Q}$ (hint: rewrite $8$. )

# Fundamentals Elements of Basic Mathematics - Logic

### Notation

$\land$ is the sign that says "and"

$\lor$ is the sign that says "or" (or is often inclusive, meaning it can either be one, the other, or both)

$\neg$ is the sign that says "not"

The three statements above are good for pure logic, but in general using english is better. For the "not" symbol, a more common example will be $\ne, \not\subset,$ etc. The main reason we would need to know the three above symbols would be when we are studying pure mathematical logic, but since logic is the foundations of math, it's good to know.

$\implies$ is the sign that says "implies"

$\iff$ is like "implies", except that both sides of the expression imply each other. 

$\exists$ means "there exists"

$\forall$ means "for all"

Again, depending on the context, these might be better expressed in english. But again, it's still good to know them.

### Problem Sets

1. Re-express $\neg (P \land Q)$ using the distributive property and explain why the distributive property works in this context. (Recall that the distributive property turns $5(4+5)$ into $5\*4 + 5\*5 = 45$.)
2. Explain why $(P \land Q) \land K$ is the same as $P \land (Q \land K)$. 
3. Given the expression $(\neg P \lor P) \land ((Q \lor P) \land (\neg P \lor \neg Q))$, considering that the "or" sign is inclusive (both can be true), explain why both $Q$ and $P$ cannot be true or false at the same time.
4. Consider the statement "$\forall n \in \mathbb{N}, \hspace{0.15cm}\text{given that}\hspace{0.15cm} n \ne 0, -n < 0$". 
	1. Explain why the statement is true or false.
	2. Is it true or false for $\forall z \in \mathbb{Z}$? Explain your reasoning.
	3. Is it true or false for $\exists r \in \mathbb{R}$?
5. Suppose that $x = 5$. 
	1. Does $x = 5 \implies x \in \mathbb{Z}$? 
	2. Does $x=5 \iff x \in \mathbb{Z}$? 
6. Given that $4 < x < 5$, show that $!\exists x \in \mathbb{Z}$ ($!\exists$ is the preferred way of saying $\neg \exists$, meaning "does not exist")
7. Suppose that there exists two sets $A$ and $B$ and $A \subseteq B$. Explain why the statement "$\forall a \in A (a \in B)$" is true.

# Basic Mathematical Techniques

This is the final and hardest section of this review, but also the most important. Make sure to pay a lot of attention here if you don't remember all of these.

### Direct Proofs

A **direct proof** involves proving a statement with sequences of statements. This is basically the most basic form of proof that can exist. It follows the style "This is true, and so this is true. Then because this is true, this is not true, therefore this is true", or something like that.

Here is an example.

Suppose $a$ and $b$ are real numbers. Prove that if $0 < a < b$ then $a^{2} < b^2$. 

Proof. Suppose that $0 < a < b$. Now multiply all sides of the inequality by $a$ to get $0 < a^{2} < ab$. 
Then multiply all sides of the original inequality by $b$ to get $0 < ab < b^2$. $ab < b^2$ and $a^{2}< ab$, so $0 < a^{2} < ab < b^2$, hence it follows that $a^{2} < b^2$. 

### Contrapositive Proofs

A **contrapositive proof** involves logically "flipping" the statement and proving it. Here is an example:

Suppose that $a, b,$ and $c$ are real numbers and $a > b$. Prove that f $ac \le bc$ then $c \le 0$. 

Before delving into the proof, let's look at the steps needed.

Contrapositive proofs negate both sides of the expression to flip it. The negation of $ac \le bc$ is $ac > bc$. The negation of $c \le 0$ is $c > 0$. The reason we aren't negating the $a > b$ part is because it's not part of the expression, it's just a given "fact". The expression here is the construct $ac \le bc \implies c \le 0$, in which we have flipped both of them to keep the original meaning.

It works in a similar way where multiplying both sides of an equation by $-1$ makes it still equal. 

Our new construct can be represented as $ac > bc \implies c > 0$.

Now, why would we ever do this? In this case, the contrapositive removes the "equal" sign from the $\le$ and $\ge$ signs, so our expression only has $<$ or $>$ signs. This makes it easier to prove.

Now moving onto the actual proof.

Proof. Assume the contrapositive and suppose $c > 0$. Since $a > b$, multiplying both sides of the inequality by $c$ gives $ac > bc$. Since the contrapositive assumes $ac > bc$ by negation, the proof is complete.

### Contradiction Proofs

A **contradiction** proof involves assuming the opposite of what you are trying to prove, and then naturally coming to a contradiction of mathematical axioms. If mathematical axioms are contradicted, it is wrong - so proving that the wrong side of an argument is wrong proves yours.

Now, for an example (though a bit more informal and less rigorous just to make it simple).

Prove that flipping a fraction will not always result in a different outcome. Again, "flipping a fraction" is not rigorous but it is a simple understandable concept.

Proof. Assume that flipping a fraction always results in a different outcome. Now consider the fraction $\frac{5}{5}$. Flipping it gives us $\frac{5}{5}$, and $\frac{5}{5}=\frac{5}{5}$ which is not a different outcome, contradicting our statement. Therefore, flipping a fraction will not always result in a different outcome.

### Induction Proofs

An **induction** proof is arguably the most beautiful proof that has been mentioned so far.

It first proves that a statement is true for a number and anything less than that number. This is called the base case.

It then proves that the statement is true for n+1. This effectively proves that it is true for all numbers in intervals of 1. Since $n+1$ is arbitrary, it can be any number up to infinity. 

This technique is mostly used for $\mathbb{N}$. This is because $\mathbb{N}$ only contains positive integers, so the interval is in 1, hence $n+1$ works. If it was a non-integer real number, then it would be in infinite intervals ex. $5.5, 5.55, 5.55, 5.5555, 5.5555555555$, so on. It's also because $\mathbb{N}$ starts with the number $0$ or $1$. If we just prove that it is true for $0$ or $1$ (this is the base case) and then prove that it's true for $n+1$, we prove it for ALL members of the natural numbers. 

After showing that something is true for the base case, the assumption that it is true for $n+1$ is called the inductive hypothesis. The goal of induction proofs is to prove the inductive hypothesis.

The reason this proof is so beautiful is because it is recursive. $n+1$ is a chain that goes on infinitely, because if $0$ is true, then it's possible that $n=0$, and if $n+1$ is true then $0+1 = 1$ is true, so $n$ can now equal $1$. Then $n+1 = 2$ so it is true for $2$. Recursion is beautiful.

To digress a bit, this is an important example of the mathematical concept of what can be called a sort of a "universal proof". Here is a similar example that uses an arbitrary variable to prove a universal statement.

Choose some $a \in A$. If $a \in B$, then $A \subseteq B$. 

We are choosing an arbitrary variable here called $a$. If an arbitrary variable from $A$ belongs to $B$, that means ANYTHING from A can belong to B since $a$ can be anything from $A$ by definition of "arbitrary". Thus, all elements from $A$ belongs to $B$. This follows a similar spirit from recursion.

Now, back to proof by induction. The following is an example.

Prove that the sum of the first $n$ natural numbers is $\frac{n(n+1)}{2}$. Recall that this is the famous formula for $\sum_{n=0}^{\infty}n = \frac{n(n+1)}{2}$. The $\sum$ sign is a "for loop" from programming, in this case it starts with $n=0$ and moves up infinitely in intervals of 1. 

Proof. Suppose $n = 0$, then $\frac{0(0+1)}{2}= 0$ so the statement holds true. Since it is debatable whether $0 \in \mathbb{N}$, start with $n=1$ also. $\frac{1(1+1)}{2} = 1$ so the statement holds. Now assume the inductive hypothesis. Substitute $n+1$ into n and we get $\frac{(n+1)((n+1) + 1)}{2} = \frac{(n+1)(n+2)}{2}$. Now, to show that $\frac{n(n+1)}{2} + (n+1) = \frac{(n+1)(n+2)}{2}$. We first algebraically convert $(n+1)$ into $\frac{2(n+1)}{2}$ and merge it with $\frac{n(n+1)}{2}$, giving us $\frac{n(n+1) + 2(n+1)}{2}$. The two pairs of $(n+1)$ can then algebraically be factored into $\frac{(n+1)(n+2)}{2}$, which completes the proof. 

### Problem Sets

These can be challenging problem sets if you aren't too familiar with proofs or if it's been a while. Feel free to ask for help and try your best. 

1. Given that $n \in \mathbb{Z}$, 
		1. Prove that the sum of two even numbers is always even. (Hint: an even number can be expressed in the form $2n$.)
		2. Prove that the square of an odd number is always odd. (Hint: an odd number can be expressed in the form $2n + 1$.)
2. $\bigcup A$ denotes the union of ALL sets inside $A$. So ex. if A = \{\{5,4\},\{4,3\}\} then $\bigcup$ A = \{5,4\} $\cup$ \{4,3\} = \{5,4,3\}. Prove that every member of $\bigcup A$ is a subset of $A$. (Hint: use the technique where you choose an arbitrary variable and show that the arbitrary variable belongs to a set, hence "universally" proving that all members belong to a set.)
3. Using proof by contradiction, prove that if $x \in \mathbb{Q}$, there can be no smallest $x$.
4. Using proof by contrapositive, prove that if a number is divisible by $2$, a number is divisible by $4$. 
5. Using proof by induction, prove that for all $n \in \mathbb{N}$, $2^{n} > n$. Assume that the natural numbers start with $1$. (Hint: after you construct an equality for the inductive hypothesis, try to prove that $2k \ge k+1$  for $k \ge 1$, then use that fact to continue on the proof.)
6. Prove that there are infinitely many prime numbers. This is a hard problem, so we will be giving an extensive starting point. We will be attempting proof by contradiction, hence first assuming that there are finitely many prime numbers. Suppose that there are infinitely many prime numbers, starting from $p1$ and going until $pn$ where $n$ is a finite integer. Suppose that $m$ is a product of all prime numbers plus 1, aka $m = p1p2p3 ... p_{n}+ 1$). A prime number can only be divisible by itself or 1 - so a prime number can't be divisible by another prime number that's not 1 or itself. Observe how if you try to divide $m$ by a prime number, there is always a remainder of 1. Use this fact to continue the proof and finish it, exploring the construct $m$. (The goal is to come to a contradiction that there are finitely many prime numbers.)
