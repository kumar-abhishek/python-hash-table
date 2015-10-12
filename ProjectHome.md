A robust, scalable, and economical Python oriented HASH table library designed to be both powerful and easy to implement.


---


**Quick Start**


```
from hashtable import *

instance = HashTable(table = [], maximum = 10)

instance.append("Sarah Jones")

instance.append(5)

print instance.lookup("Sarah Jones")

print instance.isEmpty()

print instance.isFull()

print instance.remove("Sarah Jones")

print instance.retrieve(5)

print instance.output()

instance.clear()

print instance.output()
```

**Note:** Every method within' the ` HashTable() ` class has a ` .__doc__ ` variable. Thus you can request heavier documentation of class methods via the ` .__doc__ ` declarative. For example, ` print HashTable(table = [], maximum = 10).lookup.__doc__ `