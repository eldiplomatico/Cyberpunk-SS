# Investigation Tasking — Data Center Zero-Water Claim: Entity Legitimacy & Claim Verification

**Date:** 2026-08-11
**Method:** OSINT Entity Profile → Analysis of Competing Hypotheses (Heuer); scoring C = Consistent, I = Inconsistent, A = Ambiguous, NA = Not Applicable
**Trigger:** Social media post amplifying an unattributed claim about a data center in Hiawatha with zero water consumption; community note cites peer-reviewed counter-evidence.

---

## Source Material

- **Platform:** Instagram Reels
- **Amplification account:** @celebrityscope
- **Content:** Video (2:22) featuring an unidentified older male stating: *"I have a data center right now that's running in Hiawatha..., I've never used 1 gallon of water."*
- **Community Note (Instagram):** Fact-check stating closed-loop cooling systems use ~70% less water than evaporative, but 75–90% of global data centers use evaporative cooling systems due to cost and energy savings; water consumed in evaporative cooling does not re-enter the water cycle; water cooling reduces available freshwater for locals and increases cost at tap.
- **Cited source:** University of Georgia, College of Agricultural & Environmental Sciences, Field Report — *"Understanding How Data Centers Impact Surface and Ground Waters"* (TP 121). Topics: PFAS, Pollution and Contaminants, Water, Well Water.

---

## Analytical Questions

**Group 1 (Entity Legitimacy):** Who is making this claim, and does the entity behind it have the operational profile, technical infrastructure, and track record consistent with the claim?

**Group 2 (Technical Claim Verification):** Is the zero-water-usage claim technically plausible given the identified facility's cooling architecture, local climate, and operational scale?

**Group 3 (Amplification & Narrative):** What explains the amplification of this claim through @celebrityscope, and does the distribution pattern suggest organic content, paid promotion, or coordinated narrative placement?

---

## Hypotheses

### Group 1 — Entity Legitimacy
- **H1: Legitimate operator, accurate representation.** The speaker is the verified owner/operator of a real data center in Hiawatha with the described characteristics.
- **H2: Legitimate operator, exaggerated claims.** The speaker operates a real facility but overstates its environmental performance (zero water is aspirational or applies to a narrow definition, e.g., excluding indirect water use from grid electricity generation).
- **H3: Shell entity or undisclosed affiliate.** The "data center" is a front, a nominal facility, or the speaker is representing an entity they do not control — the claim serves a narrative purpose unrelated to the facility's actual operations.
- **H4: Misidentified or conflated facility.** The speaker references a real facility but conflates it with a different operation, or the facility exists but does not match the operational profile claimed.

### Group 2 — Technical Claim Verification
- **H1: Genuinely zero-water cooling (air-cooled or immersion).** The facility uses air-cooled heat exchangers, rear-door heat exchangers, or immersion cooling that requires no water makeup.
- **H2: Closed-loop with negligible but non-zero water use.** The facility uses a closed-loop system that minimizes but does not eliminate water consumption (blowdown, makeup water, seasonal supplementation).
- **H3: Evaporative cooling with misrepresented water sourcing.** The facility uses standard evaporative cooling but the speaker defines "water use" narrowly (e.g., excludes municipal supply by using on-site well water, reclaimed water, or rainwater capture).
- **H4: Facility is sub-scale.** The "data center" is a small edge deployment, colocation cabinet, or home-lab-scale operation where zero water is trivially true but misleading in the context of the industry-wide water debate.

### Group 3 — Amplification & Narrative
- **H1: Organic content.** @celebrityscope independently found and reposted the clip as engagement bait with no coordination with the speaker or any third party.
- **H2: Industry PR / greenwashing campaign.** The content was produced or seeded by a data center operator, trade association, or PR firm to counter growing public concern about data center water consumption.
- **H3: Platform-native engagement farming.** @celebrityscope is a content mill that repurposes trending controversy (data center water debate) for engagement metrics — no industry coordination, but also no editorial judgment on accuracy.
- **H4: Coordinated counter-narrative.** The clip is part of a broader, multi-platform effort to reframe the data center water narrative ahead of regulatory action, local permitting fights, or shareholder scrutiny.

---

## Tasked Searches — 15 Items

### Priority 1 (1–6): Entity Identification & Verification
1. Identify the speaker in the video — facial recognition search, reverse image, public records for data center operators in Hiawatha (Iowa or Kansas — disambiguate).
2. Business entity search: data center companies registered or operating in Hiawatha — state corporate filings, commercial real estate records, building permits, utility interconnection agreements.
3. Local news and municipal records: any data center development, zoning changes, tax incentive applications, or public comment proceedings in Hiawatha involving the identified entity.
4. Environmental permits and water use records: state environmental agency filings, water withdrawal permits, NPDES permits, air quality permits for the identified facility.
5. Public utility data: power purchase agreements, grid interconnection filings, or load-serving entity records indicating the facility's actual operational scale (MW).
6. Speaker's public profile: LinkedIn, corporate bios, prior media appearances, conference talks, board memberships, investor disclosures — establish pattern of claims.

### Priority 2 (7–11): Technical & Environmental Verification
7. Facility cooling architecture: any public disclosures, engineering filings, vendor case studies, or trade press coverage describing the specific cooling technology in use.
8. UGA Field Report (TP 121) — full text review: extract specific findings on closed-loop vs. evaporative water consumption, PFAS contamination pathways, and groundwater impact data relevant to the Hiawatha facility's geography and climate zone.
9. Climate and hydrogeological context: annual temperature and humidity profiles for Hiawatha; determine whether air-cooled or dry-cooled systems are operationally viable year-round at that location without water-based supplementation.
10. Industry benchmarks: PUE and WUE benchmarks for data centers in comparable climate zones — what is the realistic floor for water consumption at various scales?
11. Comparable claims: identify other data center operators who have made zero-water-usage claims — were those claims sustained, qualified, or retracted upon scrutiny?

### Priority 3 (12–15): Amplification & Narrative Analysis
12. @celebrityscope account profile: creation date, posting cadence, content themes, follower demographics, engagement patterns — classify as organic creator, content mill, or coordinated account.
13. Cross-platform propagation: has this specific clip or claim appeared on other platforms (X/Twitter, TikTok, YouTube, Reddit, Facebook)? Map the distribution timeline and identify first-mover.
14. Narrative landscape: is there a broader coordinated effort to counter data center water-consumption criticism? Identify trade association campaigns, industry white papers, or PR firm involvement in the data center water debate (2025–2026).
15. Local opposition or support context: are there active community disputes, permitting fights, or environmental lawsuits involving data centers in Hiawatha or the surrounding region? This establishes whether the claim has a specific local audience or serves a broader industry narrative.

---

## Source Tiering Requirements

All findings must carry explicit source tiers:
- **Institutional:** Government filings, academic publications, court records, regulatory databases.
- **Corporate/Disclosed:** Company filings, SEC disclosures, investor presentations, press releases with named spokespeople.
- **News (corroborated):** Multiple independent outlets reporting with named sources or verifiable documentation.
- **News (single-thread):** Single outlet or single-sourced reporting.
- **Analysis/Opinion:** Trade press analysis, blog posts, social media commentary, influencer content.
- **SOCMINT (unverified):** Social media content without independent corroboration.

Confidence assessments required for each finding. Flag any finding where the source tier is insufficient to score with confidence.

---

## Deception/Denial Scan Priorities

1. **Definition games on "water use."** The most likely deception vector is narrow definition: excluding indirect water (grid electricity generation), well water vs. municipal water, or cooling water vs. total facility water (sanitation, fire suppression, humidification). Task searches must distinguish "zero water for cooling" from "zero water, full lifecycle."
2. **Facility scale mismatch.** A sub-scale facility (< 1 MW) making zero-water claims that are technically true but misleading when invoked in the context of hyperscale data center water debates. Verify actual operational capacity.
3. **Astroturf amplification.** If @celebrityscope is an organic account, the amplification question collapses — but if the account shows coordinated behavior, the entire claim's provenance is suspect. Do not assume organic without evidence.
4. **Temporal cherry-picking.** The speaker may reference a period (e.g., winter months) when air-cooled systems genuinely require no water, then generalize to "never used a gallon." Check whether the claim holds across annual operating cycles.

---

## Deliverable Format

Produce an ACH-structured report with:
1. BLUF — key matrix outcomes and bottom-line assessment of entity legitimacy and claim validity.
2. Numbered findings per group, each with source, tier, confidence, scoring against all group hypotheses, and analytic note.
3. Formal ACH matrices (Annex A) — evidence × hypothesis with C/I/A/NA scoring and inconsistency counts.
4. Cross-group bridge analysis — does the entity legitimacy assessment change the weight of the technical claim, or vice versa? Does the amplification pattern suggest the technical claim is instrumentalized?
5. Deception/denial outcomes — which scan priorities fired, which were clean?
6. Collection priorities for follow-up — what evidence would be most discriminating but was not obtainable in this cycle?
