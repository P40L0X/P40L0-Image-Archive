# P40L0 Image Archive

Archivio centralizzato di immagini con hotlink facile per siti esterni.

## 📁 Struttura cartelle

- **Nexusmods/** - Immagini per Nexusmods
- **Patreon/** - Immagini per Patreon
- **ResetEra/** - Immagini per ResetEra

## 🔗 Come generare un hotlink

Una volta caricata un'immagine, usa questo formato URL:

```
https://raw.githubusercontent.com/P40L0X/P40L0-Image-Archive/main/[CARTELLA]/[NOME_IMMAGINE]
```

### Esempi:

**Immagine in Nexusmods:**
```
https://raw.githubusercontent.com/P40L0X/P40L0-Image-Archive/main/Nexusmods/screenshot.jpg
```

**Immagine in Patreon:**
```
https://raw.githubusercontent.com/P40L0X/P40L0-Image-Archive/main/Patreon/preview.png
```

**Immagine in ResetEra:**
```
https://raw.githubusercontent.com/P40L0X/P40L0-Image-Archive/main/ResetEra/image.gif
```

## 📝 Utilizzo HTML

```html
<img src="https://raw.githubusercontent.com/P40L0X/P40L0-Image-Archive/main/Nexusmods/screenshot.jpg" alt="Screenshot">
```

## 📋 Markdown

```markdown
![Alt text](https://raw.githubusercontent.com/P40L0X/P40L0-Image-Archive/main/Patreon/preview.png)
```

## ⚙️ Note tecniche

- **Formato URL:** Raw content di GitHub (perfetto per hotlink)
- **Limite per file:** 100MB per singolo file
- **Limite repository:** 100GB totali
- **Disponibilità:** 99.9% uptime (server GitHub)
- **Cache:** GitHub può cachare i file, potrebbe volerci qualche minuto per propagare le modifiche

## 🚀 Workflow rapido

1. Carica l'immagine nella cartella appropriata
2. Copia il nome del file
3. Sostituisci `[CARTELLA]` e `[NOME_IMMAGINE]` nel template URL
4. Incolla l'hotlink dove serve

---

**Creato:** 2026-07-24 | Archivio hotlink centralizzato
