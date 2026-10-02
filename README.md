## 👋 About Me

```asm
section .about_me

username:
    db "siregon72"

role:
    db "Security Student & Developer"

interests:
    db "Reverse Engineering"
    db "Binary Analysis"
    db "Linux"
    db "CTF"
    db "Web Development"

section .tech_stack

languages:
    db "Assembly"
    db "C"
    db "JavaScript"
    db "Python"

frontend:
    db "React"
    db "Tailwind CSS"

backend:
    db "Supabase"

tools:
    db "GitHub"
    db "Cloudflare"

section .text
global _start

_start:
    call analyze_binary
    call reverse_engineer
    call build_projects
    call solve_ctf
```
