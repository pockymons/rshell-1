#rshell
rshell is an imitation of the BASH terminal. This implementation allows the use 
of connectors such as `||`, `&&` and `;`.  Anything after a `#` is a comment and 
is ignored by the program. The command `exit` closes the program. 

Connector Meanings:
`||` run command only if first one fails.
`&&` run command only if first one succeeds.
`;` run any command if the command is true.

#How to run rshell
```
$git clone https://github.com/jmeji011/rshell.git
$cd rshell
$git checkout hw0
$make
$bin/rshell
```

#Bugs
Echo with quotes do not work with this shell implementation.

`echo "hello"` , This will display `"hello"`. 



