# muse-avatars

A collection of **Muse avatar themes** — custom avatar images and animations created for [Meta Muse](https://www.meta.ai/), the personal AI assistant.

Themes are grouped **by series**: one folder per series, and inside it one folder per theme. Each theme folder holds a still avatar image (`avatar.webp`). The active theme also includes its full set of animated states (MP4) — the little animations Muse cycles through at the top of the chat: idle, working, creating, and celebrating.

> 🇫🇷 Version française plus bas.

## Series: Neko Hoodie

Streetwear cat-girl: black cropped hoodie with cat ears, long pale-pink braids, gloves and thigh tattoos — two variations generated from one reference artwork.

| Theme | Preview | Style | Status |
|---|---|---|---|
| **neko-hoodie-1** | ![neko-hoodie-1](neko-hoodie/neko-hoodie-1/avatar.webp) | Anime 3D style — cat-ear hoodie, pink braids, tattoos | ✅ Active in Muse |
| **neko-hoodie-2** | ![neko-hoodie-2](neko-hoodie/neko-hoodie-2/avatar.webp) | Pixel art version | Available |

## Series: Kimono

A swordswoman in a white kimono with red trim, an ornate hair ornament, and a katana, among cherry blossoms — four variations generated from one reference artwork.

| Theme | Preview | Style | Status |
|---|---|---|---|
| **kimono-1** | ![kimono-1](kimono/kimono-1/avatar.webp) | Anime 3D style — white kimono, red bow belt, katana | Available, animations included |
| **kimono-2** | ![kimono-2](kimono/kimono-2/avatar.webp) | Flat anime — closest to the reference artwork | Available |
| **kimono-3** | ![kimono-3](kimono/kimono-3/avatar.webp) | Semi-realistic render | Available |
| **kimono-4** | ![kimono-4](kimono/kimono-4/avatar.webp) | Pixel art version | Available |

## Series: Anime Angel

Four variations of the same angel, generated from one reference artwork.

| Theme | Preview | Style | Status |
|---|---|---|---|
| **anime-angel-1** | ![anime-angel-1](anime-angel/anime-angel-1/avatar.webp) | Anime — blonde angel, white satin dress, feathered wings, pink halo | Available, animations included |
| **anime-angel-2** | ![anime-angel-2](anime-angel/anime-angel-2/avatar.webp) | Anime — closest to the reference artwork, wings fully spread | Available |
| **anime-angel-3** | ![anime-angel-3](anime-angel/anime-angel-3/avatar.webp) | Semi-realistic render — softer light, brighter wings | Available |
| **anime-angel-4** | ![anime-angel-4](anime-angel/anime-angel-4/avatar.webp) | Pixel art version of the angel | Available |

## Animations

The active theme's `animations/` folder holds the animated states Muse rotates through depending on what it is doing:

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
├── anime-angel/              ← one folder per series
│   ├── anime-angel-1/        ← one folder per theme
│   │   ├── avatar.webp
│   │   └── animations/
│   │       ├── idle.mp4
│   │       ├── working.mp4
│   │       ├── making-something.mp4
│   │       └── milestone.mp4
│   ├── anime-angel-2/
│   │   └── avatar.webp
│   ├── anime-angel-3/
│   │   └── avatar.webp
│   └── anime-angel-4/
│       └── avatar.webp
└── kimono/
    ├── kimono-1/
    │   ├── avatar.webp
    │   └── animations/
    │       ├── idle.mp4
    │       ├── working.mp4
    │       ├── making-something.mp4
    │       └── milestone.mp4
    ├── kimono-2/
    │   └── avatar.webp
    ├── kimono-3/
    │   └── avatar.webp
    └── kimono-4/
        └── avatar.webp
└── neko-hoodie/
    ├── neko-hoodie-1/
    │   └── avatar.webp
    └── neko-hoodie-2/
        └── avatar.webp
```

## Using a theme

Ask Muse to switch: generate a new avatar from a description or a reference image, pick the option you like, and it becomes the live avatar — animations included. Previously generated themes kept in this repository can be restored at any time.

---

## 🇫🇷 Français

Une collection de **thèmes d'avatar pour Muse** — images et animations d'avatar personnalisées, créées pour [Meta Muse](https://www.meta.ai/), l'assistant personnel.

Les thèmes sont regroupés **par série** : un dossier par série, et dedans un dossier par thème. Chaque dossier de thème contient une image d'avatar (`avatar.webp`). Le thème actif contient aussi toutes ses animations (MP4) : celles que Muse fait défiler en haut de la discussion selon ce qu'il fait — repos, travail, création, célébration.

**Série Neko Hoodie** — streetwear oreilles de chat : hoodie noir court à oreilles de chat, longues tresses rose pâle, gants et tatouages sur les cuisses. Deux variantes :
- **neko-hoodie-1** — style anime 3D. ✅ Actif dans Muse.
- **neko-hoodie-2** — version pixel art.

**Série Kimono** — une épéiste en kimono blanc aux bordures rouges, parure de cheveux ornée et katana, parmi les fleurs de cerisier. Quatre variantes générées d'une même illustration :
- **kimono-1** — style anime 3D. Animations incluses.
- **kimono-2** — anime plat, le plus proche de l'illustration de référence.
- **kimono-3** — rendu semi-réaliste.
- **kimono-4** — version pixel art.

**Série Anime Angel** — quatre variantes du même ange, générées à partir d'une seule image de référence :
- **anime-angel-1** — style anime, ange blonde en robe blanche satinée, ailes de plumes, auréole rose. Animations incluses.
- **anime-angel-2** — style anime, le plus proche de l'illustration de référence, ailes grandes ouvertes.
- **anime-angel-3** — rendu semi-réaliste, lumière plus douce, ailes plus lumineuses.
- **anime-angel-4** — version pixel art de l'ange.

## License

Released under the [MIT License](LICENSE). The artwork is AI-generated.
