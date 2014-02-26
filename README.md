gbrr
====

Quick-switch for Git branches.

Usage:
------

```
gbrr [COUNT]
```

Where COUNT is the number of recently used branches to show. Defaults to 10.

Example:
--------

```
$ gbrr
0) f_test-1
1) f_test-whatever
2) master
Switch to which branch? 1

+ git checkout f_test-whatever
Switched to branch 'f_test-whatever
Your branch is up-to-date with 'origin/f_test-whatever'.
```
