## c-init

A simple python project used for setting up c/c++ project directory structure.

Usage:
```
python3 /path/to/c-init/c-init.py <options>
```

`Options` are just 3 letters telling c-init what you want the project to be:
1. First letter `<>XX`:
	- `c` - specifies it's a c project
	- `x` - specifies it's a c++ project
2. Second letter `X<>X`:
	- `a` - specifies it's an executable application
	- `l` - specifies it's a library
3. Third letter `XX<>`:
	- `m` - specifies it's a make project
	- `c` - specifies it's a cmake project

Finally, it should (somewhat) look like this:
```
python3 c-init/c-init.py xam  # will create a C++ application project compiled with make 
python3 c-init/c-init.py clc  # will create a C library project compiled with Cmake
...
```