# TheProofIsTrivial

Python port of the javascript based website
[TheProofIsTrivial](http://www.theproofistrivial.com/).

## Examples

```python
import theproofistrivial

quote = theproofistrivial.QuoteGenerator()
output = quote.create()

print(output)
```

The result is a list:

```
['The proof is trivial! Just biject it to a',
 'structure-preserving',
 'Lie algebra',
 'whose elements are',
 'prime',
 'sigma-algebras']
```

You can then process the list to make a single string or leave as is:

```python
# Single line string
output = " ".join(output)

# Multi line string
output = "\n".join(output)
```
