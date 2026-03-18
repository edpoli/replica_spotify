# 🎵 Replica Spotify

Clone statico dell'interfaccia di Spotify, costruito con HTML e Bootstrap 5. Riproduce il layout della web app — sidebar di navigazione, griglia di card, player bar fissa in basso — come esercizio di studio su Bootstrap.


🔗 **[Demo live](https://replica-spotify-six.vercel.app/)**
---

## Panoramica

Il progetto replica la struttura visiva di Spotify Web Player: una navbar con sidebar offcanvas per la navigazione, una sezione principale con griglie responsive di card per le playlist, e un player bar fisso in basso con controlli di riproduzione, barra di avanzamento e volume. Il layout è completamente responsive grazie alla griglia Bootstrap.

## Funzionalità

- **Sidebar offcanvas** — Menu laterale a scomparsa con navigazione (Home, Cerca, Libreria, Playlist), artisti ascoltati di recente e azioni rapide.
- **Griglia card responsive** — Le card si adattano da 2 colonne su mobile a 6 su desktop, replicando il layout di Spotify.
- **Player bar fissa** — Footer sticky con copertina album, info brano, controlli di riproduzione (play, skip, shuffle, repeat), barra di avanzamento e controllo volume.
- **Sfondo gradiente** — Background con gradiente rosso-viola ispirato ai temi di Spotify.

## Tech Stack

| Tecnologia | Ruolo |
|---|---|
| **HTML5** | Struttura semantica |
| **Bootstrap 5.3** | Griglia, navbar, offcanvas, utilities |
| **CSS custom** | Gradiente, barre progresso, player cover |
| **Bootstrap Icons** | Icone player e navigazione |
| **Font Awesome 7** | Icone Spotify e azioni |
| **Google Fonts** | Montserrat |

## Struttura del Progetto

```
replica_spotify/
├── index.html          # Pagina principale
├── style.css           # Stili custom
└── immagini/           # Immagini copertine e logo
```

## Utilizzo

Sito statico, nessuna build richiesta:

```bash
# Con Python
python3 -m http.server 8000

# Oppure con VS Code Live Server
```

## Licenza

MIT
