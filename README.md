# Integrated Implantation Score — Prototype

A mobile-first prototype calculator implementing an IVF **Integrated Implantation Score** that combines three domains:

- **Patient prognosis** — SART / McLernon IVF prediction model (0–10)
- **Embryo morphology** — rule-based Baczkowski (Day 3) / Gardner (Day 5) rubric (0–10)
- **Endometrial receptivity** — Endo-R ultrasound score (0–10)

```
Integrated = (SART / 10) × (Embryo + Endo-R) / 2
```

> ⚠ **Research & educational prototype — not validated for clinical use.**
> Derived from a single-center pilot study (n = 46, biochemical-pregnancy endpoint).
> Not tested against clinical pregnancy or live birth. Must not guide treatment decisions.

**Authors:** Bilen E, Okyay RE — Dokuz Eylül University, Department of Obstetrics and Gynecology.

Open `index.html` in any browser, or use the live version (add to home screen for an app-like experience).
