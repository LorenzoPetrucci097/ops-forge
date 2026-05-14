<div align="center">

# 🛡️ Cybersecurity Quiz

**Piattaforma di studio interattiva per la certificazione Cisco CyberOps Associate 200-201**

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
![HTML5](https://img.shields.io/badge/HTML5-single%20file-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![Cisco CyberOps](https://img.shields.io/badge/Cisco-CyberOps%20200--201-049fd8?logo=cisco&logoColor=white)

</div>

---

## 📖 Panoramica

Quiz interattivo single-file sviluppato come strumento di ripasso personale per la preparazione alla certificazione **Cisco CyberOps Associate 200-201** e per il ripasso generale in ambito Cybersecurity.

Nessuna dipendenza, nessun backend, nessun framework - un singolo file `.html` da aprire nel browser.

---

## ✨ Funzionalità

### 🎯 Simulazioni Cisco CyberOps 200-201
| Simulazione | Lingua | Domande | Fonte |
|---|---|---|---|
| Simulazione 1 | 🇮🇹 Italiano | 100 | CyberOps Core |
| Simulazione 2 | 🇮🇹 Italiano | 100 | Official Cert Guide - Omar Santos |
| Simulation 1 | 🇬🇧 English | 100 | CyberOps Core |
| Simulation 2 | 🇬🇧 English | 100 | Official Cert Guide - Omar Santos |

- ⏱️ **Timer da 120 minuti** con modalità esame e pratica libera
- 📊 **5 domini** con statistiche per-dominio al termine
- ✅ **Soglia superamento: 83%** (come l'esame reale)
- 🔀 **Shuffle randomizzato** delle domande e delle opzioni ad ogni sessione
- 💡 **Spiegazioni dettagliate** per ogni risposta

### 📚 Quiz a Unità Settimanali
- 10+ unità tematiche di ripasso generale in Cybersecurity
- Networking, Crittografia, Penetration Testing, SOC, Forensics e altro
- Modalità pratica con feedback immediato

### 🤖 AI Tutor integrato
- Tutor AI contestuale collegato via **OpenRouter**
- Conosce i tuoi progressi e le domande sbagliate
- Suggerisce dove concentrare lo studio
- Supporta qualsiasi modello LLM disponibile su OpenRouter

### 📈 Statistiche & Progressi
- Sidebar statistiche con **ring chart** per ogni simulazione
- Barre per-dominio con percentuale di correttezza
- Storico delle risposte sbagliate con toggle
- Dati persistiti in **localStorage** (nessun server richiesto)

---

## 🚀 Come usarlo

```bash
# 1. Clona la repository
git clone https://github.com/LorenzoPetrucci097/ops-forge.git

# 2. Apri il file nel browser
# Doppio click su "ops-forge.html"
# oppure
open "ops-forge.html"
```

> Nessuna installazione richiesta. Funziona offline dopo il primo caricamento.

### Configurazione AI Tutor (opzionale)
1. Ottieni una chiave API gratuita su [openrouter.ai](https://openrouter.ai)
2. Clicca sul terminale AI nella home page
3. Incolla la chiave → il tutor si attiva istantaneamente

---

## 🗂️ Struttura del Progetto

```
ops-forge.html          # Applicazione completa (single-file)
│
├── <style>                 # CSS - tema dark terminal, layout responsive
├── <body>
│   ├── #sidebar            # Sidebar di ripasso settimanale
│   ├── #stats-sidebar      # Sidebar statistiche & progressi
│   ├── #page-home          # Home - griglia unità + lancio simulazioni
│   ├── #page-quiz          # Modalità quiz unità
│   ├── #page-results       # Risultati quiz con analisi errori
│   └── #page-cyberops      # Motore simulazione esame CyberOps
│
└── <script>
    ├── QUIZ_DATA[]             # Domande unità (10+ unità tematiche)
    ├── CYBEROPS_QUESTIONS[]    # Bank A - 100 domande IT
    ├── CYBEROPS_QUESTIONS_B[]  # Bank B - 100 domande IT (Official Cert Guide)
    ├── CYBEROPS_QUESTIONS_A_EN[] # Bank A - 100 domande EN
    └── CYBEROPS_QUESTIONS_B_EN[] # Bank B - 100 domande EN (Official Cert Guide)
```

---

## 🎨 Stack Tecnico

| Tecnologia | Utilizzo |
|---|---|
| **HTML5** | Struttura e markup |
| **CSS3** | Tema dark terminal, variabili CSS, responsive |
| **Vanilla JavaScript** | Logica quiz, shuffle, localStorage, fetch API |
| **OpenRouter API** | AI Tutor (opzionale, bring-your-own-key) |

Zero dipendenze esterne · Zero framework · Zero build step

---

## 📋 Domini CyberOps 200-201

| # | Dominio | Peso Esame |
|---|---|---|
| 1 | Security Concepts | 20% |
| 2 | Security Monitoring | 25% |
| 3 | Host-Based Analysis | 20% |
| 4 | Network Intrusion Analysis | 20% |
| 5 | Security Policies & Procedures | 15% |

---

## 📜 Licenza

Questo progetto è distribuito sotto licenza **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

- ✅ Puoi condividere e adattare il materiale
- ✅ Devi sempre citare l'autore originale
- ❌ Non è consentito l'uso commerciale

Leggi la licenza completa: [creativecommons.org/licenses/by-nc/4.0](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 👤 Autore

**Lorenzo Petrucci**

Progetto sviluppato per esercitazione **Cisco CyberOps Associate 200-201** e materiale di ripasso in campo Cybersecurity.
Tutti i diritti riservati.

---

<div align="center">

*Realizzato con ☕ e tanta Cybersecurity*

</div>
