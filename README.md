# runoff-voting
Runoff voting is a ranking order, i.e. one of the voting systems in which the voter can specify a ranking of his preferred candidates.

compile the code with make:
```console
$ make ./runoff.c
```
usage:
```console
$ ./runoff [candidate1 candidate2 candidate3 ...]
$ Number of voters: [number]
$ Rank1: [candidate]
$ Rank2: [candidate]
$ Rank3: [candidate]
...
$ Rank1: [candidate]
$ Rank2: [candidate]
$ Rank3: [candidate]
...
Winner: candidate
```
