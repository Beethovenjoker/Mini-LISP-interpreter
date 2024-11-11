## RISC-V Assembly and Instruction Pipeline

```
                                       .  
╦  ╔═╗═╗ ╦   ┬   ╦ ╦╔═╗╔═╗╔═╗    \_____)\_____  
║  ║╣ ╔╩╦╝  ┌┼─  ╚╦╝╠═╣║  ║      /--v____ __`<  
╩═╝╚═╝╩ ╚═  └┘    ╩ ╩ ╩╚═╝╚═╝            )/    
                                         '       
```

### Introduction
In this final project, your goal is to craft a Mini-LISP interpreter. All resources you need are on the new-eeclass, including the language specifications, a standard interpreter (called smli) and some Mini-LISP program examples for testing. Since you have learnt lex and yacc, it’s good to use these tools to build your project, but you are allowed to use other languages and tools for this project.

### HackMD
#### [Compiler Final Project](https://hackmd.io/XthPcj50RNixLm39gmeO7w)

### Execution Flow
#### Step1:
在CMD下與程式碼所在的資料夾輸入以下三個指令:

```
$ flex FinalProject.l
```

```
$ bison -dy FinalProjecty.y
```

```
$ gcc lex.yy.c y.tab.c
```

#### Step2:
在CMD下與程式碼所在的資料夾輸入以下指令來檢查測資:

```
$ a.out < 01_1.lsp
```

(01_1是測資的檔案名)
