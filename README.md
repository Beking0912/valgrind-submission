# valgrind-submission

```
$ ./autogen.sh
$ ./configure
$ make
$ make install
$ gcc -g -o test test.c
$ valgrind --tool=foobar test
```