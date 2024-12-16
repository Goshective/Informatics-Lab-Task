## Решение Лабоаторной
### Команда-однострочник

```bash
ls | xargs -L 1 -d '\n' wc > result.txt 2> errors.txt
```
