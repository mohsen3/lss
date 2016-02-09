# lss
A simple equivalent to the ls command with compact representation for file names with numeric IDs.

# Example

Suppose that `ls`ing inside a directory generates the following list:

```
example.txt     file01-002.txt  file01-004.txt  file01-009.txt  file01-011.txt  file02-02.txt
file01-001.txt  file01-003.txt  file01-006.txt  file01-010.txt  file02-01.txt   file02-03.txt
```

`lss`ing will generate:

```
1   example.txt
3   file02-##.txt       1-3
8   file01-###.txt      1-4 6 9-11
```
