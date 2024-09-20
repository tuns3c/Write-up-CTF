# Description
Can you convert the number 42 (base 10) to binary (base 2)?

# Hints
- Submit your answer in our competition's flag format. For example, if your answer was '11111', you would submit 'picoCTF{1111}' as the flag.

# Solution
- First, we using bc tool to convert a decimal number. In this case, we need to convert 42 to binary. 
- Then we get the result in terminal, it is the flag
- Now we convert in CLI, the command is:
        
        echo "obase=2; 42" | bc
- Here is result:

![alt text](/images/1.png)

- Finally, we put it into flag:

        picoCTF{101010}