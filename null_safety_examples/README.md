## Null-safe examples

See /examples/README.md for details. This doc describes what's different in
working with null-safe examples only, with the assumption that null safety isn't
on by default in the stable channel.

## How do I run the analyzer on an example?

Change directory into the example's folder and run Dart commands there. For
example, if you're using the flutter beta channel:

```console
$ cd null_safety_examples/misc
$ export PATH=~/development/flutter/bin:$PATH
$ flutter upgrade
$ dart pub get
$ dart analyze
```

## How do I run example tests?

Change directory into the example's folder and run Dart commands there. For
example:

```console
$ cd null_safety_examples/misc
$ dart pub get
$ dart test  # Run VM tests ## PENDING: check!
$ dart test -p chrome  # Run browser tests ## PENDING: check!
```
