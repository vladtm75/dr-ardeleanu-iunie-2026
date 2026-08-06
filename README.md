# Dr. Ardeleanu - Rezultate Financiare Iunie 2026

Raport de grup consolidat: Vanzari, P&L si Cashflow. Toate rapoartele sunt gazduite in acest repo, in spatele unui singur gate de parola pe pagina principala.

Publicat prin GitHub Pages: https://vladtm75.github.io/dr-ardeleanu-iunie-2026/

## Continut

| Fisier | Raport | Sursa originala |
|---|---|---|
| `index.html` | Landing page + gate de parola (sessionStorage `reportsAuth`) | — |
| `sales-mobile.html` / `sales-desktop.html` | Analiza vanzari Iulie 2026 | vladtm75/raport-sales-dr-ardeleanu |
| `pl-mobile.html` / `pl-desktop.html` | Analiza P&L / EBITDA Iunie 2026 | biancabajenaru/Dr.Ardeleanu-Analiza-Financiara-Iunie |
| `cashflow-summary.html` / `cashflow-report.html` + `cashflow-report.js` | Cashflow & Treasury Iunie 2026 | acest repo |

Fiecare pagina de raport verifica `sessionStorage.reportsAuth` si redirectioneaza catre `index.html` daca nu s-a introdus parola.

Sursa datelor: P&L IUNIE 2026 V1.8.1.xlsx (sheet Cashflow, ultima coloana Actual).
Actualizat: 06.08.2026 (rebuild Pages).
