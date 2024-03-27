# Python-Modules
To check which methods or functions are available in a Python module.

**dir()**
```
import module_name
print(dir(module_name))
```

**help()**
```
import module_name
help(module_name)
```

![image](https://github.com/r1skkam/Python-Modules/assets/58542375/86583b6a-76e9-4f28-baa1-0e8d9fdb5b31)

```
import module_name
print(module_name.__dict__)
```

![image](https://github.com/r1skkam/Python-Modules/assets/58542375/baa0f0da-d04f-4618-a7ce-77e8ed07a437)

```
import math

# Using dir()
print(dir(math))

# Using help()
help(math)

# Using __dict__
print(math.__dict__)
```

![image](https://github.com/r1skkam/Python-Modules/assets/58542375/a9222a88-e90a-486c-97ee-d2a6bd64efab)

### platform

```
import platform
platform.architecture()
```

![image](https://github.com/r1skkam/Python-Modules/assets/58542375/58eb2a80-7e4a-4db5-b243-39ad3353674e)
