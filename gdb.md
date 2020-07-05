# GDB

## Instruction 

GNU debugger, It's used for c/c++ and other programming languages debug tools. It has rich and powerful fucntions. 







## How to use it 

1. `list`
    - `list [file:]function` : list the files source code of the specific function 


2. `break [point]`
    - `break [point]`
3. `delete [point]`
    - `delete [point]`
4. `run`
5. `print`
    - `print /a [arg]`  : Print the address of arg 
    - `print /s [arg]`  : Print `string` format of arg 
    - `print /c [arg]`  : Print `character` format of arg
    - `print /x [arg]`  : Print `HEX format` of arg
    - `print /t [arg]`  : Print `BIN format` of arg 
    - `print *[arg_address]` : Print the content of arg_address point to 
    - `print *(int*)(arg_address)` : Print the content of `(int*)arg_address` point to 

6. `info`
    - `info frame` : Print the frames information 
    - `info registers` : Print the register message 
    - `info locals` : Print the local arguments 
    - `info args` : Print the arguments 


7. `continue`
8. `step`
    - `stepi`   : run one insruction
    - `stepi [number]` : run `i` times instructions 
    - `nexti` : run one function instruction 

9. `disas`
    - `disas`   : Disassembly current function 
    - `disas [function_name]` : Disassembly the specific function 
    - `disas [address]` : Dissembly the function near the address 
    - `disas [start_addr] [end_addr]` : Dissembly the code from the start address to endaddress 
10. `help`
    - `help`
