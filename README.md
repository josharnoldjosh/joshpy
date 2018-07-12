# joshpy

A set of high level functions for getting things done in python3.

## Install
```python
pip3 install joshpy
```

## Usage examples
```python
from joshpy.joshpy import *

ensure_dir('test') # Will ensure a directory, test/, exists
delete_folder('test') # Will delete this folder, only if it exists

result = files(path='desktop', file_type='.jpg', recurse=False, include_path=False) # Will search a path for a certain file type and return their paths

lines(result) # Will print each element in a loop
```
