# DX-888 Manuals · TEF6686 Receiver

Documentation for the **DX-888**, a radio receiver module built around the NXP **TEF6686** tuner IC. Both manuals are kept in this repository as PDFs, so the links below always point to the files themselves — no external download page, no broken link.

## Documents

- **[DX-888.pdf](DX-888.pdf)** — English edition, 8 pages
- **[DX-888CN.pdf](DX-888CN.pdf)** — Chinese edition (中文版), 8 pages

The two editions cover the same content: hardware overview, connections and wiring, controls and operating procedure, and the specification table. Use the English edition for reference in code comments, issue reports and screenshots; use the Chinese edition when you need the exact wording of the original labels.

## How to read them

Click a file above — GitHub renders PDFs in the browser, and the **Download** button in the viewer saves a local copy. If you prefer the raw files:

```
https://raw.githubusercontent.com/jumbo5566/manuals/main/DX-888.pdf
https://raw.githubusercontent.com/jumbo5566/manuals/main/DX-888CN.pdf
```

## About the chip

TEF6686 is an NXP automotive tuner IC (AM / FM / shortwave, with RDS / RBDS / AF / ASEP / BDS data services). The DX-888 exposes this tuner on a small board with its own controls and display, so the manuals describe the board as a finished product, not the bare IC.

For the IC-level details (registers, application interfaces) refer to the NXP TEF6686 datasheet — this repository only carries the DX-888 board manuals.

## Related project

The same author's ADS-B aircraft receiver lives here: [jumbo5566/adsb-module](https://github.com/jumbo5566/adsb-module) — product introduction, web serial terminal and viewer tool.

## Files in this repository

- `README.md`
- `DX-888.pdf` — English manual
- `DX-888CN.pdf` — Chinese manual
