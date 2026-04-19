# Trading Process Flowchart

---

## 1. Daily Session Flow

```
╔══════════════════════════════════╗
║     PRE-SESSION  (8:45 AM)       ║
╚══════════════════════════════════╝
                 │
                 ▼
    ┌────────────────────────┐
    │ Review Nifty Daily &   │
    │ 1hr Chart              │
    └────────────┬───────────┘
                 │
                 ▼
    ┌────────────────────────┐
    │ Mark Key S/R Levels    │
    └────────────┬───────────┘
                 │
                 ▼
    ┌────────────────────────┐
    │ Identify 2–3 Setup     │
    │ Areas for the Session  │
    └────────────┬───────────┘
                 │
                 ▼
    ┌────────────────────────┐
    │ Calculate 1% Risk      │
    │ = Capital × 0.01       │
    └────────────┬───────────┘
                 │
                 ▼
         ┌───────────────┐
         │ Losing day    │
         │ yesterday?    │
         └──┬────────┬───┘
           YES       NO
            │         │
            ▼         ▼
    ┌──────────┐  ┌──────────┐
    │ Size     │  │ Normal   │
    │ down to  │  │ 1% risk  │
    │ 0.5%     │  │          │
    └────┬─────┘  └────┬─────┘
         └──────┬───────┘
                │
                ▼
    ┌────────────────────────┐
    │ Write Directional Bias │
    │ or "No bias — wait"    │
    └────────────┬───────────┘
                 │
╔══════════════════════════════════╗
║    MARKET OPENS  (9:15 AM)       ║
╚══════════════════════════════════╝
                 │
                 ▼
    ┌────────────────────────────────────┐
    │  Price arrived at pre-identified   │◄──────────────┐
    │  setup area?                       │               │
    └──────────┬──────────────┬──────────┘               │
              YES              NO                         │
               │               │                         │
               ▼               ▼                         │
    ┌──────────────┐   ┌──────────────┐                  │
    │ Run          │   │   WAIT       │──────────────────►┘
    │ Pre-Trade    │   └──────────────┘
    │ Checklist    │
    └──────┬───────┘
           │
           ▼
    ┌────────────────┐
    │  All 5 checks  │
    │  pass?         │
    └──┬─────────┬───┘
      YES         NO
       │           │
       ▼           ▼
┌──────────┐   ┌──────────┐
│ Recovery │   │  WAIT    │
│ Mode     │   └──────────┘
│ Check    │
└──┬───────┘
   │
   ▼
┌────────────────────────────┐
│ Entering to recover a loss?│
└──────┬───────────┬──────────┘
      YES           NO
       │             │
       ▼             ▼
┌──────────────┐  ┌──────────────────────┐
│ STOP         │  │ Calculate Lot Size   │
│ Leave screen │  │ = Risk ÷ (Stop × 65) │
│ 10 minutes   │  └──────────┬───────────┘
└──────┬───────┘             │
       │                     ▼
       ▼             ┌──────────────────────┐
┌─────────────┐      │ Define Entry / Stop  │
│ Still want  │      │ T1 / T2              │
│ to trade?   │      └──────────┬───────────┘
└──┬──────┬───┘                 │
  YES      NO                   ▼
   │        │          ┌──────────────────────┐
   ▼        ▼          │   ENTER TRADE        │
┌──────┐  ┌──────┐     └──────────┬───────────┘
│ Half │  │ Skip │                │
│ Size │  │ trade│                ▼
└──┬───┘  └──────┘     ┌──────────────────────┐
   │                   │ Place Stop-Loss Order │
   └──────────────────►│ IMMEDIATELY           │
                       └──────────┬────────────┘
                                  │
                                  ▼
                       ┌──────────────────────┐
                       │ Set alerts for T1, T2│
                       └──────────┬────────────┘
                                  │
                         ┌────────┴─────────┐
                         │                  │
                         ▼                  ▼
                  ┌─────────────┐   ┌─────────────┐
                  │ Price hits  │   │ Price hits  │
                  │   STOP      │   │    T1       │
                  └──────┬──────┘   └──────┬──────┘
                         │                 │
                         ▼                 ▼
                  ┌─────────────┐   ┌─────────────┐
                  │ Loss        │   │ Exit 50%    │
                  │ accepted    │   │ Lock profit │
                  └──────┬──────┘   └──────┬──────┘
                         │                 │
                         └────────┬────────┘
                                  │
                                  ▼
                       ┌──────────────────────┐
                       │  Daily loss limit    │
                       │  hit? (₹10,000)      │
                       └──────┬───────┬───────┘
                             YES       NO
                              │         │
                              ▼         ▼
                      ┌──────────┐  ┌──────────┐
                      │ SESSION  │  │ Max 3    │
                      │  ENDS    │  │ trades?  │
                      └──────────┘  └──┬────┬──┘
                                      YES   NO
                                       │     │
                                       ▼     ▼
                               ┌──────────┐  Back to
                               │ SESSION  │  watching
                               │  ENDS    │  for setups
                               └──────────┘

╔══════════════════════════════════╗
║   POST-SESSION  (3:30 PM+)       ║
╠══════════════════════════════════╣
║ □ Record every trade in journal  ║
║ □ Rate process: 1–10             ║
║ □ Write one lesson               ║
║ □ Note any rule deviations       ║
╚══════════════════════════════════╝
```

---

## 2. Pre-Trade Checklist (5-Gate System)

```
         Price at setup area?
                 │
                 ▼
    ┌────────────────────────────┐
    │  Gate 1 — LOCATION         │
    │  Is price at meaningful    │──── NO ──► ❌ NO TRADE
    │  S/R on 15min/1hr chart?   │
    └─────────────┬──────────────┘
                 YES
                  │
                  ▼
    ┌────────────────────────────┐
    │  Gate 2 — SIGNAL           │
    │  Candle showing rejection  │──── NO ──► ❌ NO TRADE
    │  or confirmation?          │
    └─────────────┬──────────────┘
                 YES
                  │
                  ▼
    ┌────────────────────────────┐
    │  Gate 3 — CONTEXT          │
    │  1hr or Daily chart agrees │──── NO ──► ❌ NO TRADE
    │  with trade direction?     │
    └─────────────┬──────────────┘
                 YES
                  │
                  ▼
    ┌────────────────────────────┐
    │  Gate 4 — STOP             │
    │  Do I know exactly where   │──── NO ──► ❌ NO TRADE
    │  my stop is in points?     │
    └─────────────┬──────────────┘
                 YES
                  │
                  ▼
    ┌────────────────────────────┐
    │  Gate 5 — RISK             │
    │  Lot size calculated and   │──── NO ──► ❌ NO TRADE
    │  within 1% limit?          │
    └─────────────┬──────────────┘
                 YES
                  │
                  ▼
            ✅ VALID SETUP
             Proceed to entry
```

---

## 3. Lot Size Calculation

```
    ┌────────────────────────────────────┐
    │  Step 1: Max Risk                  │
    │  = Capital × 1%                   │
    │  Example: 5,00,000 × 1% = ₹5,000  │
    └───────────────┬────────────────────┘
                    │
                    ▼
    ┌────────────────────────────────────┐
    │  Step 2: Stop in Points            │
    │  = Entry Premium − Stop Premium    │
    │  Example: ₹120 − ₹90 = 30 points  │
    └───────────────┬────────────────────┘
                    │
                    ▼
    ┌────────────────────────────────────┐
    │  Step 3: Lots                      │
    │  = Max Risk ÷ (Stop Points × 65)   │
    │  = 5000 ÷ (30 × 65)               │
    │  = 5000 ÷ 1950                    │
    │  = 2.56  →  Round DOWN  →  1 lot  │
    └───────────────┬────────────────────┘
                    │
                    ▼
         ┌────────────────────┐
         │  Lots ≥ 1 ?        │
         └──────┬───────┬─────┘
               YES       NO
                │         │
                ▼         ▼
        ┌──────────┐  ┌────────────────────┐
        │ Use this │  │ Stop too wide for  │
        │ lot size │  │ capital. Skip or   │
        └──────────┘  │ find tighter setup │
                      └────────────────────┘
```

---

## 4. Recovery Mode Protocol

```
           ┌─────────────────────┐
           │   LOSS OCCURS       │
           └──────────┬──────────┘
                      │
                      ▼
           ┌─────────────────────┐
           │ Urge to trade       │
           │ immediately?        │
           └──────┬──────┬───────┘
                 YES      NO
                  │        │
                  ▼        ▼
        ┌──────────────┐  Normal
        │ STOP         │  process
        │ Do NOT place │
        │ the trade    │
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ Stand up     │
        │ Leave screen │
        │ 10 minutes   │
        └──────┬───────┘
               │
               ▼
        ┌──────────────────────────────┐
        │ "Would I take this trade     │
        │  with zero P/L today?"       │
        └──────────┬───────────┬───────┘
                  YES           NO
                   │             │
                   ▼             ▼
          ┌─────────────┐  ┌──────────────────┐
          │ Re-enter at │  │ Do NOT trade     │
          │ HALF size   │  │ Loss is fine     │
          │ only        │  │ Session resumes  │
          └─────────────┘  └──────────────────┘
```

---

## 5. Sizing After Consecutive Losses

```
              TRADE RESULT
                   │
         ┌─────────┴─────────┐
         WIN                 LOSS
          │                   │
          ▼                   ▼
    ┌───────────┐    ┌─────────────────┐
    │ Next:     │    │ Loss count      │
    │ 1% risk   │    │ today?          │
    │ (normal)  │    └──┬──────┬────┬──┘
    └───────────┘      1st   2nd  3rd+
                        │      │     │
                        ▼      ▼     ▼
                  ┌────────┐ ┌────┐ ┌──────────┐
                  │ Same   │ │Half│ │ SESSION  │
                  │ size   │ │size│ │  ENDS    │
                  │ 1% risk│ │0.5%│ └──────────┘
                  └────────┘ └────┘

    ══════════════════════════════════
    RULE: You NEVER increase size
          after a loss. EVER.
    ══════════════════════════════════
```

---

## 6. Emergency Circuit Breakers

```
    ┌─────────────────────────────────────┐
    │     MONITOR ACCOUNT HEALTH          │
    └──────────────────┬──────────────────┘
                       │
                       ▼
           ┌───────────────────────┐
           │ Account down 20%      │──YES──► STOP live trading
           │ from starting capital?│         Simulation only
           └───────────┬───────────┘         4 weeks minimum
                      NO
                       │
                       ▼
           ┌───────────────────────┐
           │ Daily limit broken    │──YES──► Reduce ALL sizes
           │ more than 2× in month?│         by 50% next month
           └───────────┬───────────┘
                      NO
                       │
                       ▼
           ┌───────────────────────┐
           │ 3 consecutive         │──YES──► No trading week 4
           │ losing weeks?         │         Chart review only
           └───────────┬───────────┘
                      NO
                       │
                       ▼
           ┌───────────────────────┐
           │  Continue normal      │
           │  trading              │
           └───────────────────────┘
```
