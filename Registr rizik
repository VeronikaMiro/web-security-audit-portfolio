# Bezpečnostní audit webové aplikace

## Projekt
Rezervační systém pro kadeřnictví (simulace)

## Auditor
Veronika Mirovská

## Rozsah auditu

Audit se zaměřuje na základní bezpečnostní aspekty webové aplikace:
- přihlašování
- přístupová práva
- formuláře
- logování
- ochrana dat
- zálohování
- GDPR

## Metodika

Audit byl proveden na základě:
- OWASP Top 10
- základních principů IT auditu
- běžných bezpečnostních standardů

---

## Shrnutí

Aplikace obsahuje několik běžných bezpečnostních rizik, která mohou ovlivnit ochranu dat a provoz systému. Nejzávažnější problémy jsou:

- chybějící ochrana proti opakovanému přihlašování
- nedostatečné řízení přístupů
- slabé logování bezpečnostních událostí

---

## Nálezy

### Nález 1: Neomezené pokusy o přihlášení

**Riziko:** Vysoké

**Popis:**
Systém neomezuje počet neúspěšných pokusů o přihlášení.

**Dopad:**
Možnost brute-force útoku na uživatelské účty.

**Doporučení:**
- zavést limit pokusů o přihlášení
- dočasné blokování účtu
- monitoring pokusů

---

### Nález 2: Slabá validace formulářů

**Riziko:** Střední

**Popis:**
Formulář přijímá nečekané znaky a dlouhé vstupy.

**Dopad:**
Riziko chyb v datech a potenciálních útoků.

**Doporučení:**
- validace na serveru
- omezení délky vstupu
- kontrola formátu dat

---

### Nález 3: Nedostatečné řízení přístupů

**Riziko:** Vysoké

**Popis:**
Není jasně definováno oddělení rolí (uživatel/admin).

**Dopad:**
Možnost neoprávněného přístupu k datům.

**Doporučení:**
- zavést role (user/admin)
- princip minimálních oprávnění

---

### Nález 4: Nedostatečné logování

**Riziko:** Střední

**Popis:**
Systém neukládá dostatečné informace o událostech.

**Dopad:**
Nemožnost dohledat incidenty.

**Doporučení:**
- logovat přihlášení, chyby, změny
- ukládat IP adresu a čas

---

### Nález 5: Nezdokumentované zálohy

**Riziko:** Střední

**Popis:**
Není jasné, zda a jak jsou data zálohována.

**Dopad:**
Riziko ztráty dat.

**Doporučení:**
- zavést zálohovací plán
- testovat obnovu dat

---

## Závěr

Aplikace vyžaduje zlepšení v oblasti:
- přihlašování
- řízení přístupů
- logování
- dokumentace procesů

Navržená opatření pomohou zvýšit bezpečnost a stabilitu systému.
