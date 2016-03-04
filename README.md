# Doxygen

A container to generate doxygen documentation

## Usage

Navigate to the document root of your application.

```bash
docker run --rm -it -v <path to application>:/src hourd/doxygen
```

This asumes your doxygen configuration is called ```Doxyfile``` and is in the root of your application.


You can use ``` `pwd` ``` as a shorthand to say the current working directory.

```bash
docker run --rm -it -v `pwd`:/src hourd/doxygen
```
