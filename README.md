# tree-visualisation
A modification of [David Galles' visualisation](https://www.cs.usfca.edu/~galles/visualization/about.html) of [BSTs](https://www.cs.usfca.edu/~galles/visualization/BST.html), [B-Trees](https://www.cs.usfca.edu/~galles/visualization/BTree.html) and [Red-Black-Trees](https://www.cs.usfca.edu/~galles/visualization/RedBlack.html).

## Manual
- **Insert:** Enter one or more numbers between `0` and `999`. Separate them with your favorite non-digit character sequence. Press `Insert`.
- **Delete:** Enter a number. Press `Delete`.
- **Find:** Enter a number. Press `Find`.
- **Polulate randomly:** Enter a count between `1` and `99`. Press `Random`.
- **In-order deth first search:** Press `Print`.

## Visualisations
- [Binary Search Tree](./BST/)
- [B-Tree](./BTree/)
- [Red-Black-Tree](./RedBlack/)

---

## Modifications
### Functional
#### General
- Multiple values can be inserted at once (values can be separated by any non-digit character, causing that...)
- Only numbers can be added
- Maximum value is `999`.
- A number of random values between `000` and `999` can be inserted

#### B-Trees
- Changed degree notation to be in line with *Cormen et al. - Introduction to Algorithms*

### Visual
- Color theme changed
- Canvas font size increased