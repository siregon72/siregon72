## 👋 About Me

```asm
section .about_me

username:
    db "siregon72"

role:
    db "Security Student"

interests:
    db "Reverse Engineering"
    db "Binary Analysis"
    db "Linux"
    db "CTF"

_start:
    call learn
    call analyze
    call reverse_engineering

    jmp next_challenge
```
