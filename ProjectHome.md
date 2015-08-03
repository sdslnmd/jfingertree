An implementation of 2-3 finger trees in Java, and some collections implemented on top of them.

### Status ###
The finger tree implementation (FTree) is done and fairly well tested.

Still to do:
  * build some Java collections using FTree (like FList that is a RandomAccess List that implements Deque)
  * experiment with Measures and Predicates
  * Currently the middle tree in a deep tree always is eagerly evaluated (Java being a strict language), but maybe it would be a good idea to equip an FTree with an ExecutorService to asynchronously compute expressions yielding middle trees
