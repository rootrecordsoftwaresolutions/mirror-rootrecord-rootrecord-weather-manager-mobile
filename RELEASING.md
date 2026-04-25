# Publishing a release (maintainers)

1. Build and sign the Android artifact in your **private** repository.
2. On GitHub → **Releases** → **Draft a new release**, choose a tag (for example `v1.2.3`).
3. Attach the **APK** (and optional **README** / **CHANGELOG** excerpts as release description text).
4. Update [CHANGELOG.md](CHANGELOG.md) on `main` when you want the public log to match what testers read.

Do not upload keystores, `google-services.json`, Firebase JSON, or full source trees.
