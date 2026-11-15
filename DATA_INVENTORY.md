# Data inventory: Global Trade Intelligence (`index.html`)

This file lists every data point the live page (`index.html`) shows, where it comes from, when it was last refreshed, and how often it should be updated. `index-v1.html` and `index-dashboard.html` are earlier versions. Nothing links to them, so they are not refreshed.

**Last refresh: 15 November 2026**

Marks used in the "Last value" column:

- ✅ Re-verified this run.
- ⚠️ Updated, but the figure rests on secondary sources or sources that conflict. Check it against the primary release.
- 🕰️ Historical or structural data. It is not expected to change.

## 1. Page-level items

| Item | Where on the page | Last value | Source | Refresh when |
|---|---|---|---|---|
| Title, meta and hero month | `<head>`, hero eyebrow | November 2026 | n/a | Every refresh |
| Finding 1: US trade gap YTD | Findings | −12.2% (Jan–Sep), −$92.4bn ✅ | BEA, released 4 Nov 2026 | Monthly (next: 8 Dec 2026, October data) |
| Finding 2: Brent | Findings | $95.84 on 13 Nov 2026, +57% YTD ✅ | ICE settlement; IEA OMR | Every refresh |
| Finding 3: China surplus YTD | Findings | $1.04tn (Jan–Oct) ✅ | GAC, 10 Nov 2026 | Monthly (~7–10th) |
| Data-film act copy | Film `ACTS` | US gap −12.2% through September | BEA | Monthly |
| Data-film oil series and US/ASEAN shares | Film SVG | Illustrative 🕰️ | n/a | Rarely |
| Method text, caveats and source list (12 entries) | Method | Dated to the latest releases | n/a | Every refresh |
| Footer "Data current to" | Footer | 15 November 2026 | n/a | Every refresh |
| Timeline (15 events) | `TL` array | Latest entry: 13 Nov 2026 | Various | Add events as they happen |

## 2. Each of the nine economies (`N` array in `index.html`)

Each economy carries the same fields:

- `rank`: GDP or role
- `badge`: headline
- `lede`
- `vitals`: 8–12 key-figure tiles
- `trade`: annual exports and imports, 2019–2025
- `exp` / `imp`: top-8 partners, 2025 shares, with notes
- `sec`: top-10 sectors, 2025 composition
- `intel`: analysis
- `risk`

`trade`, `exp`, `imp` and `sec` are **completed-year (2025)** data 🕰️. Update them once a year, when final 2026 data is published (around Q2 2027). The tables below cover the fields that need recurring updates.

### United States

| Vital | Last value | Source / release | Cadence |
|---|---|---|---|
| Trade gap, 9 months of 2026 | −12.2%, −$92.4bn ✅ | BEA, 4 Nov 2026 | Monthly |
| Exports / imports, 9 months of 2026 | +11.6% / +6.2% ✅ | BEA | Monthly |
| September deficit | −$105.0bn (August revised to $105.7bn) ✅ | BEA | Monthly |
| September services surplus | +$30.9bn ✅ | BEA | Monthly |
| GDP, Q3 2026 | +3.4% (advance); Q2 2.2% ✅ | BEA, 29 Oct 2026 | Quarterly (second estimate 25 Nov) |
| Average effective tariff | ~7.1% (Penn Wharton); 9.0–10.9% (Yale) ⚠️ | PWBM, Yale Budget Lab | Monthly |
| Tariff on China | ~37.5% ⚠️ (tracker estimate); truce runs to 10 Jan 2027 ✅ | Trackers; Treasury | On policy change |
| USD reserve share | 56.70%; EUR 20.60% ✅ | IMF COFER Q2 2026 | Quarterly (Q3 due end-Dec) |
| LNG exports | 17.6 bcf/d (2026 forecast) ✅ | EIA STEO, November | Monthly |
| Nominal GDP (`rank`) | $32.6tn ⚠️ | IMF WEO Oct 2026 (secondary) | April and October |
| Customs duties 2025; goods deficit 2025 | $287bn; −$1.24tn 🕰️ | n/a | Annual |

### China

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| Exports / imports, 10 months of 2026 (yuan) | +17.6% / +23.6% ✅ | GAC | Monthly |
| Surplus, 10 months of 2026 | $1.04tn ✅ | GAC | Monthly |
| October exports / surplus | $412.3bn (+35.2%) / $105.3bn ✅ | GAC, 10 Nov 2026 | Monthly |
| GDP, Q3 2026 | +4.5%; 9 months +4.6% ✅ | NBS | Quarterly (Q4 due mid-Jan) |
| High-tech / semiconductor exports, Jan–Oct | +47.9% / +111.1% ⚠️ | Press citing GAC | Monthly |
| NEV exports, Jan–Oct | 4.61m units, +130% ✅ | CAAM | Monthly |
| Exports to USA, October | +32.9% YoY ✅ | GAC via press | Monthly |
| Trade with ASEAN, Jan–Oct | +24.2%, ¥7.68tn ✅ | GAC | Monthly |
| Nominal GDP (`rank`) | $21.6tn ⚠️ | IMF WEO Oct 2026 | April and October |

### India

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| Nominal GDP and rank | $4.06tn, #6 ✅ | IMF WEO Oct 2026 | April and October |
| GDP, Q1 FY27 | +7.8% ✅ | MoSPI | Quarterly (**Q2 due 30 Nov 2026**) |
| October merchandise exports / imports | $49.5bn record / $89.4bn ✅ | Ministry of Commerce | Monthly (~15th) |
| October merchandise deficit / overall gap | −$39.9bn / −$20.1bn ⚠️ (services estimated) | Ministry of Commerce | Monthly |
| FX reserves | $719.6bn (week to 6 Nov); record $785.7bn on 4 Sep ✅ | RBI | Weekly |
| Rupee | ~93.7 (11 Nov) ✅ | Market | Every refresh |
| Russian oil share | ~35% (October) ⚠️ | Kpler via press | Monthly |
| US tariff | Unsettled; deal unsigned ⚠️ | Press | On policy change |
| Services exports and remittances, FY25-26 | $421.3bn / $144.8bn 🕰️ | RBI | Annual |

### Russia

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| Fossil fuel revenue per day | €754m (October, +14% M/M) ⚠️ | CREA (via press) | Monthly |
| China / India purchases | €10.7bn / €6.4bn, both records ⚠️ | CREA | Monthly |
| Product exports | 1.49 mb/d (October) ⚠️ | IEA OMR | Monthly |
| Oil and gas budget revenue, Jan–Oct | RUB 6.44tn, −14.1% ⚠️ | MinFin (via press) | Monthly |
| India share of crude | ~35% ⚠️ | Kpler | Monthly |
| 2025 trade (`trade` 2025) | $418bn exports / $279bn imports ✅ | Customs via Interfax | Annual |

### Japan

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| September exports / imports | +16.7% / +18.9% ✅ | MoF, 21 Oct 2026 | Monthly (October data due ~19 Nov) |
| September balance | −¥536.6bn (revised to −¥556.5bn) ✅ | MoF | Monthly |
| Chips / exports to USA / vehicles | +49.4% / +22.9% / +15.1% ⚠️ | MoF via press | Monthly |
| Nominal GDP | $4.34tn, #4 ✅ | IMF WEO Oct 2026 | April and October |
| Q3 GDP | Not yet published | Cabinet Office, 16 Nov | Quarterly. Add it next run |

### Europe (EU-27 and euro area)

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| EU balance, Q1 / Q2 2026; energy deficit, Q2 | +€12.7bn / −€21.8bn; −€101.1bn ✅ | Eurostat (Q3 not yet released) | Quarterly |
| EU September balance (badge) | −€16.8bn ⚠️ | Eurostat via press | Monthly |
| Euro area September / 9 months | −€10.3bn / −€36.5bn ✅ | Eurostat, 13 Nov 2026 | Monthly |
| Germany surplus | €15.6bn (September, seasonally adjusted) ✅ | Destatis, 9 Nov 2026 | Monthly |
| China EV tariff | 35–48%, with price undertakings ✅ | European Commission | On policy change |

### Middle East (Gulf)

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| Saudi output | 9.19 mb/d (October) ✅ | OPEC MOMR, 11 Nov | Monthly |
| Gulf oil exports | 18.4 mb/d, −26% vs pre-war ⚠️ | IEA OMR, 13 Nov | Monthly |
| Kuwait / Iraq output | 2.03 / 4.60 mb/d ⚠️ | IEA estimates | Monthly |
| Saudi 9-month deficit | SR244.3bn ⚠️ | Saudi MoF | Quarterly |
| GCC growth 2026 | −4.8% ✅ | IMF REO Oct 2026 | Twice yearly |
| Iran revenue gain; bypass capacity | +$1.54bn; ~8.8 mb/d 🕰️ (spring 2026) | n/a | Refresh if a newer estimate appears |
| Hormuz status | Still restricted ✅ | IMF PortWatch, UKMTO | Every refresh |

### Australia

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| Iron ore / LNG / gold earnings | A$123bn / A$57bn / ~A$68bn (2025-26) ✅ | Resources and Energy Quarterly, Sep 2026 | Quarterly (December REQ) |
| Total resource earnings | A$403bn; A$422bn forecast for 2026-27 ✅ | REQ | Quarterly |
| September goods surplus | A$2.8bn ✅ | ABS, 5 Nov 2026 | Monthly |
| Iron ore price | $87/t (2025-26 average) 🕰️. A spot figure was not used because sources conflicted | n/a | Monthly |

### Pakistan

| Vital | Last value | Source | Cadence |
|---|---|---|---|
| FY25-26 exports / imports / deficit | $30.1bn / $69.8bn / −$39.6bn ✅ | PBS (revised) | Annual |
| Jul–Oct FY27 deficit | −$14.6bn, +16% ✅ | PBS | Monthly (~early month) |
| Remittances | $41.6bn in FY26; $14.8bn Jul–Oct FY27 ✅ | SBP | Monthly (~10th) |
| SBP reserves | $21.56bn (30 Oct) ✅ | SBP | Weekly |
| IMF programme | 4th EFF review: staff-level agreement in October; board approval pending | IMF | On event |

## 3. Known gaps for the next run

- Japan Q3 GDP is due 16 Nov and Japan's October trade data around 19 Nov.
- India Q2 FY27 GDP is due 30 Nov. India's April–October import total has not been found yet.
- The US October trade release is due 8 Dec, and the Q3 GDP second estimate 25 Nov.
- No official blended US tariff rate on China is published. The ~37.5% figure is a tracker estimate.
- The Eurostat Q3 2026 EU balance and energy breakdown are not yet published.
- Check the ⚠️ figures against the primary release pages. This run could only reach search-result excerpts, not the official sites themselves.
