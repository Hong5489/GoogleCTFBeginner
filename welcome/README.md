# Enter Space-Time Coordinates
```
Ok well done. The console is on. It's asking for coordinates. Beating heavily on the console yields little results, but the only time anything changes on your display is when you put in numbers.. So what numbers are you going to go for?  You see the starship's logs, but is there a manual? Or should you just keep beating the console?
```
[file.zip](file.zip)

Got 2 files: `log.txt`, `rand2`

Running `rand2`:
```
./rand2 
Travel coordinator
0: AC+79 3888 - 41701763051361, 88585831220439
1: Pliamas Sos - 84711225284807, 171710624322246
2: Ophiuchus - 121414305711331, 139224414951168
3: Pax Memor -ne4456 Hi Pro - 174720103051690, 14463654334697
4: Camion Gyrin - 121463846115170, 196018812518906
5: CTF - <REDACTED>

Enter your destination's x coordinate:
>>> 2
Enter your destination's y coordinate:
>>> 3
Arrived somewhere, but not where the flag is. Sorry, try again.
```
Running `strings` command found the flag!
```
# strings rand2 | grep CTF
Arrived at the flag. Congrats, your flag is: CTF{welcome_to_googlectf}
```

## Flag
> CTF{welcome_to_googlectf}