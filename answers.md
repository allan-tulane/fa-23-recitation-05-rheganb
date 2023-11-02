# CMPS 2200 Recitation 6
## Answers

**Name: Rhegan Barrett**


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt       |      1340         |         826       |  0.616
alice29.txt  |     1,039,367     |      676,374      |  0.651
asyoulik.txt |      876,253      |       606,448     |  0.692
grammar.lsp  |       26,047      |      17,356       |  0.666
fields.c     |       78,050      |       56,206      |  0.720

The ratio of Huffman to fixed-length encoding is almost always 0.6.


- **e.**

If every character had the same frequency, it wouldn't matter which character goes where. They would be placed arbitrarily with each node having a cost of n. Because they have the same frequency and are placed arbitrarily, it will create a balanced binary tree which has a depth of log n. Therefore, the cost would be n*logn
