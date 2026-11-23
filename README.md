# World News — 23 November 2026

A Chinese classical-style daily brief summarising the top world news of 23 November 2026.
The image `news-20261123.jpg` (683×1024) is the entry; `main.py` outputs it
deterministically. The news text on the image is in English. Layout is hierarchical:
the lead story (Nvidia) gets a large central headline with a sharp commentary,
the other stories appear in smaller type, and the smallest item sits in a corner.

## The 7 stories

1. **Nvidia soars 33%** — Jensen Huang reinstated as CEO; stock rebounds after a brutal sell-off (Friday -14%).
2. **Trump warns Iran** — strikes may resume in the New Year; Iran hits a U.S. base in Bahrain.
3. **COP31 collapses** — climate talks end with no deal; the longest UN climate summit ever.
4. **Russia strikes Kyiv** — deadly attacks; NATO holds emergency talks as Russian missiles enter Poland.
5. **Democrats' big win** — largest U.S. House majority since 1992 (at least 258 seats).
6. **Gaza crisis** — Israeli strike kills 3; Oxfam reports 99% of Gaza contaminated.
7. **Cartel kingpin caught** — Mexico captures Sinaloa leader "Chapo Isidro".

## How to run

```sh
python3 main.py > news.jpg
```

The program only reads the bundled image and writes its bytes to stdout.
No network access, no randomness — running it twice produces identical bytes.

## Sources

- Just Security, Early Edition: November 23, 2026
- Yeni Safak English, 23 November 2026
- South China Morning Post, world headlines
- Saachi Baat, International & World News — 23 November 2026
- Medium / All Voices News, Global and U.S. Strategic News Brief: November 23, 2026
