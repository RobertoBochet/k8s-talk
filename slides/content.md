# Intro e outro dentro l'HTML

Il markdown contiene solo il contenuto.

Di base si possono fare le slide anche in HTML se si vogliono animazioni buffe.

----

This is a long dash -- made of two little dashes (`--`).

This dash is even longer --- and it is made of three little dashes (`---`).

"Quoting" is fun and easy. `"`Plain quoting`"` is ugly.

----

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

There are **no** more heading levels.

----

<x-section-title>This is a section title</x-section-title>

If you want the section title in the top-right cornet
you can add **&lt;x-section-title&gt;title&lt;/x-section-title&gt;** in the slide

----

```python
import sys

x = 1 + 2

if x > 2:
  pass

try:
    with open('/dev/null') as f:
        pass
except IOError:
    raise Exception('Error!')
finally:
    sys.exit()
```

----

### How to display a warning

This is a warning box <!-- .element: class="warning" -->

----

- Do you remember bullet list?
  ```python
  bullet_list = ["Do you remember bullet list?"]
  ```
- You can also allign code to bullet lists!
  ```python
  bullet_list.append("You can also allign code to bullet lists!")
  ```
- It's not too hard!
  ```python
  if not hard:
      bullet_list.append("It's not too hard!")
  ```
