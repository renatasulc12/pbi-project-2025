# PBI Projekt – Engeto

Tento projekt je součástí kurzu **ENGETO Datová Akademie** a je zaměřen na procvičení Power BI vizualizací vlastního datasetu.

## Cíl projektu

Cílem projektu je analyzovat **fakturaci Městské části Praha 12** v letech **2020–2025**. 
Dashboard slouží jako přehledný nástroj pro:
- sledování vývoje fakturace,
- porovnání objemu výdajů podle jednotlivých agend (tzv. knih KDF),
- vyhodnocení spolupráce s dodavateli,
- zobrazení detailních informací o jednotlivých fakturách. 

> ℹ️ **Poznámka:** Data za rok 2025 jsou nekompletní a zahrnují pouze období **do května 2025**.

---

## Použitá data

Zdrojová data pochází z veřejně dostupného datasetu **faktur Městské části Praha 12**, který obsahuje základní informace o jednotlivých fakturách: 
https://opendata.praha.eu/organizations/praha-12

---

## Postup zpracování

- **Import dat** - 5 CSV souborů (2020–2025) pomocí kombinace souborů z jedné složky 
- **Transformace dat v Power Query** - základní úprava datových typů (např. datum úhrady jako "datum", fakturované a uhrazené částky jako "desetinné číslo", atd.), přejmenování a čištění sloupců, … 
- **DAX míry a výpočty** - např. *Fakturováno celkem (CZK)*, *Uhrazeno celkem (CZK)*, *Počet faktur* 
- **Návrh vizuálů a rozložení dashboardu** - KPI karty, tabulky, matice, sloupcové a prstencové grafy 
- **Tvorba interaktivity** - slicery, navigační tlačítka, popisky, vložení URL pod logo Praha 12 
- **Grafická úprava** - písmo *Segoe UI* a jeho kombinace, barvy dle grafického manuálu MČ Praha 12 

---

## Autor

Renata Šulcová  
[GitHub: renatasulc12](https://github.com/renatasulc12)