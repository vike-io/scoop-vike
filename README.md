# scoop-vike

A [scoop](https://scoop.sh) bucket for the vike trader CLI on Windows.

```powershell
scoop bucket add vike https://github.com/vike-io/scoop-vike
scoop install vike-cli
```

Manifests here are RENDERED at publish time from a release tag and that release own SHA256SUMS, and pushed with real history so `scoop update` can fast-forward this bucket. Nothing else lives here: no source, no scripts, no data.
