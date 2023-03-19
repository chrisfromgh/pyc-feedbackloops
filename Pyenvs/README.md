# Untangle Python Spaghetti

https://2023.pycascades.com/program/talks/untangle-python-spaghettis-deep-dive-into-environments-and-dependencies-management/
- Cheuk Ting Ho

https://github.com/cheukting

## Virtual environments

`python3 -m venv my_env`

What is inside?

```
import sys
print(sys.path)
```

This is where python where look at, all the system paths. `['',...]`

the first one is usually the local directory

When creating a new virtual envs using python venv, there are a few files

/bin
/lib
/include
pyvenv.cfg

