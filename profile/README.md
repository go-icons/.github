<p align="center"><img src="https://raw.githubusercontent.com/go-icons/brand/main/social/go-icons.png" alt="go-icons" width="640"></p>

<h1 align="center">go-icons</h1>
<p align="center">Free icon sets as embedded SVG for pure-Go UIs.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Go-1.23-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img src="https://img.shields.io/badge/code-BSD--3--Clause-7C3AED?style=flat-square">
  <img src="https://img.shields.io/badge/artwork-MIT-9333EA?style=flat-square">
  <a href="https://go-icons.github.io/"><img src="https://img.shields.io/badge/site-go--icons.github.io-581C87?style=flat-square"></a>
</p>

---

## What this is

Toolkits that render their own UI need icons, and the good free sets ship as
loose SVG files with no Go packaging. **go-icons** closes that gap: each repo
embeds a curated subset of one free icon set and serves it by name.
The file-type packs (`seti`, `material`) key on a file name — `Icon(filename)`
matches by base name, then extension, then a generic-document fallback, and
`Folder()` returns the folder glyph. The general-purpose pack (`iconoir`) keys on
the icon's own name — `Icon(name)`, with `Has` and `Names` to enumerate the set.

These are **data packages**: they return SVG *strings* and draw nothing. A
renderer — such as [go-widgets/toolkit](https://github.com/go-widgets/toolkit)'s
`SVGIcon` — turns the returned SVG into a drawn glyph. The Go code is
BSD-3-Clause; the embedded artwork keeps its **upstream** licence and is
redistributed unmodified, with that licence alongside it in each repo. That is
MIT for five of the six sets and **CC0-1.0** for `simple-icons`, which is why
this paragraph no longer says MIT: one sentence covering every repository stops
being true the moment a repository does not fit it.

## Repos

| | Repo | |
|---|---|---|
| <img src="https://raw.githubusercontent.com/go-icons/brand/main/avatar/go-icons-seti.png" width="36"> | [`seti`](https://github.com/go-icons/seti) | Seti UI file-type icons as embedded SVG, for pure-Go UIs |
| <img src="https://raw.githubusercontent.com/go-icons/brand/main/avatar/go-icons-material.png" width="36"> | [`material`](https://github.com/go-icons/material) | Material Icon Theme file-type icons as embedded SVG, for pure-Go UIs |
| <img src="https://raw.githubusercontent.com/go-icons/brand/main/avatar/go-icons-iconoir.png" width="36"> | [`iconoir`](https://github.com/go-icons/iconoir) | Iconoir UI icons as embedded SVG, for pure-Go UIs |
| <img src="https://raw.githubusercontent.com/go-icons/brand/main/avatar/go-icons-vscode-icons.png" width="36"> | [`vscode-icons`](https://github.com/go-icons/vscode-icons) | vscode-icons file-type icons as embedded SVG, for pure-Go UIs |
| <img src="https://raw.githubusercontent.com/go-icons/brand/main/avatar/go-icons-devicon.png" width="36"> | [`devicon`](https://github.com/go-icons/devicon) | Devicon language & tool logos as embedded SVG, for pure-Go UIs |
| | [`simple-icons`](https://github.com/go-icons/simple-icons) | Simple Icons **brand** logos as embedded SVG, keyed by brand name rather than by file name — CC0-1.0, not MIT. *(No avatar yet: the brand assets are generated, and the generator does not live in `go-icons/brand`.)* |

## Links

- 🎨 Brand assets — <https://github.com/go-icons/brand>
- 🌐 Site — <https://go-icons.github.io/>

---
<p align="center"><sub>Branding in <a href="https://github.com/go-icons/brand">go-icons/brand</a>. Icon artwork © its respective authors, MIT.</sub></p>
