# Description
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file)? This would be really tedious to look through manually, something tells me there is a better way.

# Hints
grep [tutorial](https://ryanstutorials.net/linuxtutorial/grep.php)

# Solution
- First, we get the file in description by command:

        wget https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file
        
- Then we show the content of file by cat command and mix with Grep:

        cat file | grep "pico"
- Finally we get the flag:

        picoCTF{grep_is_good_to_find_things_5af9d829}