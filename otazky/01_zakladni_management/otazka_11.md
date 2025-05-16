# Porterův model 5 konkurenčních sil

## Základní charakteristika modelu

Porterův model pěti konkurenčních sil je analytický nástroj vyvinutý ekonomem Michaelem E. Porterem, který slouží k:
- Posouzení atraktivity odvětví
- Identifikaci klíčových konkurenčních sil
- Porozumění dynamice odvětví
- Formulování podnikové strategie

```mermaid
graph TD
    CENTER[Konkurenční rivalita<br>v odvětví] 
    ENTRY[Hrozba vstupu<br>nových konkurentů]
    SUPPLIERS[Vyjednávací síla<br>dodavatelů]
    BUYERS[Vyjednávací síla<br>odběratelů]
    SUBSTITUTES[Hrozba<br>substitutů]
    
    ENTRY -->|Ovlivňuje| CENTER
    SUPPLIERS -->|Ovlivňuje| CENTER
    BUYERS -->|Ovlivňuje| CENTER
    SUBSTITUTES -->|Ovlivňuje| CENTER
    
    classDef center fill:#f96,stroke:#333,stroke-width:2px,color:#000;
    classDef forces fill:#bbdefb,stroke:#333,stroke-width:1px,color:#000;
    
    class CENTER center;
    class ENTRY,SUPPLIERS,BUYERS,SUBSTITUTES forces;
```

## Vysvětlení jednotlivých sil

| Síla | Popis | Faktory, které ji posilují |
|------|-------|---------------------------|
| **1. Hrozba vstupu nových konkurentů** | Jak snadné nebo obtížné je pro nové společnosti vstoupit na trh | • Nízké kapitálové požadavky<br>• Slabá loajalita ke značkám<br>• Snadný přístup k distribučním kanálům<br>• Nedostatek patentů a know-how<br>• Nízké úspory z rozsahu |
| **2. Vyjednávací síla dodavatelů** | Schopnost dodavatelů diktovat podmínky firmám v odvětví | • Malý počet dodavatelů<br>• Unikátní produkty či služby<br>• Vysoké náklady na změnu dodavatele<br>• Absence substitutů<br>• Možnost dopředné integrace |
| **3. Vyjednávací síla odběratelů** | Schopnost zákazníků ovlivňovat ceny a podmínky | • Vysoká koncentrace zákazníků<br>• Standardizovaný produkt<br>• Nízké náklady na změnu dodavatele<br>• Cenová citlivost<br>• Možnost zpětné integrace |
| **4. Hrozba substitutů** | Existence alternativních produktů či služeb | • Nízké náklady na přechod k substitutu<br>• Dobrý poměr cena/výkon substitutů<br>• Změna preferencí zákazníků<br>• Inovace v substitučních odvětvích |
| **5. Rivalita mezi stávajícími konkurenty** | Intenzita soupeření mezi firmami v odvětví | • Vysoký počet konkurentů<br>• Pomalý růst odvětví<br>• Vysoké fixní náklady<br>• Nízká diferenciace produktů<br>• Vysoké bariéry výstupu z odvětví |

## Příklad: Tesla, Inc. (odvětví elektromobilů)

```mermaid
graph TD
    subgraph "Porterův model 5 sil pro Teslu"
        CENTER[Rivalita v odvětví<br><b><font color="black">VYSOKÁ</font></b><br>VW, Ford, GM,<br>BYD, Lucid, Rivian] 
        ENTRY[Hrozba nových konkurentů<br><b><font color="black">STŘEDNÍ AŽ VYSOKÁ</font></b><br>Apple?, čínské značky] -->|Ovlivňuje| CENTER
        SUPPLIERS[Vyjednávací síla dodavatelů<br><b><font color="black">STŘEDNÍ AŽ VYSOKÁ</font></b><br>Panasonic, LG, CATL - baterie<br>TSMC, Samsung - čipy] -->|Ovlivňuje| CENTER
        BUYERS[Vyjednávací síla odběratelů<br><b><font color="black">STŘEDNÍ</font></b><br>Individuální zákazníci<br>Flotiloví zákazníci] -->|Ovlivňuje| CENTER
        SUBSTITUTES[Hrozba substitutů<br><b><font color="black">STŘEDNÍ AŽ VYSOKÁ</font></b><br>Spalovací motory<br>Hybridní vozy<br>Veřejná doprava<br>Sdílená mobilita] -->|Ovlivňuje| CENTER
    end
    
    classDef center fill:#f96,stroke:#333,stroke-width:2px,color:#000;
    classDef forces fill:#bbdefb,stroke:#333,stroke-width:1px,color:#000;
    
    class CENTER center;
    class ENTRY,SUPPLIERS,BUYERS,SUBSTITUTES forces;
```

### 1. Hrozba vstupu nových konkurentů: STŘEDNÍ AŽ VYSOKÁ

**Bariéry vstupu:**
- ✅ Vysoké kapitálové náklady (výroba, R&D)
- ✅ Silná značka Tesla a loajalita zákazníků
- ✅ Technologické know-how a patenty
- ✅ Úspory z rozsahu

**Faktory zvyšující hrozbu:**
- ❗ Rostoucí atraktivita trhu s elektromobily
- ❗ Technologický pokrok (sdílené platformy)
- ❗ Vládní podpora elektromobility
- ❗ Vstup technologických firem s kapitálem

### 2. Vyjednávací síla dodavatelů: STŘEDNÍ AŽ VYSOKÁ

**Klíčové faktory:**
- ❗ Koncentrace dodavatelů kritických komponentů
- ❗ Klíčový význam baterií a čipů
- ❗ Vysoké náklady na změnu dodavatelů
- ✅ Snaha Tesly o vertikální integraci (vlastní baterie)
- ✅ Dlouhodobé strategické partnerství s dodavateli

### 3. Vyjednávací síla odběratelů: STŘEDNÍ

**Klíčové faktory:**
- ✅ Nízká koncentrace individuálních zákazníků
- ✅ Diferenciovaný produkt (značka, software, ekosystém)
- ❗ Rostoucí dostupnost informací pro zákazníky
- ❗ Vysoká cenová citlivost (prémiový segment)
- ❗ Větší síla flotilových zákazníků

### 4. Hrozba substitutů: STŘEDNÍ AŽ VYSOKÁ

**Hlavní substituty:**
- ❗ Automobily se spalovacími motory (nižší cena)
- ❗ Hybridní automobily (přechodné řešení)
- ❗ Veřejná doprava
- ❗ Sdílená mobilita (Uber, carsharing)
- ❗ Mikromobilita (elektrokola, koloběžky)

**Faktory snižující hrozbu:**
- ✅ Rostoucí ekologické povědomí
- ✅ Klesající ceny elektromobilů
- ✅ Rozšiřování nabíjecí infrastruktury

### 5. Rivalita mezi stávajícími konkurenty: VYSOKÁ A ROSTOUCÍ

**Faktory zvyšující rivalitu:**
- ❗ Rostoucí počet konkurentů (tradiční i noví výrobci)
- ❗ Vysoké fixní náklady výroby
- ❗ Boj o tržní podíl na rostoucím trhu
- ❗ Zvyšující se cenový tlak (zejména z Číny)

**Konkurenční výhody Tesly:**
- ✅ Silná značka a loajalita zákazníků
- ✅ Technologický náskok (software, baterie)
- ✅ Vlastní síť Superchargerů
- ✅ Vertikální integrace

## Strategické implikace pro Teslu

1. **Snížení závislosti na dodavatelích** - Pokračovat ve vertikální integraci (baterie, čipy)
2. **Posílení diferenciace** - Inovace v softwaru, autonomním řízení, ekosystému
3. **Budování bariér vstupu** - Rozšiřování sítě Superchargerů a servisních center
4. **Cenová strategie** - Postupné snižování cen díky úsporám z rozsahu
5. **Expanze na nové trhy** - Geografická expanze a vstup do nových segmentů

## Závěr

Porterův model pěti sil poskytuje Tesle (i jakémukoliv jinému podniku) strukturovaný rámec pro analýzu konkurenčního prostředí a formulaci strategie. V případě Tesly ukazuje na vysoce konkurenční prostředí, kde klíčem k úspěchu je kontinuální inovace, vertikální integrace a budování silného ekosystému.

![](../../obr\porter_diamant.png)
