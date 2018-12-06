# javascript-parse-gist

### Example gist:
https://gist.github.com/eshnil2000/319e72497131a1d2f9e7e0f18038f1c0

#### Content of this gist:
```
import hashlib;<br>
import unittest;<br>
from unittest import TestCase;<br>

for i in range(10):<br>
&emsp;print(i)<br>
&emsp;&emsp;print(x);
```

#### When this renders, it returns:
new lines without the <br>
tabs without the &emsp

#### When printing to codemirror, can print without <br>:

import hashlib;
import unittest;
from unittest import TestCase;

for i in range(10):
  print(i);
    print(x);
