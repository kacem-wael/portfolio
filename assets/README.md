# Portfolio Assets

Drop your **pictures and videos** into the matching folder below. I'll wire whatever
you add into `portfolio.html`. You don't need to touch any code — just follow the
**file-naming convention** and the media will show up automatically on the site.

## Naming convention (per folder)

Inside any project/event/experience folder, use these exact names:

| File name        | What it becomes on the site                                  |
|------------------|--------------------------------------------------------------|
| `cover.jpg`      | Main visual of the card (replaces the letter monogram tile). |
| `gallery-1.jpg`  | 1st thumbnail in the gallery (click = fullscreen lightbox).  |
| `gallery-2.jpg`  | 2nd thumbnail. …and so on up to `gallery-6.jpg`.             |
| `demo.mp4`       | Embedded video player (screen recording / demo / clip).     |
| `poster.jpg`     | *(optional)* still frame shown before the video plays.       |
| `links.md`       | *(optional)* extra links — see below.                        |

Notes:
- `.jpg`, `.jpeg`, `.png`, and `.webp` all work for images — keep the base name
  (`cover`, `gallery-1`, …) the same.
- Any slot you leave empty is **hidden automatically** — no broken images.
- Recommended sizes: `cover` ~1200×750, `gallery-*` ~1000px wide, videos < 25 MB
  (compress long screen recordings so the page stays fast).

## Extra links (`links.md`)

If you want to add links (live demo, GitHub repo, video on YouTube, press article,
LinkedIn post…), create a `links.md` in the folder like this:

```
Live demo | https://example.com
GitHub | https://github.com/kacem-wael/econexus
Watch on YouTube | https://youtu.be/xxxx
```

One link per line: `Label | URL`. Tell me when they're in and I'll add the buttons.

## Folder map

```
assets/
├─ projects/
│  ├─ econexus/          EcoNexus — ML / FinTech platform
│  ├─ clinika/           Clinika — dental SaaS (in production)
│  ├─ examgen/           ExamGen — exam-generation SaaS
│  ├─ moove/             Moove — gym / sports management app
│  ├─ experthub/         ExpertHub — experts marketplace
│  ├─ stockfacturation/  StockFacturation — WPF desktop app
│  ├─ compiler-c/        Compiler written in C
│  └─ E-Uber/            E-Uber — ride-hailing app
├─ experience/
│  ├─ warp-analytics/    Apprenticeship (Clinika + Moove)
│  └─ devwise/           Internship (ExamGen)
├─ events/
│  ├─ robocup-7/         RoboCup 7.0 — organizing committee
│  ├─ robocup-8/         RoboCup 8.0 — jury member
│  ├─ ensi-forum/        ENSI Forum — organizing committee
│  ├─ gete/              GetE — pitched to investors
│  ├─ dentists-congress/ Int'l Congress of Dentists — repping Clinika
│  └─ roboday-3.0/       RoboDay 3.0 — robotics event
└─ certifications/
   └─ intro-to-cybersecurity/  Cisco Networking Academy
```

Certifications follow a slightly different convention (`certificate.pdf` + `cover.png`) —
see `assets/certifications/README.md`.
