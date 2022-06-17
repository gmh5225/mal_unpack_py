##  Utils required by mal_unpack_lib

To run correctly the library requires 3 executable files: 
- dll_load32.exe: the dll loader for 32 bit files
- dll_load64.exe: the dll loader for 64 bit files
- mal_unpack.exe: the lastest version available [here](https://github.com/hasherezade/mal_unpack/releases)

This script will automatically download them and copy to the appropriate locations.

1. Install requirements:
```console
pip install -r requirements.txt
```

2. Run using Python 3:
```console
python fetch.py
```

It should require all the neccessary executables
