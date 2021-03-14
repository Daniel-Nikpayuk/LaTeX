Stratified-Powerset-Part-One-
=============================

An article on the mathematical foundations of computing science data structures.

As the title notes, this is part one. Part two will deal with the real motivation behind all of this:
I have long planned to code (likely in C++ template language) a prototyping data structure which
deep copies the content (data) and shallow copies the structure (filters). Such shallow filters
allow for reuse and rapid building up of arbitrary data structures with minimal cost to memory---as
the content is shared.

Given its intended universal nature (to simulate all possible data structures), it will by nature also possess
(unoptimized) database behaviours and properties (having to do with read/write accessibility) and will thus likely need
to maintain a single optimization toward a record keeping history so that filters can be updated when resyncing with the
source---if the source is like a database, it will be written to, not just read: Filters are paths of accessibilty;
pointers which need to be updated if the structure itself has changed.

The above is kind of abstract, but will make more sense in the second part.

Finally, when I wrote this originally back in June, I only shortly after took my first course on
Machine Learning (Andrew Ng's Stanford Machine Learning MOOC). After seeing how neural networks
work (and further studying deep networks on my own) do I see a certain parallel between neural nets
and this prototyping data structure I have in mind. Neural networks with their emphasis on matrices
are the continuous version while this universal medium of all possible data structures is the discrete
version. I will keep this in mind in my explorations, and if my research turns up any relations to machine learning
I will post it here on my GitHub account.

Thank you.
