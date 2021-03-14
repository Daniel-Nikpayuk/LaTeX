Division Optimization
=====================

A brief survey on the math required to computationally optimize general *long division* with arbitrary radix.

This work is based from Knuth's **The Art of Computer Programming Volume 2, Chapter 4---Arithmetic, 4.3.1 The Classical Algorithms**.

Why redo what he's already done? Several reasons:

1. Knuth's book is from the '70s and he uses some old unreadable assembly language in his examples. This needs updating.
1. Knuth's book isn't free and it is surprisingly hard to find his proof or frankly any proof of the division algorithm
as a quick reference, without actually physically going down to a university library and accessing a physical copy.
1. Although Knuth outlines the division algorithm, he gives only partial proofs, and in my own opinion his proofs are ad-hoc:
Math requires rigour, especially when it's used for something as low-level and ubiquitously important as computer division.
As far as rigour goes, I myself also prefer pedagogical narratives when possible. There's no point in learning a proof if
you can't develop a skill-set from it---reinterpreting the logical tactics in a generic way to apply them in other contexts.
Respectfully, Knuth's proofs are flashy and make him seem brilliant (which he is), but don't do much for the rest of us.
1. Continuing from the previous reason, though division is taken for granted these days, learning the subtleties of how it
works improves ones general ability. For me, this makes me more capable in the long run, better able to serve my community.

Regarding copyright: As I was dissatisfied with Knuth's proof, I started from scratch. I doubt the optimization strategy itself
is copyrighted, and the proof I present is my own original work---though it does still use his logical derivations, only adapted
and rewritten for my own context.

I learned much about inequality manipulation in the process I'm pleased to say. I knew some from *real analysis* but as it turns out
*number theoretic* inequality arithmetic is subtly different and has a few tricks of its own that a real analyst might want to know.

