# valgrind-submission
1. put the `foobar` folder under valgrind source code
2. make [these](https://github.com/Beking0912/valgrind-customize-tool/commit/f71b77e984807555e622711af4ba60888b48eabc) changes
3. run the following commands
```
$ ./autogen.sh
$ ./configure
$ make
$ make install
$ gcc -g -o test test.c
$ valgrind --tool=foobar test
```
