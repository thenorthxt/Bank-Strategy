# Bank Strategy ($BANK)

Bank Strategy is an interest-bearing memecoin framework designed around one idea:

**What if a memecoin behaved more like a bank?**

Instead of relying purely on speculation, Bank Strategy converts trading activity into real on-chain yield distributed directly to holders.

Holdings become deposits.  
Fees become interest.  
Distribution becomes automatic.

---

# Core Thesis

Traditional memecoins reward attention.

Bank Strategy rewards deposits.

The system routes protocol fee flow into USDC distributions,
creating a holder-aligned reserve mechanism inspired by banking infrastructure.

The more $BANK held,
the larger the share of generated interest.

---

# How It Works

## High-Level Flow

1. Trading activity generates protocol fees
2. Fees accumulate into the treasury
3. Treasury converts fees into USDC
4. USDC is distributed proportionally to eligible holders
5. Larger deposits receive larger yield allocation

The mechanism operates continuously and transparently on-chain.

---

# Deposit Logic

In Bank Strategy, holdings are treated as deposits.

## Interest Weighting

Interest allocation is based on:
- wallet balance
- holding duration
- eligibility thresholds
- anti-sybil protections

Example:
- larger balances → larger share
- longer holding duration → higher weighting
- short-term churn → reduced eligibility

The goal is to reward stable deposits,
not speculative rotation.

---

# Yield Source

Yield does not come from inflation.

Yield comes from:
- trading fees
- protocol activity
- treasury routing

USDC distributions are funded by real inflows,
not synthetic emissions.

---

# Treasury Logic

The treasury operates as a reserve layer.

Possible routing:
- USDC distributions
- reserve stabilization
- strategic liquidity management
- protocol operations

All routing rules are transparent and configurable.

---

# Anti-Extraction Design

Bank Strategy includes mechanisms to reduce abusive farming behavior:
- cooldown periods
- minimum holding windows
- time-weighted deposits
- capped short-term extraction

The system is optimized for long-term participation.

---

# Design Principles

- Holder-aligned yield
- Transparent treasury flows
- Real distributions
- Sustainable routing
- Deposit-oriented incentives

This is not “staking.”
This is deposit-based participation.

---

# Repository Structure

- `docs/` — treasury logic, distribution specs
- `scripts/` — simulations and payout modeling
- `programs/` — future on-chain distribution logic
- `apps/` — dashboards and treasury monitoring
- `packages/` — reusable primitives

---

# Status

Bank Strategy is currently in the design and modeling phase.

This repository documents:
- yield distribution mechanics
- treasury routing
- holder weighting logic
- reserve assumptions

Parameters remain subject to iteration.

---

# Closing

Banks pay interest on deposits.

Bank Strategy applies the same principle on-chain.

Holdings become deposits.  
Activity becomes yield.
