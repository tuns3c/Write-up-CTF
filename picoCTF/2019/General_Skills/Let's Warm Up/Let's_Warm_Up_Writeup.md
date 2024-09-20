# Description
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?

# Hint
Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.

# Solution
- We use `bc` tool to convert hexadecimal to ASCII by command:

        echo "ibase=16; 70" | bc

- Then we have the result: `112`
- Now we have to convert `112` to Ascii by command:

        printf "\x70"
- Finally, we get the result `p` and put it into flag:

        picoCTF{p}