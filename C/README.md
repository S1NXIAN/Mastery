# C — Mastery Roadmap

---

## Reading order

| Order | Book |
|---|---|
| 1 | King — *C Programming: A Modern Approach* (2nd ed.) |
| 2 | Kernighan & Ritchie — *The C Programming Language* (2nd ed.) |
| 3 | Seacord — *Effective C* (2nd ed.) |

### Notes

- **Read K&R alongside King**, not after. King is the tutorial; K&R is the compressed essence and reference.
- **Effective C** is for after you can write working C programs but before you have ingrained bad habits. It teaches safety, undefined behavior, and professional discipline.


---

## Recommended compile

```
gcc -Wall -Wextra -Wpedantic -Werror -g -O0 -fsanitize=address,undefined main.c -o main
```

---

*See [REFERENCES.md](REFERENCES.md) for book details and file locations.*
