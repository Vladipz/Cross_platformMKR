## MKR

### Опис
Знайдіть кількість невироджених прямокутників зі сторонами, паралельними осям координат, вершини яких лежать у точках із цілими координатами всередині або на межі прямокутника, протилежні кути якого знаходяться у точках (0, 0) та (W, Н).

### Вхідні дані
Вхідний файл INPUT.TXT містить два натуральні числа W і Н, що не перевищують 1000.
### Вихідні дані
У вихідний файл OUTPUT.TXT виведіть відповідь на завдання.

| № | INPUT.TXT | OUTPUT.TXT |
|---|-----------|------------|
| 1 | 1 1       | 1          |
| 2 | 2 1       | 3          |
| 3 | 2 2       | 9          |



### Запуск програми
```bash
dotnet run --project App
```
### Запуск тестів
Без проміжних результатів
```bash
dotnet test Tests
```
З проміжними результатами
```bash
dotnet test Tests --logger "console;verbosity=detailed"
```

### Результати

Вхідні дані беруться з файлу `INPUT.TXT`, результати записуються в файл `OUTPUT.TXT`