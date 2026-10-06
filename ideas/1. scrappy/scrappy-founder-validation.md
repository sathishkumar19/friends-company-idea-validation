# Founder Validation: Scrap Collection App (Scrappy)

| | |
|---|---|
| **Source** | `scrappy.md`, `scrappy-claude-validation.md` |
| **Pitched by** | Ramesh |
| **Validated on** | 2026-10-04 |
| **Claude validation score** | 14/35 |
| **Founder-criteria score** | **15/45** (as pitched) · **30/45** (IT asset disposal pivot) |
| **Verdict for this team** | **Drop the household app.** The IT asset disposal pivot fits this team well and is worth testing. |

> **Founder profile used for this assessment:** Infra/Cloud Architects (datacenter, cloud, software, DevOps). Budget about ₹30L, to be spent in stages. Limited sales experience, willing to learn. Founders based in Bangalore, Australia and the US.
>
> **Note:** the README lists a Friends Criteria Rating of 21/35 for this idea. This file scores the pitch against the seven founder criteria with the team profile above, which gives a lower result.

---

## 1. Bottom Line

The household scrap app is a logistics business: trucks, agents, cash handling, weighing disputes and sorting. None of that uses the founders' skills, all of it must happen physically in India, and the margin per pickup is too small to fund growth on ₹30L.

The pivot changes the picture. **IT asset disposition (ITAD)**, meaning certified data wiping, decommissioning and e-waste-compliant recycling of laptops, servers and storage, is something datacenter and infrastructure architects already understand. The buyer is an IT head, and the DPDP Act and E-Waste Rules 2022 force them to act.

## 2. Founder-Criteria Scorecard (As Pitched: Household App)

| Criterion | Score | Why |
|---|---|---|
| **Domain Fit** | 1 | Consumer logistics and the scrap trade. No overlap with cloud, datacenter or DevOps. |
| **Implementability** | 3 | Can start in 2–3 apartment societies with a hired tempo. Scaling needs a fleet, a warehouse and agents. |
| **Budget Scalability** | 2 | Every new area needs vehicles, people and cash for buying scrap. Costs grow with volume, and ₹30–60 margin per pickup won't pay for it. |
| **AI-Native Potential** | 2 | Photo-based item pricing and route planning are nice extras. The core business is physical. |
| **Target Market** | 2 | Clearly defined (urban households) and reachable through societies, but low value and infrequent use. |
| **Competitive Landscape** | 2 | The local kabadiwala is free, trusted and pays cash. ScrapUncle, The Kabadiwala and Kabadiwalla Connect have stayed small for years. |
| **Remote Collaboration** | 1 | Everything happens on the ground in one Indian city. The Australia and US founders can't contribute meaningfully. |
| **MOAT** | 1 | No defensible moat. Kabadiwalas already have local trust, pricing leverage and pickup relationships built over decades. Any tech overlay can be copied or ignored. |
| **NorthStar / ARR** | 1 | No recurring revenue model. Revenue is ₹30–60 margin per pickup; no subscription path. North Star would be pickups per day, but volume needed for viability is unachievable on ₹30L. |
| **Total** | **15/45** | **Poor fit** |

## 3. Founder-Criteria Scorecard (Pivot: IT Asset Disposition)

| Criterion | Score | Why |
|---|---|---|
| **Domain Fit** | 4 | Datacenter decommissioning, server and storage lifecycle, data sanitisation standards (NIST 800-88) and asset inventories are familiar to infra architects. Recycling operations are not, so partner for those. |
| **Implementability** | 4 | Start as a broker: sell to the customer, do the data wipe and paperwork, and subcontract transport and recycling to authorised e-waste recyclers. |
| **Budget Scalability** | 3 | No warehouse or fleet needed if you partner. Some spend on wiping tools, secure transport and insurance. Working capital needed if you buy assets for resale. |
| **AI-Native Potential** | 3 | AI can read asset lists and photos to value hardware for resale, generate audit-ready certificates and chain-of-custody reports, and match assets to buyers. The wipe itself is not AI. |
| **Target Market** | 4 | Defined: IT and admin heads at 200–2,000-employee companies, GCCs and datacenters. Reachable through the founders' own professional networks. Each deal is worth ₹50k–5L. |
| **Competitive Landscape** | 3 | Authorised recyclers (Attero, E-Parisaraa, Cerebra) and global ITAD firms (Iron Mountain, Sims Lifecycle) exist. **Gap:** a tech-first service focused on data-erasure proof for DPDP, with a clean digital audit trail, for mid-market companies. |
| **Remote Collaboration** | 3 | Physical work stays in India, but certificate platform, valuation and reporting software can be built remotely. ITAD is also a mature market in Australia and the US if the model works. |
| **MOAT** | 3 | DPDP-compliant data-erasure certificates with a verifiable digital chain of custody create stickiness — a company that trusted you for one asset refresh will return for the next. Loses points because the service model is replicable by any authorised recycler who adds a digital layer. |
| **NorthStar / ARR** | 3 | Hardware refresh cycles (laptops every 3–4 years, servers at migration) create natural repeat business. A retainer model (quarterly compliance reporting per device lifecycle) can approach ARR. North Star metric: certified assets disposed per quarter. Not pure ARR — each job must be re-sold unless a retainer is structured. |
| **Total** | **30/45** | **Reasonable fit, worth testing** |

## 4. ₹30L Budget Plan (Pivot Only)

| Stage | Months | Spend cap | What it buys | Gate |
|---|---|---|---|---|
| **0. Prove demand** | 0–2 | ₹1.5L | Recycler partnership agreement, wipe software licence, insurance quote | 2 paid ITAD jobs |
| **1. Service + tooling** | 2–8 | ₹6L | Asset tracking and certificate platform, secure transport contract | 10 jobs and at least 1 repeat customer |
| **2. Scale** | 8–18 | ₹8L | Field technician hire, refurbished-hardware resale channel | ₹50L annual run rate |
| **Reserve** | — | ₹14.5L | Not committed. Could fund another idea in parallel. | — |

## 5. Closing the Sales Gap

- **The buyer is a peer.** IT heads, datacenter managers and procurement leads are people the founders already know from work.
- **Hardware refresh cycles create demand.** Laptop refreshes every 3–4 years and datacenter migrations to cloud produce large disposal batches.
- **Natural bundle with idea #3.** A data-destruction certificate is a DPDP compliance artefact, so the compliance SaaS and ITAD can be sold to the same buyer.

## 6. Working Across Bangalore, Australia and the US

- **Bangalore:** owns operations and customer relationships.
- **Australia and US:** build the certificate and asset platform, and research how ITAD companies there price and package.
- **Limitation:** the business only runs in one Indian city at first. Two of three founders would be in supporting roles.

## 7. Verdict

**Drop the household app.** It fails on domain fit, budget and remote work.

**Test the ITAD pivot cheaply** (Experiment 3 from the Claude validation: 40 calls to IT or admin heads, about ₹2,000). Treat it as a possible add-on to idea #3, not as the main company.
