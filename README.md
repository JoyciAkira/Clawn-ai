# 🦞 Clawn - AI Assistant Framework

Fork di [OpenClaw](https://github.com/openclaw/openclaw) specializzato per automazione enterprise e vertical AI solutions.

## Visione

Clawn è un assistente AI personale framework progettato per essere specializzato in verticali specifici:
- **Enterprise AI Copilot** - Automazione flussi aziendali
- **E-commerce Commerce Ops** - Gestione negozi online  
- **Cybersecurity SOC Assistant** - Monitoraggio sicurezza
- **Fintech Financial Ops** - Operazioni finanziarie

## Struttura del Progetto

```
clawn/
├── README.md                 # Questo file
├── MONETIZATION_PLAN.md     # Piano di monetizzazione dettagliato
├── docs/                    # Documentazione (da completare)
├── specs/                   # Specifiche tecniche (da completare)
└── src/                     # Codice sorgente OpenClaw (già clonato)
```

## Come Avviare

### 1. Dipendenze

```bash
cd src
pnpm install
```

### 2. Configurazione

Copia `.env.example` in `.env` e configura le API keys:

```bash
cp src/.env.example src/.env
# Modifica src/.env con le tue API keys
```

### 3. Avviare il Gateway

```bash
cd src
pnpm gateway
```

### 4. Accedere all'Interfaccia

Apri http://localhost:3000 nel browser.

## Caratteristiche Principali

- **Multi-channel**: WhatsApp, Telegram, Slack, Discord, Google Chat, Signal, iMessage, BlueBubbles, IRC, Microsoft Teams, Matrix, Feishu, LINE, Mattermost, Nextcloud Talk, Nostr, Synology Chat, Tlon, Twitch, Zalo, Zalo Personal, WeChat, WebChat
- **Voice Wake + Talk Mode**: attivazione vocale su macOS/iOS, modalità conversazione continua su Android
- **Canvas + A2UI**: workspace visivo guidato dall'agente
- **Multi-agent routing**: routing di canali/account/peer verso agenti isolati
- **Skills platform**: bundled, managed, e workspace skills
- **Gateway WebSocket**: piano di controllo unico per sessioni, canali, strumenti e eventi

## Piano di Monetizzazione

Vedi [MONETIZATION_PLAN.md](./MONETIZATION_PLAN.md) per il dettaglio completo.

## Stack Tecnico

- **Runtime**: Node 22+ (TypeScript)
- **Package Manager**: pnpm/bun
- **Database**: SQLite (local), PostgreSQL (cloud)
- **AI Providers**: OpenAI, Anthropic, Google, ecc.

## Licenza

MIT - derivato da [OpenClaw](https://github.com/openclaw/openclaw)

---

*Basato su analisi di TrustMRR, Acquire.com e dati VC 2026*