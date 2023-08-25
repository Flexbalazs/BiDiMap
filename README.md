# BiDiMap
Bidirectional Map

Stores key-value pairs in such a way that both sides are keys —that is, both sides form a set, both sides are unique.

Implements the following methods:

 - put(k1, k2) — Inserts an element. If something was already assigned to k1, it will be overwritten. If something was assigned to k2, it also overwrites it.
 - get(k1) — Returns the pair associated with the first key. If it doesn't contain what you are looking for, returns null.
 - getInverse(k2) — Returns the pair associated with the second key. If it doesn't contain what you are looking for, returns null.
 - remove(k1) — Removes the pair associated with the first key.
 - removeInverse(k2) — Removes the pair associated with the second key.
 - getInverse() — Creates a BiDiMap in which the two keys are listed in reverse order.
 - size() — Returns the number of entries.
