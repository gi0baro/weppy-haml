# weppy-Haml

weppy-Haml is an extension for [weppy framework](http://weppy.org) providing a Haml like syntax for templates. This is not a template engine but a compiler which converts haml files to html weppy templates.

[![pip version](https://img.shields.io/pypi/v/weppy-haml.svg?style=flat)](https://pypi.python.org/pypi/weppy-Haml) 

## Installation

You can install weppy-Haml using pip:

    pip install weppy-Haml

And add it to your weppy application:

```python
from weppy_haml import Haml

app.use_extension(Haml)
```

## Documentation

The complete documentation is available on the [weppy extensions registry](http://weppy.org/extensions/haml).

## License

weppy-Haml is released under BSD license. Check the LICENSE file for more details.
