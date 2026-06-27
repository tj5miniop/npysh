# NPYSH - {N}ative {P}ython {SH}ell

A custom shell, for Linux/Unix (possibly, testing needed), written in Python 

## FEATURES 
the shell currently supports
- Standard program execution (ls, cd, ping, fastfetch etc); this is done by scanning certain directories for executable files
- Currently uses a simple configuration system to allow users to add their own directories. More features to come such as ALIASES, VARIABLES, ETC


### Integration 

This project has primarily been developed to be Distribution agonostic, however, I will be looking into the usecases of this shell for immutable systems, such as disabling commands like DNF so then users don't accidentally break their systems
