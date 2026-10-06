# Whitepaper für investieren.mit.seli

Vier statische Seiten, die per DM verschickt werden, wenn jemand unter einem
Reel das passende Stichwort kommentiert. Kein Build, keine Abhängigkeiten —
reines HTML.

| Adresse | Stichwort |
|---|---|
| `/start` | START — ETF-Fahrplan |
| `/wolf` | WOLF — Wolfspeed |
| `/token` | TOKEN — Tokenisierung |
| `/honey` | HONEY — Honeywell |

`cleanUrls` in `vercel.json` sorgt dafür, dass die Adressen ohne `.html`
funktionieren. `noindex` ist gesetzt: Die Seiten sollen über die DM gefunden
werden, nicht über Google — sonst steht eine Aktieneinschätzung von Oktober
2026 in zwei Jahren noch im Suchindex.

Quelle der Dateien: `RaulinRegime/Seli/Whitepaper/` im Content-Repo. Dort
werden sie gepflegt, hier nur veröffentlicht.
