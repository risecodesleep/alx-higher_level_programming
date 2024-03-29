# Python - Almost a circle

This project is about unit testing, serialization, deserialization, JSON, `args` and `kwargs` in **Python**.

## Technologies used
* Files interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* Vi editor
* Bash 5.0.17(1)

## Files

`models` folder contents:

| Filename | Description |
| -------- | ----------- |
| `__init__.py` | Script that converts the directory as a package |
| `base.py` | Base class of geometrical instances |
| `rectangle.py` | Class that inherits attributes references from `Base` class |
| `square.py` | Class that inherits attributes references from `Square` class |

Each class contains public/private attibutes, class and static methods. Also, these class raise exceptions when is required.

`tests/test_models` folder contents:

| Filename | Description |
| -------- | ----------- |
| `__init__.py` | Script that converts the directory as a package |
| `test_base.py` | Module that contains unittests to `Base` class |
| `test_rectangle.py` | Module that contains unittests to `Rectangle` class |
| `test_square.py` | Module that contains unittests to `Square` class |
