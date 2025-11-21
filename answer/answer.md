to-do1-1:
si – amount of data swapped in from disk per second
so – amount of data swapped out to disk per second
bi – blocks received (block input) from a block device per second
bo – blocks sent (block output) to a block device per second

to-do2-1:
P#          SA          EA  
P1          600400      600757
P2          601200      601410
P3          602000      602468
P4          ----        Not Allocated

to-do2-2:
P#          SA          EA  
P1          600400      600757
P2          603400      603610
P3          602000      602468
P4          601200      601691

to-do2-3:
First-fit is simple and fast, but it can block later processes because it often leaves unusable gaps in memory. Best-fit uses space more efficiently by choosing the smallest partition that fits, which can allow more processes (like P4) to be allocated, but it also creates many small leftover holes. Overall, the main issue is external fragmentation, which affects both methods in different ways.

to-do3-1:
2^32 frames

to-do3-2:
12 bits

to-do3-3:
2^48 bytes (256 TB)