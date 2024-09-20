# Description
What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.

# Hints
Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.

# Solution
- We see that `bDNhcm5fdGgzX3IwcDM1` like Base64
- Then we decode it by command:

        echo "bDNhcm5fdGgzX3IwcDM1" | base64 --decode

- And we get the result `l3arn_th3_r0p35` and put it to flag:

        picoCTF{l3arn_th3_r0p35}