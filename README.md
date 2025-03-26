# Obsah
- [logo python](#Python)
- [Kod + popis kodu](#Kod)

## Python
![1_3IcLSFuT8PQg4cUBaRXH1A](https://github.com/user-attachments/assets/c398b388-8262-4156-8364-9e398fd896cc)

### Kod
```python
def faktorial(n):
    return 1 if n == 0 else n * faktorial(n - 1)

cislo = int(input("Zadejte číslo: "))
print(f"Faktoriál čísla {cislo} je {faktorial(cislo)}")

Funkce faktorial používá ternární operátor pro zjednodušení: pokud je číslo 0, vrátí 1, jinak zavolá funkci znovu s menším číslem.
Program požádá uživatele o číslo a vypíše jeho faktoriál.
``` 
