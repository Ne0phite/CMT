# CMT

## CCWC  
## Summary

Building command word count tool
1. count bytes with -c flag
2. count lines with -l flag
3. words -w flag
4. char with -m 
5. support default option that does 1-3 in one line

Need to know how to do
1. read file
2. tell type of file (.txt, .pdf...)
3. what is byte/line/word/char
4. how to build command line tool with flags


TODOs
1. create basic terminal command that prints something to the terminal
2. 
3. write a test for our user command


Done so far:
create `~/.custom_bash_commands.sh` file
    open with `open .custom_bash_commands.sh -a "TextEdit"`
write simple wwcw command 
```
function ccwc() {
 echo hi
}
```
to set it after saving
run `source .custom_bash_commands.sh`
to test write `wwcw` in command line