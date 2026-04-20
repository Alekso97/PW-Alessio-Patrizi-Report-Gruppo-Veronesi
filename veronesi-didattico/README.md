# 🌱 Veronesi Sustainability Reports — Repository Didattico

> Repository di esempio per il corso universitario · **Non affiliato con Gruppo Veronesi S.p.A.**

Questo repository è un esempio didattico per mostrare come un'azienda pubblica può distribuire i propri report di sostenibilità tramite GitHub, garantendo versionamento, accesso libero e tracciabilità.

---

## 📁 Struttura del repository

```
veronesi-sustainability/
├── index.html              ← Sito web dimostrativo
├── README.md               ← Questo file
└── reports/
    ├── dnf-2023.pdf        ← Dichiarazione Non Finanziaria 2023
    ├── dnf-2022.pdf        ← Dichiarazione Non Finanziaria 2022
    ├── dnf-2021.pdf        ← Dichiarazione Non Finanziaria 2021
    └── annual-report-2023.pdf ← Annual Report 2023
```

---

## 🚀 Come usare questo progetto

### 1. Clona il repository
```bash
git clone https://github.com/TUO-USERNAME/veronesi-sustainability.git
cd veronesi-sustainability
```

### 2. Apri il sito in VS Code
```bash
code .
```
Poi apri `index.html` con **Live Server** (installa l'estensione "Live Server" di Ritwick Dey).

### 3. Aggiungi i PDF dei report
Inserisci i file PDF reali nella cartella `reports/`. I link nel sito puntano automaticamente a questi file.

---

## 🔗 Come collegare i PDF da GitHub (Raw URL)

Per far scaricare un PDF direttamente dal sito, usa il link **Raw** di GitHub:

```https://raw.githubusercontent.com/TUO-USERNAME/REPO-NAME/main/reports/nome-file.pdf

```

### Esempio nel codice HTML:
```html
<a href="https://github.com/Alekso97/PW-Alessio-Patrizi-Report-Gruppo-Veronesi/tree/main/veronesi-didattico"
   download>
  Scarica DNF 2023
</a>
```

---

## 📊 Framework ESG utilizzati da Gruppo Veronesi

| Framework | Descrizione |
|-----------|-------------|
| **GRI Standards** | Global Reporting Initiative — rendicontazione non finanziaria |
| **DNF** | Dichiarazione Non Finanziaria (D.Lgs. 254/2016) |
| **SDGs** | Obiettivi di Sviluppo Sostenibile ONU |
| **TCFD** | Task Force on Climate-related Financial Disclosures |

---

## 🎓 Note didattiche per gli studenti

Questo progetto dimostra:
1. **Come pubblicare un sito statico su GitHub Pages**
2. **Come gestire file binari (PDF) con Git LFS o raw links**
3. **La struttura di un sito corporate con sezione sostenibilità**
4. **Il pattern di rendicontazione ESG nelle grandi imprese italiane**


---

## ⚡ Estensioni VS Code consigliate

```json
{
  "recommendations": [
    "ritwickdey.LiveServer",
    "esbenp.prettier-vscode",
    "formulahendry.auto-close-tag",
    "ms-vscode.live-server"
  ]
}
```

---

## 📄 Licenza

Questo progetto è rilasciato sotto licenza **MIT** per uso didattico.  
I loghi e marchi di Gruppo Veronesi sono di proprietà di Gruppo Veronesi S.p.A.

---

*Corso di L-31 Informatica per le Aziende digitali · Università telematica Unipegato · A.A. 2025/2026*
