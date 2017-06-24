Quickly create files from a space-delimited string of file names

# usage
```sh
$ str2file "[f:,d:] <filename> ..."
```


# examples
```sh
# create files named `foo.txt`, `bar.txt`, and `baz.txt`
$ str2file "f: foo.txt bar.txt baz.txt"

# `f:` is optional for creating files
$ str2file "foo.txt bar.txt baz.txt"

# create directories named `foo`, `bar`, and `baz`
$ str2file "d: foo bar baz"
```
