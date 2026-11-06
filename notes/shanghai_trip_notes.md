# RRSW-2026 — Shanghai Trip Notes

Pack code: **RRSW-2026**
Compiled: 2026-11-06 (Friday), for travel on Saturday **2026-11-14**

## 1. Train — Beijing (citywide) → Shanghai (citywide), Saturday 2026-11-14

Rules applied: high-speed **G only** · departure **07:00–12:00** · arrival **before 13:00** · whole-city search at both ends (Beijing → Shanghai).

Qualifying trains found (3):

| Train | Departure | Arrival | Duration |
|-------|-----------|---------|----------|
| **G5 (chosen)** | **北京南 07:59** | **上海 12:32** | **04:33 — fastest** |
| G37 | 北京南 07:52 | 上海虹桥 12:35 | 04:43 |
| G5 (from 北京) | 北京 07:40 | 上海 12:32 | 04:52 |

Trains excluded for arriving after 13:00: G565 07:07→13:12, G549 07:13→13:03, G597 07:42→13:49, G599 08:15→14:14, G633 08:37→15:01, G7 09:00→13:37, G669 09:07→14:59, G643 09:18→15:20, G693 09:47→15:56, G9 10:00→14:35, G11 10:03→14:39, G657 10:47→16:52, G23 11:00→15:37, G735 11:13→17:38, G737 11:17→17:22, G733 11:25→16:59, G741 11:50→18:02.

### Chosen train: G5

- **Train number:** G5 (high-speed, air-conditioned)
- **Board:** 北京南, Saturday 2026-11-14, **07:59**
- **Arrive:** 上海, **12:32** — 28 minutes ahead of the 13:00 deadline
- **Trip time:** 4 h 33 min
- **Seat availability when checked:** 商务座 remaining 1, 一等座 available, 二等座 available

Full stop list for G5 (2026-11-14):

| # | Station | Arrive | Depart | Notes |
|---|---------|--------|--------|-------|
| 1 | 北京 | — | 07:40 | origin |
| 2 | 北京南 | 07:54 | **07:59** | board here |
| 3 | 济南西 | 09:22 | 09:26 | |
| 4 | 南京南 | 11:23 | 11:25 | |
| 5 | 上海 | 12:32 | — | arrival |

## 2. Reading — "Attention Is All You Need"

- Paper: *Attention Is All You Need* (Vaswani et al.), arXiv:1706.03762 (v7)
- **Total page count (PDF):** 15

- **First occurrence of "attention" (any case):** page 1, in the paper title "Attention Is All You Need"
- **First sentence containing the word (running text, abstract):** "The best performing models also connect the encoder and decoder through an attention mechanism."

- **Total occurrences of "attention" (any case):** 97
- **Every page where the word occurs:** 1, 2, 3, 4, 5, 6, 7, 9, 10, 11, 12, 13, 14, 15 (every page except page 8)

Per-page breakdown: p1 = 6, p2 = 12, p3 = 6, p4 = 21, p5 = 14, p6 = 8, p7 = 5, p9 = 5, p10 = 4, p11 = 3, p12 = 1, p13 = 5, p14 = 5, p15 = 2.

- **One-sentence summary of the paper's main claim:** The Transformer, an encoder-decoder architecture built entirely on attention (dispensing with recurrence and convolutions entirely), achieves better translation quality than prior sequence transduction models (28.4 BLEU on WMT 2014 English→German; 41.8 BLEU English→French, a new single-model state of the art) while being far more parallelizable and dramatically cheaper to train.
