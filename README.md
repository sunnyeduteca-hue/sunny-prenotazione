[README.md](https://github.com/user-attachments/files/26176977/README.md)
# 🌈 Sunny on the Rainbow — Sistema AI Multi-canale

Sistema completo di gestione clienti, prenotazioni feste e assistente AI per **Sunny on the Rainbow** — centro famiglia con parco giochi, area bimbi, mini farm e family bar a Vanzaghello (MI).

---

## 🌐 Pagine del sito

| Pagina | URL | Descrizione |
|--------|-----|-------------|
| 🎂 Prenotazioni clienti | `/index.html` | Form prenotazione feste e chat AI |
| 🖥️ Totem | `/totem.html` | Schermo touch in loco per i visitatori |
| 📊 Dashboard | `/dashboard.html` | Statistiche e panoramica attività |
| 👩‍💼 Operatore | `/operatore.html` | Pannello gestione per lo staff |
| 📱 WhatsApp Business | `/whatsapp.html` | Dashboard messaggi WhatsApp |
| 🔒 Privacy | `/privacy.html` | Informativa sulla privacy |

---

## 🤖 Funzionalità AI

- **Chat AI** su sito, WhatsApp, Instagram, Messenger e Facebook
- **Knowledge Base** con 39 Q&A su prezzi, orari, regole e servizi
- **Prenotazione automatica** con verifica disponibilità slot (max 3 per fascia oraria)
- **Email automatica** con link PayPal per pagamento acconto (50%)
- **Biglietto di invito** generato automaticamente dopo il pagamento
- **Notifiche Telegram** per ogni nuovo messaggio ricevuto

---

## 💳 Flusso prenotazione completo

```
Cliente compila il form
        ↓
Verifica disponibilità slot
        ↓
Salva prenotazione + Google Calendar
        ↓
📧 Email con link PayPal acconto (50%)
        ↓
Cliente paga su PayPal
        ↓
🎂 Biglietto di invito generato automaticamente
        ↓
📧 Email con biglietto al cliente
```

---

## 🔗 Webhook n8n attivi

| Webhook | URL | Descrizione |
|---------|-----|-------------|
| WhatsApp | `/webhook/webhook-whatsapp` | Messaggi WhatsApp Business |
| Instagram | `/webhook/webhook-instagram` | Messaggi Instagram |
| Messenger | `/webhook/webhook-messenger` | Messaggi Messenger |
| Chat web | `/webhook/webhook-chat` | Chat dal sito |
| Prenotazione | `/webhook/prenotazione-compleanno` | Form prenotazione |
| Biglietto | `/webhook/create-birthday-card` | Genera biglietto |

---

## 💰 Listino prezzi 2026

| Pacchetto | Mer/Ven | Sab/Dom/Festivi |
|-----------|---------|-----------------|
| Fai da Te | 235€ | 275€ |
| Festa Sunny | 315€ | 360€ |
| Festa con Merenda | 275€ | 325€ |

**Acconto:** 50% del totale, pagabile via PayPal  
**Extra:** +30€ giardino esterno (apr-ott) | +30% dal 2° festeggiato  
**Bambini extra:** 8€ (3+ anni) | 6€ (1-2 anni) | gratis sotto 1 anno

---

## 📅 Orari

- **Feste:** Mer/Ven 16:30–19:00 | Sab/Dom/Festivi 15:00–18:00
- **Apertura pubblica:** Mer–Dom 15:30–19:00 | Lun–Mar chiusi
- **Slot disponibili:** Mattino 10–13 | Pomeriggio | Sera 19–22

---

## 🛠️ Tecnologie utilizzate

- **n8n** — automazione workflow e webhook
- **OpenAI GPT-4o-mini** — AI conversazionale
- **Google Sheets** — database prenotazioni e conversazioni
- **Google Calendar** — calendario eventi feste
- **PayPal Business API** — pagamento acconti
- **Gmail** — invio email automatiche
- **Meta API** — WhatsApp, Instagram, Messenger
- **GitHub Pages** — hosting sito statico gratuito

---

## 📞 Contatti

**Sunny on the Rainbow**  
📍 Via Giacomo Brodolini 3, 20020 Vanzaghello (MI)  
📞 351 910 3655  
📧 info@sunnyontherainbow.it  
🌐 www.sunnyontherainbow.it

---

*Sistema sviluppato con ❤️ per Sunny on the Rainbow*
