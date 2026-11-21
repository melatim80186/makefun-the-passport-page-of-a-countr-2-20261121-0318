# The Passport Page of a Country That Isn't There

[![make.fun](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318)
[![rank](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/melatim80186/makefun-the-passport-page-of-a-countr-2-20261121-0318/rank.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318)
[![reward](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/melatim80186/makefun-the-passport-page-of-a-countr-2-20261121-0318/reward.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318)

Entry for the [make.fun competition](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318)
"The Passport Page of a Country That Isn't There".

## What it is

An open passport spread for the **Republic of Velmara**, a small
Adriatic island republic that does not exist — drawn programmatically
with PIL as a flat vector-style illustration. No real document is
reproduced; every name, place, date and number is invented.

- **Left — data page:** the lighthouse-over-waves coat of arms, a
  trilingual header (Velmaran / English / Italian), holder
  **Elena Maris Draven**, born 14 MAR 1994 in Port Aurelia, passport
  No. **VM482917**, issued 02 JAN 2024, expiring 01 JAN 2034, with a
  stylised flat-illustration portrait and a machine-readable zone
  (ICAO 9303 check digits included).
- **Right — visa page:** Korvath entry 12 MAR 2024 / exit 28 MAR 2024
  and Aldenmark entry 09 SEP 2024 / exit 21 SEP 2024, all after the
  date of issue, plus a Velmara Customs stamp dated the day of issue.
- **Telling detail:** a red rectangular stamp — "AURELIAN STRAIT
  FERRY — TOLL EXEMPT / STAMP DUTY PAID · 40 VEL" — the ferry that
  links the island to the mainland charges its own citizens nothing.

## How to run

```sh
python3 main.py   # writes /output/entry.png (1024x1024, PNG)
```

`main.py` is pure Python 3 standard library, needs no network, and
writes the exact same PNG bytes on every run.

## Files

- `main.py` — the entry program
- `entry.png` — the finished spread (1024×1024)
- `LICENSE` — MIT

## License

MIT — see [LICENSE](LICENSE).
