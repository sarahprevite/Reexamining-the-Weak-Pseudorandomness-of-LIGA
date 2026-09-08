# Reexamining-the-Weak-Pseudorandomness-of-LIGA
The Lattice Isomorphism Problem (LIP) has gained significant attention in recent years. The notable
development of the first LIP-based digital signature scheme HAWK attracted widespread interest, and was
a top candidate for NIST standardization. Unfortunately, HAWK suffered a recent security breach
that halves the keyspace, found by Claude. While the weakness in HAWK had nothing to do with
the underlying hard lattice problem, the exceeding subtlety of the loophole illustrates the importance of
cross-examining work carefully.
Bencina et al. defined LIP as a group action under equivalent quadratic forms , called the Lattice
Isomorphism Group Action (LIGA). Bencina proved that LIGA is not weakly pseudorandom or weakly
unpredictable under some constraints, emphasizing its theoretical cryptographic interest in exploring the
overlap between coding theory, lattice cryptography, and algebraic concepts. Expanding upon Bencina’s
work, Budroni et al. sought to tighten the bounds on the weak pseudorandomness and unpredictability of
LIGA with significantly tighter bounds and fewer constraints [3]. Budroni focuses on showing that LIGA is
neither 2−weakly pseudorandom nor 3−weakly unpredictable. The consequences of such results are that,
among other things, the LIP scheme developed by Khuc et al. lacks linkable anonymity.
This paper offers a converse to Lemma 1 that alters the proof of Theorem 1 in Budroni’s work and leaves
the 2−weakly pseudorandomness of LIGA over the integers in question. The algorithm is explained, with
the associated Github provided. The converse of Lemma 1 given generalizes the results over a broader
ring than the integers. In this work, we prove following statements:

• The converse of Lemma 1 is false via counterexample.

• As a result, Theorem 1 remains unproven.

• The converse of Lemma 1 generalized beyond integer rings is (almost) true.


Original paper: https://scholar.google.com/citations?view_op=view_citation&hl=en&user=bQUhnPgAAAAJ&citation_for_view=bQUhnPgAAAAJ:M3ejUd6NZC8C
