# Git - Základné operácie

## 1. Vytvorenie súboru a prvý commit

- V _Source Control_ pridaj súbor, ktorý chceš trackovať.
- Vytvor **commit**.
- Zmeny v trackovaných súboroch sú teraz súčasťou histórie tohto repozitára.

## 2. Výber zmien na commit

- V _Source Control_ vyber, ktoré zmeny chceš commitnúť.
- Zmeny, ktoré nechceš commitnúť, môžeš **vymazať** alebo ponechať v pracovnom stave.

## 3. Návrat k historickému commitu

- Otvor _Source Control_.
- Zvoľ **checkout detached** pre vybraný commit.
- Vidíš verziu súborov platnú v danom commite.

## 4. Synchronizácia s remote

- **Publish / Push / Sync** commit.
- Pozri sa na _GitHub_ – commity a momentálny stav sú teraz súčasťou **remote repozitára**.

## 5. Obojsmerná synchronizácia

- Ak sa niečo zmení na remote, môžeš:
  - V _Source Control_ spraviť **pull**.
  - Tvoje lokálne súbory sa teraz zmenia na verziu totožnú s remote.

## 6. Branch – pracovná verzia / nová feature

- Vytvorí sa **kópia** daného commitu a trackuje sa ako keby nový repozitár.
- Zmeny a commity v repozitári sú **samostatné** – najskôr lokálne, po pushnutí aj remote.

## 7. Simple merge

- Pridaj novú **feature** do novej branch.
- Vytvor **pull request** na _GitHube_.

## 8. Simple merge + zmeny v maine

- Pridaj novú **feature** do novej branch.
- Sprav **zmeny v starej feature v maine**.
- Vytvor **pull request** na _GitHube_.

## 9. Conflicted merge

- Vytvor novú **branch**.
- Pridaj novú **feature** + zmeň starú feature.
- Sprav iné **zmeny v starej feature v maine**.
- Vytvor **pull request** na _GitHube_.

## 10. Riešenie konfliktov

- Sprav **merge mainu do branch lokálne** – tým integruješ zmeny v _maine_, ktoré sa udiali odkedy bola vytvorená branch.
- **Manuálne** rozhodni všetky konflikty.
- Sprav **pull request** na _GitHube_ pre branch – teraz už bude schodný.

---

### ℹ️ Poznámka:

Ak chceš **zmeniť branch**, musíš:

- Commitnúť zmeny **alebo** ich **stashnúť**.
- Inými slovami, musíš sa rozhodnúť, čo urobiť s neuloženými zmenami.
