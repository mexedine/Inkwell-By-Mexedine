# INKWELL

A little crayon page for drawing, doodling, and frame-by-frame animation. INKWELL pairs a warm paper-and-pencil visual language with a browser-based canvas studio.

## What's inside

- **Drawing studio:** pencil, pen and crayon-style brushes, adjustable size and opacity, colour palette and custom colours.
- **Canvas and paper:** paper/background packs, canvas sizing, fit controls and reference images.
- **Layers:** add, duplicate, delete, toggle visibility and adjust opacity.
- **Selection:** lasso selection and selection operations.
- **Animation:** create, duplicate and delete frames, preview animation and adjust FPS.
- **Export and backup:** export artwork and portable project data.
- **Hand-drawn interface:** warm paper textures, rounded controls, playful loading animation and a notebook-inspired visual style.

## Repository layout

```text
.
├── README.md
├── index.html
├── assets/
│   └── screenshots/       # Add project screenshots here
└── android/
    ├── Inkwell-v1.6.7.apk
    └── README.md
```

## Run the web app

The supplied web build is a standalone HTML file. No package installation or build step is required.

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. If browser restrictions affect file or download behaviour, serve the folder over HTTP instead, for example with `python -m http.server 8000`, then open `http://localhost:8000`.

## Android APK

- **Version:** 1.6.7
- **File:** `android/Inkwell-v1.6.7.apk`
- **Original filename:** `Inkwell_v1.6.7_1793794555785.apk`
- **Size:** 9,603,129 bytes
- **SHA-256:** `e79707d4dc0f57104222c64d305a2f430efa160b001d4eec978136a590378a8d`

The APK is the supplied compiled artifact. It is not represented as a build generated from the HTML source in this repository. Signing certificate, target-device compatibility and update behaviour should be verified before treating it as a production release.

## Screenshots

The `assets/screenshots/` directory is reserved for screenshots. The repository package does not include screenshot images; add the original PNGs here when ready.

## Important storage note

The supplied HTML describes project drafts as local and in-memory, and warns that they are not stored after a refresh. Use the app's project backup/export feature to keep portable copies. This repository does not provide cloud sync or a backend service.

## License

No license has been specified. Until a license is added, the default copyright rules apply; public visibility does not automatically grant permission to reuse or redistribute the code or artwork.
