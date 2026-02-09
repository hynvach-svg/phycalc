# Fyzikální kalkulačka – 1. ročník SŠ

Jednoduchá webová **fyzikální kalkulačka** určená pro studenty 1. ročníku středních škol.  
Aplikace umožňuje počítat základní úlohy z mechaniky pomocí známých fyzikálních vzorců.

Aplikace funguje:
- jako běžná webová stránka
- jako **instalovatelná aplikace (PWA)**
- i **offline**

---

## ✨ Funkce

Aplikace obsahuje výpočty pro:

1. **Rovnoměrný pohyb**
   - rychlost `v`
   - dráha `s`
   - čas `t`

2. **Rovnoměrně zrychlený / zpomalený pohyb**
   - rychlost `v`, počáteční rychlost `v₀`
   - zrychlení `a`
   - čas `t`
   - dráha `s`

3. **Pohyb po kružnici**
   - rychlost `v`
   - poloměr `r`
   - perioda `T`
   - dostředivé zrychlení `aₙ`
   - dostředivá síla `Fₙ`
   - hmotnost `m`

4. **Dynamika (Newtonovy zákony)**
   - síla `F`
   - hmotnost `m`
   - zrychlení `a`

5. **Hybnost**
   - hybnost `p`
   - změna hybnosti `Δp`

6. **Tření**
   - normálová síla `N`
   - třecí síla `Fₜ`
   - třecí koeficient `μ`

7. **Gravitační síla**
   - gravitační síla `F_g`
   - hmotnosti `m₁`, `m₂`
   - vzdálenost `r`

U každého výpočtu se zobrazí:
- **výsledek**
- **použitý vzorec**

---

## 🌙 Tmavý režim

- přepínání pomocí tlačítka 🌙 / ☀️
- nastavení se ukládá do `localStorage`
- respektuje systémové nastavení uživatele

---

## 📱 Instalace jako aplikace (PWA)

Aplikace je **Progressive Web App**.

### Instalace:
1. Otevřete aplikaci v prohlížeči (Chrome / Edge)
2. Klikněte na **„Instalovat aplikaci“**
3. Aplikace se přidá:
   - na plochu (PC)
   - na domovskou obrazovku (Android)

### Vlastnosti PWA:
- běží **offline**
- spouští se **na celou obrazovku**
- nepotřebuje App Store

---

## 🧠 Jak aplikace funguje

- Každá kapitola má:
  - výběr veličiny, kterou chceme spočítat
  - vstupní pole pro známé hodnoty
- Po kliknutí na **„Spočítat“**:
  - JavaScript vyhodnotí dostupná data
  - zvolí správný vzorec
  - zobrazí výsledek a použitý vztah

Použité konstanty:
- tíhové zrychlení: `g = 9.81 m/s²`
- gravitační konstanta: `G = 6.674 × 10⁻¹¹`

---
