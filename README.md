# L08E03: Exercise points analysis

Pomoci balíčku `data` z úkolu L08E03 napište jednoduchý script (`sum_points.py`), který ze vstupních dat `data.csv` (zisk bodů z domácích úkolů předmětu KMI/JP) v pracovním adresáři vytvoří soubor ve formátu `output.json` s následujícím obsahem:

```json
{"L01E01": 39, "L01E02": 38, "L01E03": 38, "L01E04PEP": 38, "L02E01": 36, "L02E02": 35, "L02E03": 35, "L02E04PEP": 37, "L03E01": 36, "L03E02": 31, "L04E01": 31, "L04E02": 32, "L04E03": 29, "L05E01": 31, "L05E02": 21, "L06E01": 17, "L06E02": 5}
```

Soubor obsahuje vždy název úkolu a součet získaných bodů (např. tedy úkol L01E01 splnilo 39 studentů). **Soubor do repozitáře neposílejte!**

Při řešení použíjte v maximální míře funkcionalitu balíčku `data` a `json`.

## Lokální testování
Funkčnost řešení ověříte následujícím příkazem:

```bash
pytest tests.py
```