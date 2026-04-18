# Trading System — Nifty/BankNifty Options
### Built for: Indian Futures & Options Market | Capital: Under 5 Lakhs

---

## The One Rule That Overrides Everything

> **You do not have a market problem. You have a recovery-mode problem.**

When you are in recovery mode — trying to win back a loss — you are not trading anymore. You are gambling with leverage. This system is designed to make recovery mode structurally impossible.

---

## Part 1 — Risk Architecture (Non-Negotiable)

These rules are not guidelines. They are circuit breakers. Violating them means you are not following the system.

### Rule 1 — Maximum Risk Per Trade

```
Capital under 5 lakhs → Risk no more than 1% per trade

5 lakhs × 1% = ₹5,000 maximum risk per trade

This is your stop-loss size. Position size derives FROM this — not the other way around.
```

**How to calculate lot size from this:**
1. Define your stop-loss in points (e.g., 20 points on BankNifty options)
2. BankNifty lot = 15 units, Nifty lot = 25 units
3. Max risk ₹ ÷ (stop points × lot size) = number of lots

Example — BankNifty option trade:
- Max risk: ₹5,000
- Stop: 25 points from entry
- BankNifty lot size: 15
- Max lots = 5000 ÷ (25 × 15) = 13.3 → trade 1 lot only

**Never reverse-engineer lots first and justify the risk after.**

---

### Rule 2 — Daily Loss Limit (The Recovery Mode Killer)

```
Daily Loss Limit = 2% of capital = ₹10,000

When this limit is hit → session ends immediately.
No exceptions. No "one more trade to recover."
```

This rule exists for one reason: your blow-up pattern is **increasing size after a loss**.
The daily loss limit means there is no "after a loss" — the session is over.

**What to do after hitting the daily limit:**
1. Close all positions
2. Log off the trading platform
3. Write in your journal: what happened, what emotion you felt, what the urge to keep trading felt like
4. Do not re-open the platform until the next session

---

### Rule 3 — Weekly Loss Limit

```
Weekly Loss Limit = 5% of capital = ₹25,000

After 2.5 consecutive losing days → no trading on day 3.
```

This prevents a bad week from turning into an account-ending week.

---

### Rule 4 — Position Sizing After a Loss

This is the direct antidote to your specific blow-up pattern:

```
After 1 losing trade  → Next trade: same size (1% risk)
After 2 losing trades → Next trade: HALF size (0.5% risk)
After 3 losing trades → Session ends (daily limit likely hit anyway)

You NEVER increase size after a loss.
```

Write this on a card and tape it to your monitor.

---

## Part 2 — The Pre-Trade Checklist

Before entering ANY trade, answer all 5 questions. If any answer is NO — do not trade.

```
[ ] 1. LOCATION  — Is price at a meaningful S/R level on the 15min/1hr chart?
[ ] 2. SIGNAL    — Is there a candle pattern showing rejection or confirmation?
[ ] 3. CONTEXT   — Does the 1hr or daily chart agree with this direction?
[ ] 4. STOP      — Do I know exactly where my stop is, in points?
[ ] 5. RISK      — Have I calculated lot size from my stop, within my 1% limit?
```

All 5 YES = you may enter.
Any 1 NO = wait. Do nothing. Doing nothing is a position.

**The 6th unwritten question (answer honestly before every trade):**
"Am I entering this because it's a valid setup, or because I want to make back what I lost?"
If the answer is the second one — do not trade.

---

## Part 3 — Trade Structure

Every trade must be defined before entry:

```
ENTRY PRICE     : ___________
STOP LOSS       : ___________ (points: ___)
TARGET 1 (T1)   : ___________ (first S/R obstacle — take 50% off here)
TARGET 2 (T2)   : ___________ (trail remainder with structure)
LOT SIZE        : ___________ (derived from risk calc, not gut feel)
SETUP TYPE      : TST / BOF / BPB / PB / CPB
REASON (1 line) : ___________
```

You do not enter a trade that you cannot fill this out for. If you cannot articulate the setup type and reason — it is not a setup.

---

### Stop Loss Rules

- Stop is placed where your trade thesis is proven wrong — just beyond the structure
- Stop is entered as an order on the platform at the moment you enter the trade
- Stop is **never moved against you** (wider) — it may only be moved in your favour
- If stopped out: accept it. Record it. Move on. It is the cost of operating the system.

---

### Options-Specific Notes

Options decay (theta) works against you every day. For Nifty/BankNifty options:
- Avoid holding options through weekends unless you have a strong directional conviction
- Do not buy deep OTM options as lottery tickets — this is disguised gambling
- Prefer slightly OTM or ATM options for defined-risk directional trades
- Expiry-day trading has extreme gamma risk — apply stricter rules: 0.5% risk limit per trade on expiry day

---

## Part 4 — Session Procedure

### Before Market Open (8:45 AM – 9:15 AM)

```
[ ] Review Nifty and BankNifty daily chart — what is the higher timeframe context?
[ ] Mark key S/R levels on 1hr chart (use yesterday's high/low, weekly pivot, recent structure)
[ ] Note the trend: uptrend / downtrend / sideways
[ ] Identify 2–3 areas where a valid setup could form today
[ ] Check your current capital and recalculate your 1% risk amount
[ ] Write your bias or "no bias — I will wait for clarity"
[ ] Check your emotional state — are you carrying yesterday's loss emotionally?
```

**If you had a losing day yesterday:** Double your caution today. Size down to 0.5% automatically.

---

### During Session (9:15 AM – 3:30 PM)

```
[ ] Watch for price to arrive at your pre-identified setup areas
[ ] Do NOT look for trades in random price space
[ ] When price arrives at setup area: apply Pre-Trade Checklist
[ ] Execute only if all 5 checkboxes pass
[ ] After entry: enter stop-loss order immediately
[ ] Set a price alert for T1 and T2
[ ] Do NOT watch the P&L number — watch the price action
```

**Maximum trades per session: 3**
More than 3 setups in a day is suspicious — you may be force-fitting setups.

---

### After Session (3:30 PM – 4:30 PM)

```
[ ] Record every trade in Trade Journal (template below)
[ ] Calculate today's P&L vs daily loss limit
[ ] Rate your process adherence: 1–10 (not your P&L — your rule-following)
[ ] Write one lesson in Lessons Journal
[ ] If you deviated from the plan at any point — write exactly why
```

---

## Part 5 — Trade Journal Template

Fill this for every trade, win or lose:

```
DATE          :
INSTRUMENT    : Nifty / BankNifty Options — [strike] [CE/PE] [expiry]
SETUP TYPE    : TST / BOF / BPB / PB / CPB
TIMEFRAME     : 5min / 15min entry, 1hr context
ENTRY         : ₹___  at ___:___ (time)
STOP          : ₹___  (___  points)
TARGET 1      : ₹___
TARGET 2      : ₹___
LOT SIZE      : ___ lots  |  Capital at risk: ₹___
EXIT          : ₹___  at ___:___
RESULT        : +₹___ / -₹___  |  +___ R / -___ R
---
WHAT I SAW    : (what the chart showed — 2 lines max)
WHAT I FELT   : (emotional state at entry and exit — honest)
RULE FOLLOWED : YES / NO — if NO, which rule and why
LESSON        : (one sentence — what to carry forward)
```

---

## Part 6 — The Recovery Mode Protocol

This is the most important section. Read it after every loss.

### What recovery mode feels like:
- "I need to make this back today"
- "One more trade — it will definitely work"
- "I'll use a bigger size, quicker recovery"
- "The market owes me this"
- "This setup is not perfect but I'll take it anyway"

### What recovery mode actually is:
Your prefrontal cortex (rational decision-making) has been partially disabled by the stress of the loss. You are not thinking clearly. Your amygdala (threat response) is running the trade. This is not a metaphor — it is neuroscience.

### The protocol when you feel recovery mode triggering:

```
Step 1 — STOP. Do not place the trade.
Step 2 — Stand up. Leave the screen for 10 minutes. No exceptions.
Step 3 — Return and ask: "Would I take this trade if I had no position today?"
Step 4 — If yes: take it, but at HALF your normal size.
Step 5 — If no: you already knew the answer. The loss for today is acceptable.
```

**The math on why recovery mode destroys accounts:**

You are down ₹10,000. You double your size to recover. Now your next trade risks ₹10,000. If it loses: you are down ₹20,000. You double again. Risks ₹20,000. If it loses: down ₹40,000. This is exactly how a 5-lakh account becomes a 0 account in a single afternoon.

The only recovery that works is: accept today's loss, trade tomorrow at normal size, let the edge play out over many trades.

---

## Part 7 — Performance Tracking

Track these weekly. Not daily — weekly. Daily P&L tracking feeds emotional volatility.

| Metric | Formula | Target |
|---|---|---|
| Win Rate | Wins ÷ Total trades | 40–50% (not a goal, an observation) |
| Average Win | Sum of winning trades ÷ Number of wins | Should be in R units |
| Average Loss | Sum of losing trades ÷ Number of losses | Should be ~1R |
| Expectancy | (Win% × Avg Win R) – (Loss% × 1R) | Must be positive over 50+ trades |
| Process Score | Sum of daily process ratings ÷ days | Goal: ≥7/10 consistently |
| Rule Violations | Count per week | Goal: 0 |

**The most important number is Process Score, not P&L.**

A process score of 9/10 with a losing week = good week.
A process score of 4/10 with a winning week = dangerous week (you got lucky, not skilled).

---

## Part 8 — The Weekly Review

Every weekend (30–45 minutes):

```
[ ] Review all trades from the week — chart by chart
[ ] For each trade: was the setup valid? was execution correct?
[ ] Identify your best trade (highest quality process, regardless of outcome)
[ ] Identify your worst trade (most impulsive, most rule-breaking)
[ ] Extract one pattern you want to improve next week
[ ] Check if you hit any of your limits (daily/weekly)
[ ] Read your Motivation Journal entry — reconnect with why you are doing this
```

---

## Part 9 — Emergency Rules

### If account drops 20% from starting capital (₹1 lakh lost):
→ Stop live trading completely. Return to simulation for 4 weeks minimum.

### If you break the daily loss limit rule more than twice in a month:
→ Reduce all trade sizes by 50% for the following month. No exceptions.

### If you have 3 consecutive losing weeks:
→ Do not trade week 4. Spend it reviewing charts, identifying what setups you missed, what setups you forced.

---

## The System in One Page

```
BEFORE:    Mark S/R. Identify setup areas. Know your 1% risk number.

ENTRY:     5-question checklist. All pass = enter. Any fail = wait.
           Define stop, T1, T2, lot size BEFORE entering.
           Enter stop-loss order IMMEDIATELY after entry.

AFTER:     Record trade. Rate your process 1–10. Write one lesson.

LIMITS:    1% per trade. 2% daily. 5% weekly.
           Hit the daily limit → session over, no exceptions.

AFTER LOSS: Same size next trade. Never bigger. Never "just one more."

RECOVERY MODE: Recognize it. Leave screen. Come back smaller.

JUDGE YOURSELF ON: Process adherence, not P&L.
```

---

*This system is built on YTC Price Action Trader principles by Lance Beggs, adapted for Indian equity derivatives markets.*
