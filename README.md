# muse-avatars

A collection of **Muse avatar themes** — custom avatar images and animations created for [Meta Muse](https://www.meta.ai/), the personal AI assistant.

Themes are grouped **by series**: one folder per series, and inside it one folder per theme. Each theme folder holds a still avatar image (`avatar.webp`). The active theme also includes its full set of animated states (MP4) — the little animations Muse cycles through at the top of the chat: idle, working, creating, and celebrating.

> 🇫🇷 Version française plus bas.

## Series: Anime Angel

Four variations of the same angel, generated from one reference artwork — saved here so they can be swapped back at any time.

| Theme | Preview | Style | Status |
|---|---|---|---|
| **anime-angel-1** | ![anime-angel-1](anime-angel/anime-angel-1/avatar.webp) | Anime — blonde angel, white satin dress, feathered wings, pink halo | ✅ Active in Muse, animations included |
| **anime-angel-2** | ![anime-angel-2](anime-angel/anime-angel-2/avatar.webp) | Anime — closest to the reference artwork, wings fully spread | Available |
| **anime-angel-3** | ![anime-angel-3](anime-angel/anime-angel-3/avatar.webp) | Semi-realistic render — softer light, brighter wings | Available |
| **anime-angel-4** | ![anime-angel-4](anime-angel/anime-angel-4/avatar.webp) | Pixel art version of the angel | Available |

## Animations (anime-angel-1)

The `anime-angel/anime-angel-1/animations/` folder holds the animated states Muse rotates through depending on what it is doing:

- `idle.mp4` — at rest (also used while connecting)
- `working.mp4` — working on a task
- `making-something.mp4` — creating or building something
- `milestone.mp4` — celebrating a milestone

## Repository structure

```
muse-avatars/
├── README.md
├── LICENSE
├── CHANGELOG.md
└── anime-angel/              ← one folder per series
    ├── anime-angel-1/        ← one folder per theme
    │   ├── avatar.webp
    │   └── animations/
    │       ├── idle.mp4
    │       ├── working.mp4
    │       ├── making-something.mp4
    │       └── milestone.mp4
    ├── anime-angel-2/
    │   └── avatar.webp
    ├── anime-angel-3/
    │   └── avatar.webp
    └── anime-angel-4/
        └── avatar.webp
```

## Using a theme

Ask Muse to switch: generate a new avatar from a description or a reference image, pick the option you like, and it becomes the live avatar — animations included. Previously generated themes kept in this repository can be restored at any time.

---

## 🇫🇷 Français

Une collection de **thèmes d'avatar pour Muse** — images et animations d'avatar personnalisées, créées pour [Meta Muse](https://www.meta.ai/), l'assistant personnel.

Les thèmes sont regroupés **par série** : un dossier par série, et dedans un dossier par thème. Chaque dossier de thème contient une image d'avatar (`avatar.webp`). Le thème actif contient aussi toutes ses animations (MP4) : celles que Muse fait défiler en haut de la discussion selon ce qu'il fait — repos, travail, création, célébration.

**Série Anime Angel** — quatre variantes du même ange, générées à partir d'une seule image de référence, sauvegardées ici pour pouvoir y revenir à tout moment :

- **anime-angel-1** — style anime, ange blonde en robe blanche satinée, ailes de plumes, auréole rose. ✅ Actif dans Muse, animations incluses.
- **anime-angel-2** — style anime, le plus proche de l'illustration de référence, ailes grandes ouvertes.
- **anime-angel-3** — rendu semi-réaliste, lumière plus douce, ailes plus lumineuses.
- **anime-angel-4** — version pixel art de l'ange.

## License

Released under the [MIT License](LICENSE). The artwork is AI-generated.
