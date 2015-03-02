### trie

An extremely small and very fast trie implementation. Keys are binary strings, and the span of the trie can be set from 1 to 8.
```c
/* to change trie span, both variables below must be changed */
#define TRIE_SPAN  5 /* trie span */
#define TRIE_LIMIT 32 /* 2 ^ span */
```
A trie with a span of one is essentially a bitwise binary tree, which this lib can be used as.