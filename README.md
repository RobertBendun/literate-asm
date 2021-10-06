# Literate Assembler

## Concept

Basically Markdown file with asm code blocks. Instead of labels reference headers.

## Example

````md
This program exits with two numbers

```asm
mov rdi, 12
mov rsi, 21
call # Add 2 numbers
mov rdi, rax
mov rax, 60
syscall
```

# Add 2 numbers
```asm
mov rax, rdi
add rax, rsi
ret
```
````
