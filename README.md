# Baitcaster Setup Reference Data

Plain-text reference tables for baitcasting reel setup, extracted from the published
guides on [Baitcaster Tips](https://baitcastertips.com).

The point of this repository is that the numbers are in a format you can diff, chart,
import, or check against your own tackle — instead of being locked inside a web page.

## What is in here

| File | What it holds |
|---|---|
| `data/line-weight-by-lure-class.csv` | Reel class → lure weight → mono/fluoro lb → braid lb, with gram and kilogram conversions |
| `data/wind-adjustment.csv` | How to shift line weight, brake clicks and expected distance as wind speed rises |
| `data/braid-vs-mono-decision.csv` | Setup → line choice → the reason, for four common baitcaster setups |
| `data/backlash-diagnosis-order.md` | The five things to check when a baitcaster backlashes on every cast, in order |
| `data/backlash-nest-grading.md` | How to grade a bird's nest as light / buried / severe, and which method each grade takes |
| `data/spool-tension-vs-brake.md` | Why spool tension and brake are not the same control, and what each one affects |

## Conventions

- Decimal values use a period; thousands are not separated.
- The original tables use en dashes in ranges (`4 – 8`) and a true minus sign in one
  cell (`−1 click`). Here both are written as the ASCII hyphen-minus (`4 - 8`,
  `-1 click`) so the files parse cleanly in CSV readers and spreadsheets. No numeric
  value was changed.
- Units are kept exactly as published: `oz`, `g`, `lb`, `kg`, `mph`, `km/h`.
- Rows are in the same order as the source tables. Nothing has been added, removed or
  re-sorted.

## Scope and limits

These are reference values for recreational baitcasting tackle in the classes named in
each row. They are not manufacturer specifications, and they are not a substitute for
the line rating printed on your own rod and reel.

## License

The files in `data/` are released under CC0 1.0 Universal — a public domain
dedication, so you can reuse them for any purpose without attribution. See
[LICENSE](LICENSE) for the full text.

## Corrections

If a row is wrong, open an issue with the row, the value you expected, and where your
value comes from. Corrections with a source get applied; unsourced ones do not.
