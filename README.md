# Python

### List operations
`remove` removes the `first matching value`, not a specific index:
```
>>> x = ['a', 'b', 'c', 'd']
>>> x.remove('b')
>>> x
['a', 'c', 'd']
```
`del` removes the item at a specific index:
```
>>> y = ['a', 'b', 'c', 'd']
>>> del y[1]
>>> y
['a', 'c', 'd']
```
`pop` removes the item `at a specific index` and `returns it`.
```
>>> z = ['a', 'b', 'c', 'd']
>>> z.pop(1)
'b'
>>> z
['a', 'c', 'd']
```
