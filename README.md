# runoff-voting
Runoff is a ranked choice voting system. Each voter rank the candidates in a preference list. If any candidate has a majority of the first vote preference, that candidate is declared the winner. If no candidate has more than 50% of the votes, an instant runoff takes place. The candidate that received the least amount of votes is eliminated from the election, anyone that had previously selected that candidate as their first preference now has their second preference considered. The process repeats until one candidate has the majority or the election comes to a tie.

compile the code with make:
```console
$ make ./runoff
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
$ Winner: candidate
```
