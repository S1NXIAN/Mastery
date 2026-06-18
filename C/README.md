# C Mastery Roadmap

A curated learning path to mastering the C programming language from syntax basics to professional, secure development.

## Reading Order

| Order | Resource | Description |
| :---: | :--- | :--- |
| 1 | King — *C Programming: A Modern Approach* (2nd ed.) | Core language tutorial covering up to C99. |
| 2 | Kernighan & Ritchie — *The C Programming Language* (2nd ed.) | The definitive compressed essence and reference. |
| 3 | Seacord — *Effective C* (2nd ed.) | Modern professional discipline, safety, and security. |

> [!NOTE]  
> **Read King and K&R concurrently.** Use King as the primary structured tutorial and K&R as the concise conceptual reference.
> 
> **Read Effective C afterwards.** Do not start this until you can comfortably write working programs. It targets C17/C23 standards and focuses on eliminating undefined behavior before bad habits become permanent.

## Recommended Compilation

Always compile with strict diagnostics, warnings-as-errors, and address/undefined-behavior sanitizers enabled:

```bash
gcc -Wall -Wextra -Wpedantic -Werror -g -O0 -fsanitize=address,undefined main.c -o main
```

For details on where to obtain these books and their local file locations, see the [References Guide](file:///home/xian/Projects/mastery/C/REFERENCES.md).

