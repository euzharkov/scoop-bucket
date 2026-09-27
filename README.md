# scoop-bucket

[Scoop](https://scoop.sh) manifests for tools by [@euzharkov](https://github.com/euzharkov).

```powershell
scoop bucket add euzharkov https://github.com/euzharkov/scoop-bucket
scoop install rhow
```

| App | What it is |
|---|---|
| `rhow` | Discover how to run and operate any repository. Source: [euzharkov/run-how](https://github.com/euzharkov/run-how) |

Manifests download prebuilt binaries from GitHub Releases and verify their SHA256. The source
of truth for `rhow.json` is `packaging/scoop/rhow.json` in the run-how repository; it is copied
here at release time. `autoupdate` reads new hashes from the release's `SHA256SUMS`.
