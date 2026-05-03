# TCGx Compiled Data

Compiled Pokémon TCG card data for Japanese and Korean, sourced from [tcgdex/cards-database](https://github.com/tcgdex/cards-database).

## Files

| File | Language | Cards |
|------|----------|-------|
| `sv.json` | JA/KR | ~5,300 |
| `s.json` | JA/KR | ~4,600 |
| `sm.json` | JA/KR | ~3,800 |
| `xy.json` | JA/KR | ~1,500 |
| `xyb.json` | JA/KR | ~800 |
| `bw.json` | JA/KR | ~1,200 |
| `dp.json` | JA/KR | ~900 |
| `dpt.json` | JA/KR | ~400 |
| `pl.json` | JA/KR | ~300 |
| `hgss.json` | JA/KR | ~600 |
| `ex.json` | JA/KR | ~2,000 |
| `neo.json` | JA/KR | ~300 |
| `e.json` | JA/KR | ~500 |
| `vs.json` | JA/KR | ~140 |
| `l.json` | JA/KR | ~200 |
| `adv.json` | JA/KR | ~1,000 |
| `pcg.json` | JA/KR | ~700 |
| `pmcg.json` | JA/KR | ~450 |
| `m.json` | JA/KR | ~200 |

## Usage

Data is consumed by [TCGx](https://github.com/) via jsDelivr CDN:
```
https://cdn.jsdelivr.net/gh/USERNAME/tcgx-data@main/sv.json
```

## Build

Run `node build-tcgx.js` to regenerate from `tcgdex/cards-database`.
