# Claude Validation: Scrap Collection App (Scrappy)

| | |
|---|---|
| **Source** | `scrappy.md` |
| **Pitched by** | Ramesh |
| **Validated on** | 2026-10-04 |
| **Score** | **14/35** |
| **Verdict** | **Kill it** (adjacent pivot: corporate IT asset disposal) |

---

## 1. Quick Take

This is a real behaviour but a weak problem. Urban Indians already have a kabadiwala who comes to the door, pays cash and haggles in 10 minutes. The pitch has to beat a free, trusted, cash-paying service, and its answer is "reward points". The unit economics of household scrap don't work: a ₹300 pickup leaves about ₹30–60 of margin, and the truck and agent cost more than that.

## 2. The Five Fatal Questions

**Q1: Who is the customer, and would they pay for this today?**
- **Households:** they don't pay. They expect to *be paid*, and the local kabadiwala already pays cash on the spot. Willingness to pay is negative.
- **Kabadiwalas:** they won't pay for a "B2B platform". They work in cash, have thin margins and already know where to sell.
- **Industrial recyclers:** they pay for *volume and purity* at scale, meaning tonnes of sorted PET or copper. Household pickups don't produce that.
- There's no named customer who would pay today. That's a no.

**Q2: Why hasn't someone built this already?**

Many have:
- **The Kabadiwala** (Bhopal), **ScrapUncle** (Delhi NCR) and **Kabadiwalla Connect** (Chennai) have run app-based household pickups for 5+ years. They're all still small and regional.
- **Recykal** (Hyderabad) succeeded by going **B2B**: EPR compliance credits for producers, plus a recycler marketplace. That's where the money is.
- **Cashify** succeeded only in high-value electronics (phones and laptops), where one item is worth ₹5,000+.
- **What's different now:** the E-Waste (Management) Rules 2022 and plastic EPR mandates create buyers who are *legally required* to pay. None of that helps a household-pickup app.

**Q3: What's the distribution advantage?**

None. Every pickup needs a person and a vehicle. Demand is infrequent (a household declutters every 2–3 months), so customers forget the app between uses. Apartment-society tie-ups (MyGate, NoBrokerHood) are the only cheap channel, and the existing players already use them.

**Q4: Can this be a big business, or is it a feature?**
- **It's a feature.** Urban Company, Swiggy Genie or a society app could add "schedule scrap pickup" in a week.
- **$1M ARR (about ₹8.4 Cr) in net revenue** at roughly ₹40 net margin per pickup means **about 2.1 million pickups a year**, or 5,800 a day. That needs a fleet the size of a logistics company.
- **The ceiling** is a regional services business, not a venture-scale company.

**Q5: Can the founder actually build this?**

The app is easy. The hard parts are physical: managing a fleet of agents, cash handling, weighing disputes, warehousing and sorting. Nobody in the founding group appears to have run logistics operations. On day one you'd need an ops lead who has run last-mile pickups.

## 3. Idea Scorecard

| Dimension | Score | Notes |
|---|---|---|
| Problem severity | 2 | Clutter is a mild annoyance, and the kabadiwala already solves it |
| Market size | 3 | Every urban home generates scrap, but the value per home is tiny |
| Willingness to pay | 2 | Households won't pay; recyclers pay only for bulk, sorted supply |
| Competition gap | 2 | Informal kabadiwalas, ScrapUncle, The Kabadiwala, Recykal, Cashify |
| Distribution | 2 | Infrequent use, manual pickups, no growth loop |
| Timing | 2 | EPR rules help B2B, not household pickups |
| Founder fit | 1 | No logistics or recycling-operations background |
| **Total** | **14/35** | **Significant concerns: a pivot is needed** |

## 4. Validation Experiments

**Experiment 1: Would households pick you over their kabadiwala?**
- **Test:** Do households choose an app pickup over their existing kabadiwala?
- **How:**
  1. Put up flyers and a WhatsApp number in 3 gated societies (about 1,500 homes).
  2. Offer "Free pickup + 10% above kabadiwala rate".
  3. Do the pickups yourselves using a hired tempo.
- **Success:** At least 60 bookings (4%), and at least 20% of those book again within 6 weeks.
- **Time and cost:** 2 weeks, about ₹10,000 ($120).

**Experiment 2: Does one pickup make money?**
- **Test:** What's the contribution margin per pickup?
- **How:**
  1. Log weight, material mix, rate paid, resale price and the agent's time for every pickup in Experiment 1.
  2. Sell the scrap to a local aggregator.
- **Success:** At least ₹50 net margin per pickup after agent and vehicle cost. If you don't reach that, kill the C2B model.
- **Time and cost:** Runs alongside Experiment 1, ₹0 extra.

**Experiment 3: Is there demand for corporate IT asset disposal (the pivot)?**
- **Test:** Will mid-size companies pay for certified IT asset disposal?
- **How:**
  1. Email or call 40 IT or admin heads at 200–2,000-employee companies in Bengaluru and Chennai.
  2. Offer pickup of retired laptops and servers, a certified data wipe, and an EPR-compliant recycling certificate.
  3. Ask for a paid pilot quote.
- **Success:** At least 5 qualified meetings and at least 2 who ask for pricing on a real refresh batch.
- **Time and cost:** 2 weeks, about ₹2,000.

## 5. Verdict: Kill It

The household scrap app competes with a free, cash-in-hand, door-to-door service. Funded players have stayed small for years, and the margin per pickup can't cover the cost of collecting it.

**A better adjacent problem: IT asset disposition (ITAD) for mid-market companies.**
- **Value per pickup:** one laptop batch is worth ₹50k–5L.
- **Forced demand:** the DPDP Act makes certified data erasure a legal requirement, and the E-Waste Rules 2022 require documentation trails.
- **Fit:** an IT-services team already knows the buyer (IT and admin heads).
- **Synergy with idea #3:** a data-destruction certificate is a DPDP compliance artifact.
