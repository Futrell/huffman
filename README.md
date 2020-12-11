n-ary huffman code
---

Given a finite discrete probability distribution, return an n-ary Huffman code for it.

Usage:
```{python}
import huffman

weights = [.25, .25, .2, .1, .1, .1]

binary_code = huffman.huffman(weights, n=2)
# [(1, 0), (1, 1), (0, 0), (0, 1, 0), (0, 1, 1)]

trinary_code = huffman.huffman(weights, n=3)
# [(0,), (1,), (2, 2), (2, 0), (2, 1)]

```
