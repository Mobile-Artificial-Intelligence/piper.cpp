# piper.cpp
This is simply a refactoring of the piper and piper-phonemize libraries to allow easier compilation and integration

A fast, local neural text to speech system that sounds great and is optimized for the Raspberry Pi 4.

## Building
To build run:
```sh
make example
```

or to just build the library run:
```sh
make
```

## Running
To execute the example run:
``` sh
./piper_cli en_US-lessac-medium.onnx "Hello, World!"
```

Original Project here [rhasspy/piper](https://github.com/rhasspy/piper)
