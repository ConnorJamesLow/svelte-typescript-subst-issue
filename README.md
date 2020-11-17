# Steps to reproduce on Windows
 - [subst](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/subst) a directory and clone this repository into it. 
 - From the subst'd drive letter, build and run the project, e.g.  

```bash
D:\> npm i
D:\> npm run dev
# or
D:\> npm run build
D:\> npm start
```
 - Build should fail:
```log
Unexpected token (Note that you need plugins to import files that are not JavaScript)
1: function test(name: string) {
                     ^
2:     console.log('Hello,', name);
3: }
```  
