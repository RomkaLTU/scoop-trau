# scoop-trau

[Scoop](https://scoop.sh) bucket for [trau](https://trau.sh) — an autonomous,
ticket-driven development loop.

```powershell
scoop bucket add trau https://github.com/RomkaLTU/scoop-trau
scoop install trau
trau --version
scoop update trau    # later, to update
```

Manifests under `bucket/` are generated on every tagged release by
[GoReleaser](https://goreleaser.com); edit
[`.goreleaser.yaml`](https://github.com/RomkaLTU/trau/blob/main/.goreleaser.yaml)
in the main repo rather than this bucket.

Native Windows support is **experimental** — see the
[platform matrix](https://github.com/RomkaLTU/trau#platforms).
