# INKWELL

A playful, mobile-first drawing studio with a notebook-and-crayon visual language. INKWELL is designed for sketching, layering, experimenting with colour, and making small flipbook animations.

## What's in this repository

- **[index.html](./index.html)**: the latest supplied INKWELL web build, preserved as a single-file HTML application.
- **assets/screenshots/**: home for the supplied app screenshots and visual previews.
- **releases/**: release notes and APK provenance.
- **README.md**: project overview and setup notes.

## Run INKWELL

The web build is self-contained. Download `index.html` and open it in a modern browser. For the most consistent storage and offline behaviour, serve it from a local or hosted HTTP(S) origin rather than opening it as a `file://` URL.

A simple local server can be started with Python:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Android

The supplied Android package is named `Inkwell_v1.6.7_1793794555785.apk` (9,603,129 bytes).

SHA-256:

```
e79707d4dc0f57104222c64d305a2f430efa160b001d4eec978136a590378a8d
```

The APK is a compiled installable artifact, not the editable source project. Release distribution should use a GitHub Release asset so the binary can be downloaded without bloating Git history. See [releases/README.md](./releases/README.md) for the current artifact record.

## Screenshots

The screenshots supplied with the project belong in `assets/screenshots/`. See [assets/screenshots/README.md](./assets/screenshots/README.md) for the intended image set and naming.

## Project notes

- The repository keeps the supplied HTML intact rather than rewriting or minifying it.
- User drawings and local project data are stored by the application in the browser/WebView environment. They are not automatically committed to this repository.
- Do not commit personal drawing exports, private signing keys, keystores, API tokens, or machine-specific Android configuration.
- APK installation and runtime behaviour should be tested on the target Android device before describing a build as production-ready.

## License

No license has been declared yet. Until a license is added, the default copyright rules apply and reuse should not be assumed to be permitted.
