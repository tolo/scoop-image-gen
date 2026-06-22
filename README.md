# scoop-image-gen

Scoop bucket for [image-gen](https://github.com/tolo/image_gen_cli) — a CLI that
generates images with OpenAI GPT-Image models using ChatGPT-subscription
credentials.

## Install

```powershell
scoop bucket add image-gen https://github.com/tolo/scoop-image-gen
scoop install image-gen
```

The manifest in `bucket/image-gen.json` is rendered and pushed automatically by
the `Release Binaries` workflow in the main repo on each `v*` tag.
