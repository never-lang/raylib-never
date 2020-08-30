# raylib-never

### Running examples

First exprt variables which point to raylib and Never raylib bindings.

```bash
export LD_LIBRARY_PATH=${HOME}/projects/raylib/src
export NEVER_PATH=${HOME}/projects/never/sample/lib
```

Then run examples:

```
${HOME}/projects/never/build/never -s 400 -f core_input_mouse.nev
${HOME}/projects/never/build/never -s 400 -f models_waving_cubes.nev
```

