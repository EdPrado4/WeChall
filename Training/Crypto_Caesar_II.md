# Crypto - Caesar II

I guess you are done with Caesar I, aren't you?
The big problem with caesar is that it does not allow digits or other characters.
I have fixed this, and now I can use any ascii character in the plaintext.
The keyspace has increased from 26 to 128 too. \o/

Enjoy!

```
0E 36 36 2B 20 31 36 29 73 20 40 36 3C 20 3A 36
33 3D 2C 2B 20 36 35 2C 20 34 36 39 2C 20 2A 2F
28 33 33 2C 35 2E 2C 20 30 35 20 40 36 3C 39 20
31 36 3C 39 35 2C 40 75 20 1B 2F 30 3A 20 36 35
2C 20 3E 28 3A 20 2D 28 30 39 33 40 20 2C 28 3A
40 20 3B 36 20 2A 39 28 2A 32 75 20 1E 28 3A 35
6E 3B 20 30 3B 06 20 78 79 7F 20 32 2C 40 3A 20
30 3A 20 28 20 38 3C 30 3B 2C 20 3A 34 28 33 33
20 32 2C 40 3A 37 28 2A 2C 73 20 3A 36 20 30 3B
20 3A 2F 36 3C 33 2B 35 6E 3B 20 2F 28 3D 2C 20
3B 28 32 2C 35 20 40 36 3C 20 3B 36 36 20 33 36
35 2E 20 3B 36 20 2B 2C 2A 39 40 37 3B 20 3B 2F
30 3A 20 34 2C 3A 3A 28 2E 2C 75 20 1E 2C 33 33
20 2B 36 35 2C 73 20 40 36 3C 39 20 3A 36 33 3C
3B 30 36 35 20 30 3A 20 30 36 37 2D 36 39 39 35
36 29 37 2C 75 
```

## Solution

```python
code = '
0E 36 36 2B 20 31 36 29 73 20 40 36 3C 20 3A 36 33 3D 2C 2B 20 36 35 2C 20 34 36 39 2C 20 2A 2F 28 33 33 2C 35 2E 2C 20 30 35 20 40 36 3C 39 20 31 36 3C 39 35 2C 40 75 20 1B 2F 30 3A 20 36 35 2C 20 3E 28 3A 20 2D 28 30 39 33 40 20 2C 28 3A 40 20 3B 36 20 2A 39 28 2A 32 75 20 1E 28 3A 35 6E 3B 20 30 3B 06 20 78 79 7F 20 32 2C 40 3A 20 30 3A 20 28 20 38 3C 30 3B 2C 20 3A 34 28 33 33 20 32 2C 40 3A 37 28 2A 2C 73 20 3A 36 20 30 3B 20 3A 2F 36 3C 33 2B 35 6E 3B 20 2F 28 3D 2C 20 3B 28 32 2C 35 20 40 36 3C 20 3B 36 36 20 33 36 35 2E 20 3B 36 20 2B 2C 2A 39 40 37 3B 20 3B 2F 30 3A 20 34 2C 3A 3A 28 2E 2C 75 20 1E 2C 33 33 20 2B 36 35 2C 73 20 40 36 3C 39 20 3A 36 33 3C 3B 30 36 35 20 30 3A 20 30 36 37 2D 36 39 39 35 36 29 37 2C 75 
'

```
