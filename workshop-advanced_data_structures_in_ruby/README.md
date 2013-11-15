# Advanced Data Structures in Ruby

Most Rubyists reach for core structures to represent their data (e.g. `Array`
and `Hash`). These may be good choices for one-off scripts or basic
applications but most real-world applications would benefit from using more
advanced data structures.

We will start by implementing a singly linked list in Ruby. This will be
followed by a doubly linked list, working our way up to trees, heaps, and
priority queues. [Thread safe](https://github.com/headius/thread_safe) and
persistent data structures will also be covered.

As we implement each of these structures, we will discuss the theoretical
tradeoffs between them and run benchmarks to prove that they perform as
predicted by the theory.
