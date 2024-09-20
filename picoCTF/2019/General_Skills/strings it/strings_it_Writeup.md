# Description
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings) without running it?

# Hints
[strings](https://linux.die.net/man/1/strings)

# Solution
- We get the file by command:

        wget https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings

- We show the content of that file by command `strings` and find the flag by command `grep`:

        strings strings | grep "pico"

- Now we get the flag:

        picoCTF{5tRIng5_1T_7f766a23}