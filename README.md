# PVA2 - Programování a vývoj aplikací
## Cvičení 06: Řídicí struktury - cykly

### Jak řešit
- Všechny úkoly řešte v souboru `reseni.py`, kde jsou připravená data a proměnné ve tvaru `vysledek = ...`.
- Místo `...` napište cyklus, který výsledek vytvoří. Názvy proměnných ani data neměňte, podle nich se řešení automaticky vyhodnocuje.
- Výsledek počítejte cyklem z dat v programu, ne opsáním hodnoty.
- Po každém `git push` se řešení vyhodnotí a výsledek najdete v pull requestu **Feedback**.
  Čísla požadavků odpovídají číslům úkolů níže, požadavky 20 a 21 kontrolují, že program používá cykly `for` a `while`.

### Cyklus `for` a funkce `range()`

#### 1
Do seznamu `prirozena` uložte prvních 10 přirozených čísel (1 až 10).

#### 2
Do seznamu `licha` uložte lichá čísla od 1 do 19. Použijte krok funkce `range()`.

#### 3
Do seznamu `odpocet` uložte čísla od 10 do 1 (sestupně).

#### 4
Do proměnné `soucet` uložte součet všech čísel od 1 do `n` (včetně `n`).

#### 5
Do proměnné `delka` uložte počet znaků textu `text`. Nepoužívejte funkci `len()`, znaky spočítejte cyklem.

#### 6
Do seznamu `ocislovane` uložte ovoce ze seznamu `ovoce` s pořadím od jedničky ve tvaru `"1. jablko"`.

### Cykly a slovník

#### 7
Do seznamu `vyprodano` uložte názvy zboží ze slovníku `sklad`, kterého je 0 kusů.

#### 8
Do proměnné `celkem_bodu` uložte součet bodů všech žáků ze slovníku `body`.

#### 9
Do proměnné `nejlepsi` uložte jméno žáka, který má ve slovníku `body` nejvíce bodů.

#### 10
Do seznamu `prospeli` uložte jména žáků, kteří mají alespoň 60 bodů.

#### 11
Ze slovníku `cenik` vytvořte nový slovník `cenik_dph` se stejným zbožím a cenami zvýšenými o 21 % DPH.
Ceny zaokrouhlete na 2 desetinná místa (`round(cislo, 2)`). Slovník `cenik` neměňte.

#### 12
Do slovníku `cetnost` uložte, kolikrát se které slovo opakuje v textu `veta`.

Očekávaný výsledek: `{'jablko': 3, 'hruška': 2, 'švestka': 1}`

#### 13
Ve slovníku `znamky` má každý žák seznam známek. Do slovníku `prumery` uložte ke každému jménu průměrnou známku žáka.

### Vnořené cykly

#### 14
Do seznamu `vzor` uložte řádky následujícího vzoru jako texty (`"1"`, `"1 2"`, …):

```
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```

### Řízení cyklu

#### 15
Do proměnné `prvni_zaporna` uložte první zápornou hodnotu ze seznamu `teploty`. Jakmile ji najdete, cyklus ukončete (`break`).

#### 16
Do seznamu `platna` uložte hodnoty ze seznamu `mereni` kromě chybějících měření `-1`. Chybějící hodnoty přeskočte (`continue`).

#### 17
Vyhledejte jméno `hledane` v seznamu `zaci`.
Když ho najdete, uložte do `zprava` text `"<jméno> je ve třídě"`, jinak `"<jméno> ve třídě není"` (použijte `else` u cyklu).

### Cyklus `while`

#### 18
Do seznamu `mocniny` uložte všechny druhé mocniny přirozených čísel od 1 do 81 (1, 4, 9, …). Použijte cyklus `while`.

#### 19
Spoříte `tydne` korun týdně. Cyklem `while` zjistěte, kolik týdnů musíte spořit, abyste měli alespoň `cil` korun, a výsledek uložte do `tydny`.
