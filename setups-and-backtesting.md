# Setups — Identification, Signals & Backtesting

---

## What Is a Setup?

A **setup** is a specific market condition where the probability of price moving in your favour is higher than random — justified by a reason, not a feeling.

It has three components that must all be present:

```
1. LOCATION  — where price is (a meaningful S/R level, structure area)
2. SIGNAL    — what price is doing at that location (rejection, confirmation)
3. CONTEXT   — does the higher timeframe agree with the trade direction?
```

If any one of these is missing, it is not a setup — it is a guess.

### The Three Questions a Setup Must Answer with "Yes"

| Question | What You're Checking |
|---|---|
| Is price at a meaningful area? | Location has value — not random space |
| Is there evidence of the move starting? | Price is showing its hand |
| Is the broader market aligned? | You're not fighting the trend |

All three yes = setup exists. Enter with a defined stop and target.
Any one no = stand aside and wait.

### The Correct Order of Operations

Most beginners reverse this. They see a signal first and then hunt for a reason. That is backwards.

```
1. Identify the location first  (where should I be watching?)
2. Wait for price to arrive     (patience)
3. Watch for the signal         (is it showing intent to move?)
4. Check context                (higher TF agrees?)
5. Then and only then — execute
```

> A setup is not something you find. It is something you **wait for**.

---

## The 5 Setup Types

All are variations of one idea: **price arrives at a significant area and shows evidence of holding or breaking.**

| Setup | Description | Emotional Driver |
|---|---|---|
| **TST** — Test of Support/Resistance | Price probes a level, shows rejection | Trapped traders panic, fuel the reversal |
| **BOF** — Breakout Failure | Break fails and reverses | Breakout traders trapped, they fuel the move back |
| **BPB** — Break-Pull-Back | Confirmed break, then pullback to the broken level | Latecomers join, early traders add to position |
| **PB** — Pullback in Trend | Trend continuation after a retracement | Dominant emotional bias; pullback = opportunity |
| **CPB** — Complex Pullback | Multi-leg pullback before continuation | Tests weak hands more thoroughly than simple PB |

---

## Identifying Setup Signals

A signal is **price behaviour at the location that tells you the move is beginning**. You are reading the candles for evidence of intent.

### The Two Signal Types

**1. Rejection Signal** — price arrives at a level and gets pushed back

```
What to look for:
- Long wick into the level, small body closing away from it
- Two or more candles probing the level, failing to close through
- A sharp reversal candle (engulfing, pin bar) right at the area
```

**2. Continuation Signal** — price pauses in a trend, then resumes

```
What to look for:
- Candles slow down and tighten in range (compression)
- A breakout candle closes strongly beyond the compression
- Volume (if available) expands on the breakout candle
```

### Signal Checklist

Before calling it a signal, ask:

| Check | What It Means |
|---|---|
| Where exactly did it happen? | Must be at your pre-identified location, not random |
| What did the wicks tell you? | Wicks = rejection; bodies = conviction |
| Did it close or just probe? | A close is stronger evidence than an intrabar wick |
| Was the signal candle decisive? | Small indecision candles are not signals |
| Did the next candle confirm? | One candle alone is often not enough |

---

## Backtesting Process

Backtesting is how you build **statistical confidence** in your ability to identify setups before risking real money.

### Two Methods

**Method 1 — Static Chart Review** *(faster, good for pattern recognition)*

```
1. Open a historical chart — go back 3–6 months
2. Cover the right side of the chart
3. Reveal it bar by bar
4. At each bar, ask: is there a setup here?
5. If yes — record your entry, stop, target
6. Reveal forward to outcome
7. Log the result. Move to the next section.
```

**Method 2 — Market Replay** *(better, builds real execution skills)*

```
1. Use a platform with replay functionality
   (TradingView, Sierra Chart, NinjaTrader)
2. Set replay to your trading timeframe
3. Run it at speed — treat it exactly like a live session
4. Follow your full pre-session → during → post-session routine
5. Goal: simulate real conditions, not just spot patterns
```

> Market replay is superior because it forces decisions **in real time** without knowing what comes next. Static review allows you to unconsciously cheat.

---

## What to Record for Every Backtest Trade

```
Date & Time         — when the setup occurred
Market & Timeframe  — what you were trading
Setup Type          — TST / BOF / BPB / PB / CPB
Location            — what S/R level or structure area
Signal Description  — what exactly triggered the entry
Entry Price         — where you entered
Stop Price          — where you were wrong
T1 Price            — first target
T2 Price            — second target (if applicable)
Outcome             — T1 hit / T2 hit / stopped out / scratched
R:R Achieved        — actual reward relative to risk
Notes               — what was clean, what was messy, what you'd do differently
```

---

## Evaluating Your Backtest Results

Do not evaluate after 10 trades. You need a **minimum of 50, ideally 100** for statistically meaningful data.

### The Numbers That Matter

```
Win Rate       = winning trades / total trades
Average Win    = average R gained on winning trades
Average Loss   = average R lost on losing trades (should be close to 1R)
Expectancy     = (Win% × Avg Win) - (Loss% × Avg Loss)
Profit Factor  = gross profit / gross loss  (aim for > 1.5)
Max Drawdown   = largest peak-to-trough loss sequence
```

### Minimum Acceptable Benchmarks

| Metric | Minimum Acceptable |
|---|---|
| Expectancy | Any positive number |
| Profit Factor | Above 1.3 |
| Max Drawdown | Recoverable within your risk rules |
| Sample Size | 50+ trades before drawing conclusions |

A positive expectancy over 100 trades means your **edge is real**. Now you build execution consistency on top of it.

---

## The Full Process End to End

```
PHASE 1 — LEARN THE SETUP
└── Study the setup type in theory
└── Find 20 examples on historical charts (identify only, don't trade)
└── Build pattern recognition — what does a clean one look like?

PHASE 2 — STATIC BACKTEST
└── 50–100 trades on historical data, bar by bar
└── Record everything in your Trades Journal
└── Calculate expectancy at the end

PHASE 3 — MARKET REPLAY
└── Replay full sessions — follow your procedures
└── Decisions under time pressure, not hindsight
└── Another 50+ trades. Compare results to Phase 2.

PHASE 4 — SIM TRADING (live market, no real money)
└── Trade the live market in a simulator
└── Real conditions: spread, slippage, news, your emotions
└── 2–3 consistent months before progressing

PHASE 5 — LIVE, MINIMUM SIZE
└── Real money, smallest position size possible
└── Process identical to Phase 4
└── Only new variable is psychological pressure
```

The reason for phases: **each phase adds exactly one new variable**. You isolate what you're learning at each stage rather than trying to master everything at once.

---

> Backtesting tells you if the **pattern has edge**.
> It does not tell you if **you can execute it under pressure**.
> That is what Phases 4 and 5 reveal. Most traders discover their real problem there, not in Phase 2.
