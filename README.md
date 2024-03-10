# 'Hello World!' as an ELF file
### Generates an executable ELF file that says "Hello, World!" for x86 Linux (or system v XD)


## Compilation:
It's super simple. Use any compiler you want and name the output anything you want. For example:

```gcc hello-elf.c -o hello-elf```

## Usage:

Run the compiled program in your terminal using 

```./hello-elf```

You can change the name of the file that is generated by passing your preffered file name as an argument to the command. Spaces and anything after them will be removed. By default, the name of the generated file is 'elf-file.' The file will always be generated in the current working directory.

You may have to make the ELF file actually executable using `chmod`:

```chmod +x elf-file```