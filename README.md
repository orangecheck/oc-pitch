## OrangeCheck — Bitcoin-Collateralised Identity for Every Human, Bot & Machine

### 0.  The One-Liner
**OrangeCheck** is the company that created and stewards the open-source [**OrangeCheck Protocol**](github.com/orangecheck/oc-whitepaper). The protocol lets any username, API key or device ID escrow a live Bitcoin deposit—once—then reuse that bonded identity everywhere. Sybil attacks become unaffordable, log-ins become one-click, and reputation is now backed by energy, not paperwork.

> “**Everybody can post a security-deposit; if you cheat, you lose it.   
> That one primitive disinfects the entire Internet.**”  
> — *Michael Saylor*

---

### 1.  Why This Is the Killer App Bitcoin Has Waited For
| Web Problem | Existing Fix | Fatal Flaw | OrangeCheck Answer |
|-------------|--------------|-----------|--------------------|
| Bots & spam | CAPTCHAs, phone OTP | Annoy users, cost \$-fractions | One bonded handle ⇢ slash on abuse; no friction for honest users |
| API abuse & jail-breaks | Rate limits, per-IP tracking | Arms race, high false-positives | Each key must carry a Bitcoin bond; break rules, lose sats |
| Fractured log-ins | OAuth silos, password managers | Phishing, central KYC troves | Same key that guards bond signs every log-in (BIP-322) |
| “Proof of personhood” schemes | New tokens, biometrics | Custodian & privacy nightmare | Proof = visible, slash-able stake; nothing else |

**Three immutable truths drive the fly-wheel:**

1. **Linear Sybil cost** – Fake accounts now cost real Bitcoin, forever.  
2. **Zero marginal friction** – Stake once, act freely; no pay-per-post tolls.  
3. **Instant verification** – One `gettxout` or LN probe answers “is this user still staked?”

---

### 2.  Business Model — Trust-as-a-Service

| Product | Revenue Engine | Why It Scales Fast |
|---------|----------------|--------------------|
| **Bond Bank** (custody-optional) | 10 bp annual fee on pooled user deposits; yields routed liquidity fees back to users | Tens of millions in bonds = high-margin float |
| **Edge Verify API** | \$-tiered requests | Every site & device must query badge status; volume exponential |
| **Sybil Intel & Risk Feed** | Enterprise licence | AI vendors & fintech plug in for automatic ban-hammer + compliance |
| **White-Label Wallet SDK** | % of Lightning routing & recovery insurance | Wallets embed in a week; we monetise in-wallet flows |
| **Slash Escrow** | 5 % fee on confiscated bonds | Bad actors literally pay our upside |

> **Unit economics**: 50 M daily verifications @ \$0.0002 = \$10 k ARR per mid-size customer; infra cost ~\$800 ⇒ 92 % gross margin.

---

### 3.  TAM & Network-Effect Moat

* **Social + Creator** \$25 B bot-mitigation spend        
* **AI / API Keys** \$10 B lost annual abuse                    
* **DePin / IoT** 1 B devices need tamper-proof ID              
* **Bitcoin Treasuries** \$100 B idle BTC seeking productive yield  

The first company to aggregate **global stake-weighted reputation data** becomes the **Experian of the permissionless Internet**.  Bonds are portable, but score history is sticky—our analytics moat deepens with every verification.

---

### 4.  Why We’ll Win

1. **First-mover protocol authorship** — like Red Hat to Linux, we publish the spec and capture enterprise support dollars.
2. **Bitcoin-only** — zero alt-token risk, maximal regulatory clarity.
3. **No block-bloat** — sub-dust UTXO or off-chain HTLC; critics can’t cry “spam chain.”
4. **Cash-flow from Day 1** — Verify API already in private beta; two wallets committed to embed SDK Q3.

---

### 5.  Traction & Roadmap

* **Pilot Nostr relay:** 78 % bot reduction with 20 000-sat bonds.  
* **MVP Verify API:** 30 ms median latency across three PoPs.  
* **Q1 ’26:** 1 M live bonds → \$50 M pooled BTC → \$5 M Bond-Bank float.  
* **Q4 ’27:** \$8 M ARR, 90 % gross margin, cash-flow positive.

---

### 6.  Team & Ask

* **Wil N.** — Co-Founder OrangeCheck, Infinite Engineer
* **Zahid I.** — Co-Founder OrangeCheck, Infinite Engineer

**Raise:** \$1.5 M seed → 18-month runway → Bond Bank launch, SDK rollout, Series A optional.  

---

> **OrangeCheck turns Bitcoin’s thermodynamic certainty into a universal trust layer.**  
> Stake is the new captcha.  Proof-of-work is now proof-of-person.  Help us mint the reputation standard for the next trillion-user Internet.
