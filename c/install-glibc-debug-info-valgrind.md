# Install glibc debug info for Valgrind

If Valgrind (compiled from source) complains about a function redirection that cannot be setup, it can be easily fixed on Debian (and probably Ubuntu) with:

```bash
$ sudo apt-get update
$ sudo apt-get install libc6-dbg
```