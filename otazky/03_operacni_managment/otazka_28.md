# Otázka 28: Co je a k čemu slouží analýza citlivosti?

**Analýza citlivosti** je technika používaná k určení, jak změny vstupních proměnných v modelu ovlivňují výstupní výsledky. Pomáhá pochopit, které vstupní faktory mají největší dopad na výsledky a jak se tyto výsledky mohou měnit při různých scénářích. Typicky se využívá například ve financích, projektovém řízení nebo inženýrství.

---

## Hlavní účely analýzy citlivosti

- **Identifikace klíčových proměnných:** Zjistí, které vstupy mají největší vliv na výsledek.
- **Lepší pochopení modelu:** Ukáže, jak spolu proměnné souvisí a ovlivňují výsledek.
- **Podpora rozhodování:** Umožní posoudit, jak by se výsledek změnil při různých scénářích (optimistický, realistický, pesimistický).
- **Řízení rizik:** Pomáhá zaměřit se na nejrizikovější faktory a navrhnout opatření.

---

## Příklady použití

- **Vyhodnocení významu jednotlivých položek ekonomického výsledku**
- **Volba mezi alternativními projekty:**  
    - Určení pravděpodobnosti určitého stavu okolí, pro který jedna z alternativ poskytuje nejlepší očekávaný výnos  
    - Pokud jsou některé alternativy rovnocenné, může pomoci informace o pravděpodobnosti
- **Možný vývoj projektu při změnách vstupních parametrů**
- **Citlivost zisku na změnu faktorů, které ho ovlivňují**

---

## Jak analýza citlivosti probíhá?

1. **Změna jedné proměnné:** Ostatní proměnné jsou konstantní, sleduje se dopad na výstup.
2. **Změna více proměnných najednou:** Kombinují se různé scénáře.
3. **Simulace (např. Monte Carlo):** Zkoumá se vliv mnoha proměnných s různými pravděpodobnostmi.

---

## Ukázková tabulka analýzy citlivosti

| Položka                | Počáteční hodnota | Zlepšení o 10% | Změna faktoru | Nová hodnota zisku [Kč] | Změna zisku [%] |
|------------------------|:----------------:|:--------------:|:-------------:|:-----------------------:|:---------------:|
| **Objem prodeje [ks]** |      2 500       |     2 750      |     250       |        492 500          |     **15,9**    |
| **Prodejní cena [Kč]** |       650        |      715       |      65       |        587 500          |     **38,2**    |
| **Variabilní náklady [Kč]** |    380    |      342       |     -38       |        520 000          |     **22,4**    |
| **Fixní náklady [Kč]** |    250 000       |   225 000      |   -25 000     |        450 000          |     **5,9**     |

---

## Příklady výstupů

- **Tornado diagram:** Graficky ukazuje, které proměnné mají největší vliv.
- **Tabulky scénářů:** Přehledně zobrazují výsledky pro různé kombinace vstupů.

---

**Shrnutí:**  
Analýza citlivosti je důležitý nástroj pro pochopení nejistot, řízení rizik a lepší rozhodování v nejistých podmínkách.

[<- Domů](../../README.md)