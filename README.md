section .data

name:  db "siregon72"
role:  db "Security Student"
stack: db "ASM, C, Python"
focus: db "Reverse Engineering, CTF"

section .text
global _start

_start:
    call reverse
    jmp keep_learning
