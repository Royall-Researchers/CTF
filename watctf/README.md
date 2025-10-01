# WATCTF trick
 where the provide python program prints lot of noisy output and appears to hide the flag.the program actually reads the flag, but uses carriage returns (`\r`) to overwrite lines in the terminal. so, the flag look like unwanted content. when viewed interactively

## solve

- when run the program and save complete stdout to a file

for example :
```bash
python program.py > subl.txt
 
