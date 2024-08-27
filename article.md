# test

labels: playing_around

this is a test file.

```python
def edge(from: Node, to: Node):
  """an indicator function that returns true if the veridical graph has an edge from x to y."""
  d = distance(from, to)
  return d < from.shell.projected_onto(d).norm()
```
