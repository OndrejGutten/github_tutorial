# **GitHub v VS Code – Rýchly Tutoriál**

## **1) Commity a ich návrat**

- V **Source Control (Ctrl + Shift + G)** pridajte súbory (`+`) a urobte commit (`✓` s popisom).
- Ak chcete **vrátiť projekt do staršej verzie**, otvorte **Commit History** (`... → View History`), kliknite pravým na commit a vyberte **Reset to Commit**.

---

## **2) Lokálne vs. vzdialené repozitáre**

- Lokálny repozitár **existuje len na vašom PC**, vzdialený na **GitHube**.
- **Push (odoslanie)**: `... → Push` synchronizuje zmeny do GitHubu.
- **Pull (stiahnutie)**: `... → Pull` aktualizuje lokálny repozitár, ak sa na GitHube niečo zmenilo.

### **👉 Príklad rozdielu:**

1. Urobte commit a **nepushnite ho** → Zmena je iba **lokálne**.
2. Pozrite si GitHub → Zmena tam **nie je**.
3. Kliknite na `... → Push` → Teraz sú dáta **synchronizované**.

---

## **3) Vytvorenie a prepínanie medzi branchami**

- Novú **vetvu (branch)** vytvoríte:
  1. Kliknite v ľavom dolnom rohu na **vetvu**.
  2. Vyberte **Create New Branch** → Pomenujte ju (napr. `novy-feature`).
- **Prepínanie medzi vetvami**: Kliknite na názov vetvy a zvoľte inú vetvu.

---

## **4) Merging v GitHube**

- Po pushnutí **branch** na GitHub prejdite do **Pull Requests**.
- Kliknite **New Pull Request** → vyberte zdrojovú vetvu (`novy-feature`) a cieľovú (`main`).
- Kliknite **Merge Pull Request** → Zmeny sa aplikujú do `main`.

---

## **5) Aktualizácia branch pred spojením do main**

**Problém:** Ak sa `main` zmenil po vytvorení vašej vetvy, nemôžete ju spojiť.

**Riešenie v VS Code:**

1. **Prepnutie na main**: Kliknite na názov branchu a vyberte `main`.
2. **Stiahnutie nových zmien**: `... → Pull`.
3. **Prepnutie späť na vetvu**: Kliknite a vyberte `novy-feature`.
4. **Spojenie main do vetvy**: `... → Merge Branch` → vyberte `main`.
5. **Push zmien** a následne merge na GitHube.

---

🎉 **Hotovo!** Teraz máte prehľad o práci s GitHubom priamo v VS Code! 🚀
