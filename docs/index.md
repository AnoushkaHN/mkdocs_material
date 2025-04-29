# Home Page 

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples

### Codeblocks

Some `code` goes here.

### Plain codeblock 

```
Some code

def myfunction()
// some comments

```

#### Code for a specific language

Some more code with the `py` at the start:

```py
import tensorflow as tf
def function_name()
```


#### With a title

```py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j+1] = items[j +1], items[j]
```


#### With line numbers

```py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j+1] = items[j +1], items[j]
```

#### Highlight line

```py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j+1] = items[j +1], items[j]
```

## Icons and Emojis

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-linkedin:{ .linkedin }

:octicons-heart-fill-24:{ .heart }