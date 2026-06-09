# Tree Testing AE

Piattaforma di tree testing per la nuova architettura informativa del portale Agenzia delle Entrate.

**Owner:** CXMSogei (migrato da roccajoe il 09/06/2026)  
**App partecipante:** https://cxmsogei.github.io/tree-testing-ae/  
**Dashboard admin:** https://cxmsogei.github.io/tree-testing-ae/admin.html  

## Stack
- Frontend: HTML/CSS/JS vanilla, design tokens Sogei AE (#323232, #fab600, Titillium Web)
- Storage: Firebase Realtime DB (tree-testing-ae)
- Hosting: GitHub Pages

## File
- `index.html` — app partecipante (welcome → profile screening → instructions → 10 task → final feedback)
- `admin.html` — dashboard con SVG pietree visualization
- `tree.json` — alberatura TO-BE (296 leaves, 12 macro-aree + Servizi rapidi)
- `tasks.json` — 18 task pool, config 3 profili × 30 = 90 partecipanti totali, screening enabled
