# AQUANT FIN V SERIES

## A Layered Quantitative Market-State and Trade-Qualification Architecture for Intraday Systematic Trading

**AQUANT FIN V SERIES** is an independent quantitative research project investigating intraday systematic trading as a **layered decision problem**, rather than as a simple BUY/SELL signal-generation problem.

The research explores how market-state representation, statistical flow characterization, liquidity and structural context, exhaustion-aware qualification, execution-state control, and post-trade telemetry can be integrated into a controlled quantitative research architecture.

---

## Core Research Systems

### ALIM V19.2 PRO
**Adaptive Liquidity & Intelligence Model**

The principal demonstrated strategy implementation, combining:

- Multi-factor market-state representation
- Directional-flow proxies
- Statistical order-flow analysis
- Liquidity and structural context
- Institutional/reversal conditions
- CVD and liquidity-sweep analysis
- Higher-timeframe context
- Exhaustion-aware veto logic
- Non-exhausted pullback qualification
- Deterministic weighted scoring
- Adaptive position lifecycle management

### QUANTUM-2 V24.3

Research and execution-state extension incorporating:

- Explicit execution-state modelling
- Finite-state execution architecture
- Market-state classification
- Discrete velocity and acceleration features
- Trade-level MFE/MAE telemetry
- Exit attribution
- Execution latency and state-transition tracking
- Shadow Audit
- Controlled hypothesis experimentation
- Research governance and configuration traceability

---

## Research Question

The central research question is:

> **Can a layered representation of market state, combined with explicit trade qualification, exhaustion-aware veto logic and execution-state control, provide more informative trade selection than a signal-only framework?**

This remains an empirical research question.

The project therefore treats performance improvement as something to be **tested rather than assumed**.

---

## Conceptual Architecture

```text
Market Observations
        ↓
Feature Construction
        ↓
Market-State Representation
        ↓
Statistical Flow State
        ↓
Structure / Liquidity Context
        ↓
Trade Qualification
        ↓
Exhaustion Veto / Pullback Quality
        ↓
Deterministic Decision Layer
        ↓
Execution-State Control
        ↓
Position Management
        ↓
Trade Telemetry
        ↓
Shadow Audit
        ↓
Controlled Research
