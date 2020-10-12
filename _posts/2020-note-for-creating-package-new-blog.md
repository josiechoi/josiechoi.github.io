---
layout: post
title:  Note for creating package "
date:   2020-10-12 14:09:00 +0400
author: "Josephine Choi"
---

# Structure of writing a package

work_dir/
├── my_package
│   ├── __init__.py
│   └── utils.py
├── requirements.txt
└── setup.py
```
pip install -r requirements.txt allows you to install everything listed in requirements.txt file
```
Class
- according to PEP 8, should be in camelCase, should never contain underscore

```
class MyClass :
    """
    :This is documentation that would come up when an user calls for help
    : help blah blah blah
    """
    def __init__(self, value):
        #Define attribute
        self.attribute=value
```

- similar to function, we can add this to the __init__ file (MyClass in the same directory)

```
from .my_class import MyClass
```

- to create an instance of MyClass (working in work_dir/my_script.py)

```
import my_package
#create instance of my_class
my_instance=my_package.MyClass(value='class attribute value')

#print out class attribute name
print(my_instance.attribute)

```

The self convention :
- a strong PEP 8 convention
- is a way to refer to a class even though we don't know what the user is going to name their instance. When defining typical class instance methods, like __init__ , self is the first argument
