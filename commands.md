# Základní Struktura Python

## Hlavní datové typy
- `boolean = True / False` – pravda/nepravda
- `integer = 10` – celé číslo
- `float = 10.01` – desetinné číslo
- `string = "123abc"` – řetězec
- `list = [ value1, value2, … ]` – seznam
- `dictionary = { key1:value1, key2:value2, …}` – slovník

## Číselné operátory
- `+` sčítání
- `-` odčítání
- `*` násobení
- `/` dělení
- `**` mocnina
- `%` zbytek po dělení
- `//` celočíselné dělení

## Porovnávací operátory
- `==` rovno
- `!=` nerovno
- `>` větší
- `<` menší
- `>=` větší nebo rovno
- `<=` menší nebo rovno

## Operace s řetězci
- `string[i]` – znak na pozici i
- `string[-1]` – poslední znak
- `string[i:j]` – znaky od i do j

### Metody pro řetězce
- `string.count(x)`
- `string.find(x)`
- `string.format(x)`
- `string.join(L)`
- `string.lower()`
- `string.replace(x, y)`
- `string.split(x)`
- `string.strip(x)`
- `string.upper()`

## Operace se seznamy
- `list = []`
- `list[i] = x`
- `list[i]`
- `list[-1]`
- `list[i:j]`
- `del list[i]`

### Metody pro seznamy
- `list.append(x)`
- `list.clear()`
- `list.copy()`
- `list.count(x)`
- `list.extend(L)`
- `list.index(x)`
- `list.insert(i, x)`
- `list.pop(i)`
- `list.remove(x)`
- `list.reverse()`
- `list.sort()`

## Operace se slovníky
- `dict = {}`
- `dict[k] = x`
- `dict[k]`
- `del dict[k]`

### Metody pro slovníky
- `dict.clear()`
- `dict.copy()`
- `dict.get(k)`
- `dict.items()`
- `dict.keys()`
- `dict.pop(k)`
- `dict.update(D)`
- `dict.values()`

## Ošetření výjimek
```python
try:
    # kód
except <chyba>:
    # ošetření
else:
    # pokud nedošlo k chybě
```

## Vestavěné funkce
- `abs(n)`
- `float(x)`
- `help(object)`
- `input(s)`
- `int(x)`
- `len(x)`
- `list(x)`
- `map(function, L)`
- `max(L)`
- `min(L)`
- `print(x, sep='y')`
- `range(n1,n2,n)`
- `round(n1,n)`
- `sorted(L)`
- `str(x)`
- `sum(L)`
- `type(x)`

## Podmínkové příkazy
```python
if podmínka:
    # kód
elif jiná_podmínka:
    # jiný kód
else:
    # výchozí kód
```

## Smyčky
- `break`, `continue`, `pass`

### While
```python
while podmínka:
    # tělo
```

### For
```python
for prvek in seznam:
    # tělo

for i in range(start, stop, step):
    # tělo

for i, hodnota in enumerate(seznam):
    # tělo

for k, v in slovnik.items():
    # tělo
```

## Třídy
```python
class Trida:
    def __init__(self, parametry):
        self.atribut = parametry

    def metoda(self):
        return self.atribut

obj = Trida("hodnota")
obj.metoda()
```

## Funkce
```python
def funkce(param):
    return param
```

## Import modulů
```python
import modul
modul.funkce()

from modul import *
funkce()
```

---

