# New Intermedia AI Blog

Blog ufficiale di **New Intermedia AI** - Analisi e approfondimenti su intelligenza artificiale, tecnologia, diritto e innovazione digitale.

## 🌐 Visita il Blog

**[https://newintermediai.github.io/blog/](https://newintermediai.github.io/blog/)**

## 📚 Contenuti

Il blog tratta temi all'intersezione tra tecnologia e diritto:

- **Intelligenza Artificiale** - Impatto sul lavoro, etica, regolamentazione
- **Blockchain e registri decentralizzati** - Certificazioni, proprietà digitale, smart contract
- **Diritto digitale** - Privacy, proprietà intellettuale, responsabilità
- **Innovazione tecnologica** - Trend, analisi, casi studio

## 📝 Articolo in Evidenza

### Revicta e il caso TerraVision vs Google Earth
*Come la data certa su registro decentralizzato avrebbe cambiato la storia*

Un'analisi di come un sistema di notarizzazione digitale come Revicta avrebbe potuto cambiare l'esito della controversia tra TerraVision e Google Earth, dimostrando l'importanza della prova tecnica temporale nei contenziosi sulla proprietà intellettuale.

## 🛠️ Tecnologie

- **[Jekyll](https://jekyllrb.com/)** - Generatore di siti statici
- **[GitHub Pages](https://pages.github.com/)** - Hosting gratuito
- **Tema**: Minima (personalizzato)

## 🚀 Setup Locale

Per testare il blog in locale:

```bash
# Clone del repository
git clone https://github.com/newintermediai/newintermediaai.github.io-blog.git
cd newintermediaai.github.io-blog

# Installa le dipendenze
bundle install

# Avvia il server di sviluppo
bundle exec jekyll serve
```

Il blog sarà disponibile su `http://localhost:4000/blog/`

## 📁 Struttura del Progetto

```
├── _config.yml              # Configurazione Jekyll
├── _posts/                  # Articoli del blog
│   └── 2026-07-22-revicta-terravision.md
├── _layouts/                # Layout HTML
│   ├── default.html
│   ├── post.html
│   └── page.html
├── assets/
│   ├── css/style.css        # Stili personalizzati
│   └── images/              # Immagini
├── index.md                 # Pagina principale
├── about.md                 # Pagina "Chi Siamo"
└── 404.md                   # Pagina errore
```

## ✍️ Come Pubblicare un Nuovo Articolo

1. Crea un nuovo file in `_posts/` con il formato: `YYYY-MM-DD-titolo-articolo.md`
2. Aggiungi il front matter YAML:

```yaml
---
layout: post
title: "Titolo dell'articolo"
subtitle: "Sottotitolo opzionale"
date: YYYY-MM-DD
author: "New Intermedia AI"
image: /assets/images/immagine.png
categories: [categoria1, categoria2]
tags: [tag1, tag2, tag3]
---

Contenuto dell'articolo in Markdown...
```

3. Carica l'immagine in `assets/images/`
4. Commit e push su GitHub

## 📄 Licenza

© 2026 New Intermedia AI. Tutti i diritti riservati.

## 🔗 Link Utili

- [Sito Principale](https://newintermediai.github.io)
- [Blog](https://newintermediai.github.io/blog/)
- [Feed RSS](https://newintermediai.github.io/blog/feed.xml)
