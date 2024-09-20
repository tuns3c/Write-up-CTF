# Description
What is 0x3D (base 16) in decimal (base 10)?

# Hints
Submit your answer in our flag format. For example, if your answer was '22', you would submit 'picoCTF{22}' as the flag.

# Solution
- We use the bc tool to convert `base16` to `base10` by command:

        echo "obase=10; ibase=16; 3D" | bc

because the `bc` tool does not recognize the `0x` prefix commonly used to indicate hexadecimal (base16). Then we need to remove the prefix `0x` in `0x3D`.

- Now we get the result and put it into flag:

        picoCTF{61}