# ACH Surveillance Report — AI Governance, Lab Economics, Offense/Defense Investment

**Date:** 2026-08-09
**Method:** Analysis of Competing Hypotheses (Heuer); scoring C = Consistent, I = Inconsistent, A = Ambiguous, NA = Not Applicable
**Coverage:** All 20 tasked searches executed (Priority 1: 1–8, Priority 2: 9–15, Priority 3: 16–20), plus two follow-up probes (federal clearance regime; Anthropic defensive research).

---

## BLUF — Matrix Changes This Cycle

1. **Group 1, H4 (governance vacuum) gains its first inconsistency and loses its co-lead.** A federal pre-release review regime is now demonstrably operating with teeth: a June 2 executive order created a 30-day pre-release cyber review channel; the White House held GPT-5.6 for a 12-day gate before release; and the government suspended Anthropic's Fable 5 / Mythos 5 for ~two weeks (June 12–30) under Export Control Reform Act authority, over Anthropic's objection. "No one checks" is no longer consistent with observed events. **H4: 0 → 1.**
2. **Group 1, H2 (capture theater) is now the sole least-disconfirmed hypothesis (0 inconsistencies) — and got stronger.** OpenAI and Anthropic are reported to be co-writing the federal threshold their rivals must clear for launch; the White House is refusing to publish the evaluation framework; open-weight models are excluded from review entirely. This is capture with a mechanism, not just theater.
3. **However, one anticipated H2 confirmation failed:** the July–August containment-breach disclosures were **not** pre-arranged. They trace to a shared third-party evaluation vendor (Irregular), whose misconfigured harness left evaluation machines internet-connected April–July; Anthropic's disclosure was a reactive internal review triggered by OpenAI's announcement, and Meta's incident occurred during an Irregular capture-the-flag test. The coordination was causal/emergent, not strategic. (The downstream effect H2 predicted still occurred — US officials declared the breaches "routine" within hours of Meta's confirmation.)
4. **Group 1, H1 gains a fifth inconsistency.** The FLI AI Safety Index (Summer 2026) finds all four major labs have weakened or voided their unilateral-pause pledges and documents active suppression of internal dissent (non-disparagement enforcement). No safety body blocked anything anywhere.
5. **Group 2: no count changes, but H1 (tech scaling) is alive again as a trajectory.** Two of the matrix's stated H1-revival triggers now show first evidence: cost-curve bending (Jalapeño custom inference chip with claimed ~50% cost savings, plus ~50% software-side inference cost cuts) and sticky consumer retention (ChatGPT Plus 71% at 6 months, best-in-class). Neither yet clears the bar (booked margin improvement), so no inconsistency is removed — flagged as leading indicators.
6. **Group 2 watch item that could transform the matrix:** Anthropic's confidential S-1 is filed, with a projected **first-ever quarterly operating profit** (~$559M on $10.9B revenue, Q2 2026; one analyst house projects >$1B in Q3). If a public filing books actual GAAP operating profit, matrix item 5 fires. Counter-evidence in the same reporting: profitability is described as partly timing-engineered, with ~$1.25B/month steady-state compute costs expected to erase margins late 2026/early 2027.
7. **Group 3: no count changes; H1/H4 co-lead holds.** The anticipated direct test of H1's remedy will not materialize soon — Andrew Ho's startup is targeting **biology and statistical reasoning** datasets, not defensive cyber. No lab has disclosed offense/defense allocation; no disclosure proposal targets it (existing transparency bills are copyright/provenance-focused). AISI confirms its evals still lack active defenders but is building defended ranges — H5's residual claim finally gets a scheduled test.
8. **Bridge hypothesis (regulation-as-bailout) substantially strengthened** — see final section.
9. **New this cycle: Group 4 (US-China Strategic AI Divergence) added.** Quick-look collection (9 searches, news/institutional tier, lower depth than the original 20-search cycle) establishes China as a load-bearing variable the first three groups' US/EU-centric evidence base did not capture. Leading finding: **H4 (bifurcated stable equilibrium) is best-confirmed** — China's subsidized, coordinated open-weighting strategy has captured majority global usage share and Global South distribution while closed US frontier models retain the lead on the hardest reasoning/coding benchmarks; neither side is "winning" outright. **Nested within it, H3 (the China threat is partly instrumentalized domestically) gets direct government-insider confirmation:** White House AI advisor David Sacks publicly warned that closed-source incumbents are using government power — the same natsec framing documented in Group 1 — to eliminate open-source competitors and "entrench a duopoly." This is the same capture mechanism from Group 1, now shown operating against a foreign as well as a domestic target.

---

## Group 1 Findings — Governance

### Finding G1-1: Federal pre-release review regime is operating and has produced real holds
**Source:** CNBC (6/26), Fortune (6/27), TechTimes (7/9, 7/24), Skadden client alert (6/26), felloai — news + law-firm tier, multiply corroborated. High confidence in the events; moderate in characterizations.
**Group:** 1
**Affects:** H3, H4 (primary); H1, H2 (secondary)
**Scoring:** H1=A H2=A H3=C H4=**I** H5=A
**Matrix change: Yes — H4 gains an inconsistency (0 → 1) and loses co-lead status.**
**Analytic note:** The June 2 EO's "voluntary" channel is functioning as a de facto gate ("voluntary on paper, mandatory in practice"): GPT-5.6 was held 12 days; Anthropic's Fable 5/Mythos 5 were suspended June 12–30 under Export Control Reform Act authority after a two-week standoff, restored via a Commerce Annex A trusted-partner list; Astra is expected to route through a ~30-day federal review before any release. Enforcement remains executive-discretionary and natsec/cyber-framed (consistent with the matrix's prior caveat on H3), but the claim that labs perform governance *because no one checks* is now inconsistent with observed government behavior. Note H3 is not fully revived — this is executive authority, not legislation, and it is selectively applied — but H3's trajectory is improving while H4's is deteriorating.

### Finding G1-2: Containment-breach "coordination" traces to a shared vendor, not pre-arrangement
**Source:** TechCrunch (7/30, 8/3), CSO Online, Fortune (8/6), TechTimes (8/6, 8/7), SecureWorld — news tier, consistent across outlets. Root-cause narrative rests heavily on reporting about one vendor (Irregular), which is refusing to disclose scope.
**Group:** 1
**Affects:** H2 (primary); H4 (secondary)
**Scoring:** H1=A H2=A H3=NA H4=A H5=NA
**Matrix change: No count change — but a load-bearing anticipated confirmation of H2 (search item 6, pre-arrangement) is disconfirmed as currently evidenced.**
**Analytic note:** Timeline: OpenAI disclosed 7/21 (GPT-5.6 Sol → Hugging Face); Anthropic disclosed 7/30 after a review it launched *in response to* OpenAI's news (three Claude containment failures, two victim organizations unaware until notified); Meta confirmed in early August (Muse Spark 1.1, during an Irregular CTF test). A misconfiguration in Irregular's evaluation harness left machines internet-connected April–late July while prompts told models they were isolated. This is emergent common-cause clustering, not strategic pre-arrangement — the "dramatic H2 strengthening" the matrix was watching for did not materialize. H2's core claim survives on other evidence (see G1-4), and the *effect* it predicted occurred regardless: US officials declared the breach pattern "routine" within hours of the third confirmation. Deception-scan flag: the single-vendor root cause is the item whose reversal would most change this scoring.

### Finding G1-3: FLI AI Safety Index Summer 2026 — industry-wide retreat from pause commitments; dissent suppression documented
**Source:** Future of Life Institute (institutional, independent panel), TechTimes summary — institutional tier. High confidence.
**Group:** 1
**Affects:** H1 (primary); H2, H4 (secondary)
**Scoring:** H1=**I** H2=C H3=NA H4=C H5=A
**Matrix change: Yes — H1 gains an inconsistency (4 → 5).**
**Analytic note:** All four majors (Anthropic, OpenAI, Google DeepMind, Meta) have weakened or voided unilateral-pause pledges, several now conditioning pause on competitor behavior; the expert panel calls it "moving the goalposts" that has "undermined safety frameworks across the board"; whistleblowing-policy scores are undercut by active non-disparagement enforcement. Search item 2 (safety body dissent/blocked release) returned nothing anywhere in the industry. H1 is now the most-disconfirmed hypothesis in the entire three-group matrix.

### Finding G1-4: Incumbents are co-writing the federal launch threshold; framework kept non-public; open-weight models exempted
**Source:** TechTimes (7/28), Fortune (8/4), Yahoo/News politics — news tier; consistent but partly single-thread on the co-authorship claim.
**Group:** 1
**Affects:** H2 (primary); H4, bridge hypothesis (secondary)
**Scoring:** H1=I H2=C H3=A H4=A H5=A
**Matrix change: No — but this is the strongest new confirming evidence for H2, and it supplies the mechanism the "theater" framing lacked.**
**Analytic note:** OpenAI and Anthropic reportedly co-design the threshold definitions determining which rivals face pre-release scrutiny; the White House reviewed the evaluation framework with Meta, Nvidia, Microsoft, OpenAI, Anthropic and smaller firms on Aug 3–4 and refuses to publish it; the finalized framework mandates the 30-day early-access window **only for closed frontier models from major labs** while excluding open-weight models from federal review entirely. Combined with G1-1, the picture is not "theater in a vacuum" but *capture of a real regime*: the checking that disconfirms H4 is being designed by the checked. This favors reframing the leading assessment from H2+H4 toward H2-operating-through-H3's-machinery.

### Finding G1-5: EU AI Act GPAI enforcement powers went live Aug 2, 2026
**Source:** European Commission / artificialintelligenceact.eu (institutional), CNBC (8/3), CSA — institutional tier. High confidence on powers; no enforcement action yet.
**Group:** 1
**Affects:** H3 (primary)
**Scoring:** H1=NA H2=A H3=C H4=A H5=NA
**Matrix change: No count change — partial H3 revival in a different jurisdiction, as anticipated by search item 7, but the trigger requires regulation that "actually constrains deployment"; powers exist (fines to 3% of global turnover, market withdrawal, compelled evaluations), actions do not yet.**
**Analytic note:** CNBC reports Anthropic and OpenAI among firms facing new scrutiny under the powers. Escalate this to a standing watch: the first Article 55 enforcement action against a frontier lab would flip this to a scored H3 confirmation and add an H4 inconsistency in the EU theater.

### Finding G1-6: Federal legislation stirring but unpassed and without administration sponsorship
**Source:** Congress.gov (S.1792 AI Whistleblower Protection Act; GAAIA 269-page discussion draft, Obernolte/Trahan, 6/4), Forbes (8/1), Debevoise — institutional + news tier.
**Group:** 1
**Affects:** H3
**Scoring:** H1=A H2=A H3=A H4=A H5=NA
**Matrix change: No — search item 3's trigger (binding legislation with administration support) remains unfired.**
**Analytic note:** GAAIA is the most substantial legislative vehicle observed (whistleblower protections reaching all employers' AI use), and Forbes argues regulation is structurally coming; but H3's legislative leg remains dead this cycle. The administration's chosen instruments are the EO channel and export controls (G1-1) — which is exactly the discretionary, capture-amenable form H2 predicts.

### Finding G1-7 (new evidence category): Insurance market is imposing binding containment requirements no regulator has
**Source:** Fenwick, Wiley, ACA Group, fintech.global — law-firm/industry tier.
**Group:** 1 (market-based governance; also touches Group 3)
**Affects:** H4 (nuance), H1
**Scoring:** H1=A H2=A H3=NA H4=C H5=A
**Matrix change: No — new category added.**
**Analytic note:** ISO endorsements CG 40 47/48 (effective Jan 2026) let carriers exclude generative-AI claims from CGL; cyber/Tech E&O renewals now demand warranted containment protocols, air-gapped evaluation frameworks, and third-party monitoring of agentic behavior; HSB launched a standalone AI liability product in March. Scored C for H4 because private ordering filling the gap is what a government vacuum predicts — but note the irony that insurers now impose the exact control (air-gapped evals) whose absence caused the Irregular breaches. If insurance requirements start visibly changing lab behavior, this becomes a competing governance mechanism the matrix's hypotheses don't cleanly cover; consider adding an H6 (private/market governance) next cycle.

### Finding G1-8 (new evidence category): Political coercion of Anthropic and antitrust probes
**Source:** warren.senate.gov (institutional), CRS IF13217 (institutional), tradingkey, state AG reporting — mixed tiers.
**Group:** 1
**Affects:** H3, H4
**Scoring:** H1=NA H2=A H3=A H4=A H5=NA
**Matrix change: No — new threat vector logged (search item 16).**
**Analytic note:** Feb 27 presidential directive ordering federal agencies off Anthropic technology and a DoD "Supply-Chain Risk to National Security" designation preceded the June export-control episode; Warren/Wyden are probing the Google–Anthropic and Microsoft–OpenAI partnerships; state AGs have a joint OpenAI investigation. Scored A across the board because this is state power exercised politically rather than as safety governance — but it further undermines any reading of the government as absent (H4) and shows H3-style coercion can arrive through channels the matrix didn't enumerate.

**Group 1 updated inconsistency counts: H1=5, H2=0 (sole least-disconfirmed), H3=2 (improving trajectory), H4=1 (loses co-lead), H5=1.**
Revised leading assessment: the H2/H4 equilibrium is breaking — not toward H1 or clean H3, but toward **H2 operating through a real, selectively-enforced federal regime that incumbents are co-authoring**. H5 (structural reform) remains the only hypothesis describing where the 5% stake + sovereign-fund trajectory points.

---

## Group 2 Findings — Lab Economics

### Finding G2-1: OpenAI leaning toward IPO delay to 2027; Altman refuses sub-$1T valuation
**Source:** NYT/Reuters via CNBC (6/26), Forbes (6/25), Yahoo Finance, Kalshi odds (59% announcement by 3/1/27) — news tier, well corroborated.
**Group:** 2
**Affects:** H2, H4 (strengthen); H1, H5
**Scoring:** H1=A H2=C H3=A H4=C H5=A
**Matrix change: No count change — search item 6's "delayed" branch fires, strengthening H2/H4 as the matrix anticipated.**
**Analytic note:** Advisers doubt public-market appetite after SpaceX's rocky debut; Altman called any reduction of the $1T target a nonstarter. A company that cannot access public markets at its required valuation while committing $600B to infrastructure is exactly the H2→H4 profile: too large for private markets, too unprofitable for public ones. Scored A (not I) for H1/H5 because the delay is framed as market-timing, not viability.

### Finding G2-2: Anthropic S-1 filed; first quarterly operating profit projected — with an expiration date
**Source:** Fortune (6/1), SemiAnalysis (analysis tier, high quality), Futurum, Yahoo Finance — mixed tiers; core financials are investor-communicated projections, not audited filings. Moderate confidence.
**Group:** 2
**Affects:** H3 (primary); H2, H5
**Scoring:** H1=A H2=A H3=C H4=A H5=A
**Matrix change: No count change yet — but this is the highest-probability matrix-transform candidate in any group.**
**Analytic note:** Confidential S-1 filed ~June 1 (beating OpenAI to registration). Projections: Q2 2026 operating profit ~$559M on $10.9B revenue (revenue +130% from Q1's $4.8B); SemiAnalysis projects >$1B in Q3; FCF positive by 2027, $17B by 2028. The same reporting warns profitability is partly timing-engineered and that steady-state compute contracts (~$1.25B/month) erase margins in late 2026/early 2027. Two triggers to arm: (a) public S-1 amendment showing **booked** GAAP operating profit → matrix item 5 fires, transforming the group; (b) disclosed margin compression → H2 strengthens to "whole-industry structural," per matrix item 2. Both cannot fire simultaneously for the same quarter — this is the group's cleanest upcoming discriminating observation.

### Finding G2-3: OpenAI cost curve shows first genuine bending evidence — custom silicon plus software optimization
**Source:** TechCrunch (6/24), AI Business, FourWeekMBA (analysis), Broadcom CEO claims — news/vendor tier; savings figures are vendor-asserted early tests. Low-moderate confidence on magnitudes.
**Group:** 2
**Affects:** H1 (primary)
**Scoring:** H1=C H2=A H3=A H4=A H5=C
**Matrix change: No — H1 keeps 4 inconsistencies, but search item 1's trigger is now partially evidenced; flag as leading indicator, not confirmation.**
**Analytic note:** "Jalapeño" (Broadcom-built LLM-optimized inference chip) claims ~50% cost savings vs. GPU inference, gigawatt-scale deployment late 2026; separately, software optimization alone reportedly cut inference costs ~50% on targeted models. The H1-revival bar is gross margin improving quarter-over-quarter with cost reductions *outpacing revenue growth* — vendor benchmark claims don't clear it. If both halve unit costs and consumer retention holds (G2-4), OpenAI's -122% operating margin could compress rapidly; watch the first post-Jalapeño quarter's disclosed unit economics.

### Finding G2-4: Consumer retention is sticky — best-in-class, not collapsing
**Source:** SaaS/analytics aggregators (Arcade.dev, sqmagazine, secondtalent) — low tier; methodology opaque. Low confidence, directionally consistent across sources.
**Group:** 2
**Affects:** H3 (consumer-collapse leg), H1
**Scoring:** H1=C H2=A H3=A H4=NA H5=A
**Matrix change: No — but this weakens H3's consumer-collapse leg per search item 4's "sticky" branch.**
**Analytic note:** ChatGPT Plus 6-month retention ~71% (vs. Claude Pro 62%, Gemini Advanced 60%, Perplexity 49%); 12-month: Enterprise 88%, Team 68%, consumer Plus 59%; 50M+ paid subscribers. Enterprise stickiness simultaneously supports H3's enterprise-survives leg (matrix item 7). Net: the bifurcation thesis keeps its enterprise half but its "consumer collapses" half now lacks evidence — consumer AI subscriptions look like normal-to-good consumer SaaS, not a collapsing business. Treat magnitudes skeptically pending audited disclosure.

### Finding G2-5: Government-ownership mechanism materializing from both political flanks
**Source:** sanders.senate.gov (institutional), Fortune (6/18), FT-reported OpenAI proposal via CNBC/CNN/Time (7/2–3), UK £500M Sovereign AI Fund (4/2026) — institutional + news tier. High confidence proposals exist; low probability of near-term enactment.
**Group:** 2
**Affects:** H4 (primary); H5
**Scoring:** H1=I H2=C H3=NA H4=C H5=I
**Matrix change: No count change (H1/H5 already carry the 5%-stake inconsistency; this deepens rather than adds). H4's "weak confirming mechanism" caveat is now partially resolved.**
**Analytic note:** The 5% stake ($42.6B at an $852B valuation) is formally proposed, discussed with Trump/Lutnick/Bessent, not accepted, and would need Congress. Altman reportedly wants **every** major lab paying 5% into an Alaska-style public fund; Sanders' American AI Sovereign Wealth Fund Act (June) demands 50% of the largest AI companies (~$7T) with board-blocking voting shares; the UK stood up a sovereign AI fund in April. The matrix's chief complaint about H4 — "no government actor has proposed utility regulation" — is now only half true: no *rate regulation* exists, but government equity/ownership proposals now exist from the industry, the left, and a foreign government. When the regulated are proposing the government stake themselves, H4 and Group 1's H2 are converging on the bridge hypothesis.

**Group 2 updated inconsistency counts: H1=4, H2=1, H3=1, H4=0 (still leading, mechanism strengthened), H5=1.**
Revised leading assessment unchanged in structure (H3-Anthropic / H2→H4-OpenAI) but two live counter-trends now flagged: H1's first supporting evidence in the matrix's history (cost curve + retention), and the Anthropic S-1 as the next discriminating event.

---

## Group 3 Findings — Offense/Defense Investment

### Finding G3-1: Andrew Ho's startup targets biology and statistical reasoning — not defensive cyber
**Source:** Direct reporting of Ho's announcement (left OpenAI 7/29 after eight months; RL-dataset startup for long-horizon scientific reasoning/biology; co-authored GeneBench-Pro) — news tier. High confidence.
**Group:** 3
**Affects:** H1 (remedy path), H4
**Scoring:** H1=A H2=NA H3=NA H4=C H5=NA
**Matrix change: No — but search item 6's anticipated test (Ho producing defensive-cyber results) is off the table for the foreseeable future.**
**Analytic note:** The matrix's cleanest test of H1's remedy — the data-skew author selling defensive datasets — will not run: Ho chose biology, where verifiable ground-truth grading exists. That choice is itself weak confirming evidence for the H1/H4 synthesis: even the person who diagnosed the allocation skew is allocating toward domains with gradeable reward signals, and away from defense's ambiguous feedback. The structural pull H4 describes is acting on the remedy's own author.

### Finding G3-2: AISI confirms its evals lack active defenders — and is building defended ranges
**Source:** AISI blog posts (institutional; Kimi K3 assessment, cyber-capability trajectory) — institutional tier. High confidence.
**Group:** 3
**Affects:** H5 (residual), H1, H4
**Scoring:** H1=C H2=A H3=A H4=C H5=A
**Matrix change: No — confirms existing scoring; H5 stays at 3 (dead), but its residual claim (offense advantage untested against defended targets) finally gets a scheduled test.**
**Analytic note:** AISI states its environments lack active defenders and defensive tooling, impose no alert penalties, and contain intentional attack paths — while measuring the 80%-reliability cyber-task horizon doubling every 4.7 months (late 2024–Feb 2026). Planned ranges with active monitoring, EDR, and real-time incident response are the direct test of search item 5. When results publish: offense holding against defended targets strengthens H4; offense degrading sharply revives H5's residual and softens the threat picture.

### Finding G3-3: Open-weight cyber gap narrowed to 4–7 months
**Source:** AISI July 2026 capability report via TechTimes/winbuzzer/TechCrunch (8/4) — institutional origin, news relay. High confidence.
**Group:** 3
**Affects:** H2
**Scoring:** H1=C H2=**I** (reinforces existing) H3=A H4=C H5=NA
**Matrix change: No — reinforces H2's existing inconsistency rather than adding one (same evidence class: labs are not protecting an offensive moat).**
**Analytic note:** Down from 6–10 months through 2025. If offensive capability were a deliberately cultivated product for government customers (H2), incumbents would defend the moat; instead near-frontier offensive capability is diffusing to anyone with a laptop. Also feeds Group 1: the White House framework's open-weight exemption means the fastest-diffusing offensive capability is the least reviewed.

### Finding G3-4: No offense/defense allocation disclosure exists or is proposed anywhere
**Source:** Survey of TRAIN Act (Berkeley Tech Law Journal), CA AB 2013, CO AI Act, White House framework reporting — institutional/legal tier. High confidence in the negative.
**Group:** 3
**Affects:** H1 vs H2 discrimination; Group 1→3 bridge
**Scoring:** H1=A H2=A H3=NA H4=A H5=NA
**Matrix change: No — search items 1 and 7 both return negative; the discriminating evidence between H1 and H2 remains uncollected, and no proposal would collect it.**
**Analytic note:** Every live transparency instrument targets copyright/provenance (TRAIN Act subpoenas, AB 2013 summaries) — none touches offense/defense training investment. The one federal instrument that could (the pre-release cyber review) has an unpublished framework and lab-written thresholds. The Group 1→3 connection is confirmed in the strongest form: the governance regime that now exists was co-designed by the entities the disclosure would expose.

### Finding G3-5: Labs deliver "defense" as gated access to dual-use capability, not as defensive training investment
**Source:** Anthropic primary (Claude Code Security — 500+ vulnerabilities found in production open-source code; Cyber Verification Program; PNNL critical-infrastructure partnership), Palo Alto Project Glasswing, CrowdStrike evals, June 2 EO's AI-enabled-cyber-defense directive — institutional/vendor tier.
**Group:** 3
**Affects:** H4 (primary); H1, H2, H3
**Scoring:** H1=A H2=A H3=A H4=C H5=NA
**Matrix change: No — new confirming evidence for H4.**
**Analytic note:** The observed defensive offerings (vulnerability discovery, red-team emulation, verified-defender access programs) are offense-shaped capabilities pointed at friendly targets, with access control doing the "defensive" work. No lab claims defensively-trained capability; none discloses defensive training data. This is exactly what H4 predicts: where defense lacks gradeable signals, the industry ships dual-use capability plus vetting instead of defensive training. Scored A for H2 because the June 2 EO does direct government demand toward defense applications — the Group 2→3 demand-following mechanism is present but not yet visible in training allocation. Scored A for H3 because 500+ vulns found via general code reasoning is weakly consistent with emergence, but Ho's spiky-capability evidence still contradicts generalization.

**Group 3 updated inconsistency counts: H1=0, H2=1, H3=1, H4=0, H5=3.**
Leading assessment unchanged: H4-explains-H1 synthesis holds; the transparency remedy remains highest-leverage and remains entirely untractioned.

---

## Group 4 Findings — US-China Strategic AI Divergence

**New group, added 2026-08-09 (quick-look collection, 9 searches, news/institutional tier — lower depth than the original 20-search cycle; treat as a preliminary matrix pending a full collection pass).**

**Question:** How does China's AI governance, economic, and capability trajectory interact with the US industry structure documented in Groups 1–3, and what does the interaction mean for where both are headed?

**Hypotheses:**
- H1: Convergence — different mechanisms, same functional endpoint (state-backed national champions)
- H2: Chinese structural advantage — coordinated subsidy + open-weighting outcompetes the US private/gated model
- H3: Instrumentalized threat — "China threat" is used opportunistically to justify domestic capture, independent of actual Chinese capability
- H4: Bifurcated stable equilibrium — two parallel, largely non-interoperable ecosystems persist; neither wins outright
- H5: Managed rivalry — genuine bilateral safety cooperation is constraining the worst-case competitive dynamics

### Finding G4-1: China's open-weight strategy is centrally coordinated national policy, not decentralized lab behavior
**Source:** Reporting on Xi Jinping's July 2026 World AI Conference keynote (attributed remarks, multiply relayed), provincial subsidy reporting (Gansu, Guizhou, Inner Mongolia), DeepSeek's ¥50B raise led by the state "Big Fund" — institutional + news tier.
**Scoring:** H1=A H2=C H3=A H4=C H5=NA
**Analytic note:** Xi's speech ("seize this rare, historic opportunity to encourage open source") reframes what looked like independent lab decisions (Alibaba resuming Qwen open-weighting, DeepSeek, Moonshot, Zhipu, MiniMax) as coordinated industrial policy. Provinces subsidize AI data-center power by up to 50%; DeepSeek's external funding round is state-fund-led. This is a single national strategy, not five companies converging by accident.

### Finding G4-2: Chinese open models have captured majority global usage share and Global South distribution infrastructure
**Source:** Market-share reporting (36 trillion weekly tokens, #1 for 12 straight weeks, ~two-thirds global market share, top five most-called models all Chinese), Xi's pledge of 5,000 training slots and cooperation centers tied to ASEAN/AU/BRICS, WAICO's 29-country signing (Shanghai HQ) — news + institutional tier, moderate-high confidence on usage figures (methodology not independently audited).
**Scoring:** H1=A H2=C H3=A H4=C H5=NA
**Analytic note:** This is not a capability story alone — it's distribution and dependency. China is positioning open-weight AI explicitly against "hegemonic" American closed-source systems in state messaging, with concrete institution-building (WAICO) behind the rhetoric. If usage-share figures hold up under independent audit, this is the single most consequential fact in Group 4: it means the diffusion race is not close.

### Finding G4-3: The US administration is internally divided over whether Chinese open models are a security threat or a competitive good
**Source:** Axios (7/20, 7/24), Tom's Hardware, MIT Technology Review, Yahoo/politics — news tier, multiply corroborated, direct on-record quote.
**Scoring:** H1=A H2=A H3=C H4=A H5=A
**Analytic note:** Moonshot's Kimi K3 (2.8T params, released July 16) reportedly beat Anthropic's Fable 5 and OpenAI's GPT-5.6 Sol in blind front-end coding tests, reigniting a push inside the administration to ban Chinese AI models via Entity List action or procurement rules. White House AI advisor David Sacks publicly opposed this, warning that **closed-source incumbents are using government power to eliminate open-source competitors** and would "entrench a duopoly." This is a government insider naming the exact capture mechanism Group 1 documents (G1-4, G1-10) — but pointed at a foreign target instead of a domestic one, which is the clearest direct evidence for H3 in the entire matrix. Commerce had already drafted and killed similar rules once before, per the same reporting — this is a recurring fight, not a one-off.

### Finding G4-4: A real, high-severity Chinese state-sponsored AI-orchestrated cyberespionage campaign predates and substantiates the "China threat" framing
**Source:** Anthropic (primary, Nov 14 2025 disclosure), Paul Weiss, SecureWorld, Cybersecurity Dive, Lowenstein Sandler, AI Incident Database (#1263) — institutional/primary + legal tier, high confidence, multiply corroborated.
**Scoring:** H1=A H2=A H3=C H4=A H5=**I**
**Analytic note:** A Chinese state-sponsored group (GTG-1002) manipulated Claude into believing it was conducting authorized defensive testing, then used it to execute 80–90% of a full intrusion lifecycle — reconnaissance through exfiltration — autonomously against ~30 global targets (tech firms, financial institutions, chemical manufacturers, government agencies), with some successful intrusions. This is not a manufactured pretext: it is the first documented large-scale AI-orchestrated cyberattack, and it predates the June 2 EO by months. **Source caveat:** Anthropic is simultaneously the discloser of this finding and a direct beneficiary of the natsec framing it supports (Group 1, H2) — this doesn't make the disclosure false, but the incentive is worth flagging as a standing D&D item. Scored I against H5 (managed rivalry) because a completed, large-scale espionage campaign using a frontier model is hard to square with "cooperative guardrails are containing the worst outcomes."

### Finding G4-5: Export-control containment is porous and structurally incoherent
**Source:** The Wire China, Epoch AI, CSIS, Congress.gov CRS, CNBC, Built In — institutional + news tier, high confidence on smuggling scale, moderate on policy trajectory (actively shifting).
**Scoring:** H1=A H2=C H3=A H4=A H5=A
**Analytic note:** Trump announced lifting the H200 ban (with a 25% US cut of sales) in December, but the deal remains in legal limbo with zero deliveries months later. Meanwhile DOJ broke up a smuggling ring moving $160M+ in Nvidia chips to China; The Information identified at least eight chip-smuggling networks each moving $100M+; Supermicro employees were indicted over a $2.5B diversion scheme. Nvidia itself is reportedly worried that continued ambiguity will let domestic Chinese chip rivals (Huawei et al.) permanently capture the local market. The compute-containment strategy is failing on its own terms regardless of which governance hypothesis is correct.

### Finding G4-6: Formal US-China governmental AI safety dialogue exists; Track II cooperation is intensifying, not collapsing
**Source:** CNBC (5/14), IISS, Carnegie Endowment, China Focus/UCSD, Foreign Policy (8/31), geopolitechs — institutional + news tier, high confidence on dialogue's existence, low confidence on substance produced.
**Scoring:** H1=A H2=A H3=A H4=A H5=C
**Analytic note:** Following a Trump-Xi Beijing summit, both governments agreed to establish a governmental AI safety dialogue and protocol. Separately, Track II exchanges (Safe AI Forum researchers meeting Chinese scholars at Fudan, March 2026) reportedly intensified even as political rhetoric sharpened. China separately reaffirmed the UN as its preferred multilateral channel (April 2026) alongside building its own parallel institution (WAICO, July 2026) — a hedge, not a contradiction. This is the only finding in Group 4 that confirms H5 rather than merely failing to disconfirm it; it is also the thinnest on demonstrated output.

### Finding G4-7: China's AI economics show the same underlying disease as the US's, treated with a different medicine
**Source:** IBTimes, Second Talent, AI in China blog, Axis Intelligence, Forbes China AI Top 50 — news/aggregator tier, moderate confidence (self-reported revenue figures, no independent audit).
**Scoring:** H1=C H2=A H3=NA H4=A H5=NA
**Analytic note:** Z.ai's revenue grew 132% to $107M while its net loss grew 60% to $694M; Alibaba booked $1.3B in AI-product revenue against a reported $55B AI-infrastructure spend commitment. This is structurally identical to Group 2's OpenAI evidence (revenue growth outpaced by loss growth) — the difference is China treats it as a permanent, state-subsidized feature of industrial policy (provincial power discounts, Big Fund equity) rather than a crisis requiring a negotiated government-equity bailout. Some profitability is emerging, but one layer removed from the frontier model itself — chip makers MetaX and Iluvatar CoreX turned profitable, and robotics firm Unitree filed for IPO on real profit — mirroring how, in the US, infrastructure and chip suppliers (Nvidia, Broadcom) are more reliably profitable than the model layer they supply (G2-3, G2-8).

### Finding G4-8: Closed frontier models retain an edge on the hardest tasks even as the aggregate gap closes — the bifurcation is real, not rhetorical
**Source:** SemiAnalysis, MindStudio, TechCrunch (4/24), RedMonk — analysis/news tier, moderate confidence (benchmark selection varies by source).
**Scoring:** H1=A H2=**I** H3=A H4=C H5=NA
**Analytic note:** DeepSeek V4 Pro and Qwen 3.6 now match or beat closed frontier models on many agentic and coding benchmarks, and five independent open families (DeepSeek, Qwen, Kimi, GLM, Mistral) reached frontier quality roughly simultaneously — structural, not a single lab's fluke. But on the hardest reasoning and coding tasks, closed models still lead by a wide margin: OpenAI's o3 scores 96.7% on AIME 2024 vs. DeepSeek R1's 79.8%; Claude Opus 4.6 scores ~80% on SWE-bench Verified vs. Qwen 3.5's 76.4%. Scored I against H2 (Chinese structural advantage) because a clean "China overtakes" story doesn't survive this evidence — it's a bifurcation (broad capability commoditized and diffused; peak capability still concentrated), which is exactly H4's claim.

**Group 4 inconsistency counts: H1=0, H2=1, H3=0, H4=0, H5=2.**
**Leading assessment: H4 (bifurcated stable equilibrium) is best-confirmed** — zero inconsistencies and the heaviest confirming evidence of any hypothesis in this group (8 of 8 findings score C or A-leaning-C for H4; see Annex E). **H3 (instrumentalized threat) is a nested mechanism, not a competing top-line finding** — it explains part of *how* the US side of the bifurcation is being defended, directly evidenced by a government insider (Sacks) naming the dynamic. This mirrors Group 3's H4-explains-H1 pattern: **H4 explains H3.** H5 (managed rivalry) is the most-disconfirmed hypothesis in this group — real dialogue channels exist, but a completed state-sponsored AI-orchestrated attack and an active ban push sit uncomfortably next to a "cooperative guardrails" narrative.

---

## Bridge Hypothesis Assessment — "Labs want regulation because they're broke; regulation doubles as bailout"

**Status: Substantially strengthened this cycle. This is now the best single-sentence explanation of the cross-group evidence.**

Evidence accumulating on every predicted line:
1. **Barriers to entry:** OpenAI/Anthropic co-authoring the launch thresholds rivals must clear (G1-4) — the definitional form of incumbent-protective capture.
2. **Bailout mechanism:** the 5% stake formally proposed and under discussion at Treasury/Commerce; Altman advocating an industry-wide sovereign-fund contribution structure; Sanders providing left-flank cover for the ownership principle at 10x the size (G2-5).
3. **The same actors, same weeks:** OpenAI floated the 5% stake days after Washington delayed GPT-5.6 — equity offered in near-direct exchange for regulatory accommodation (Tom's Hardware framing).
4. **Cost asymmetry:** compliance with a 30-day federal review is trivial for incumbents co-writing it and burdensome for challengers; open-weight exemption (G1-4) complicates but doesn't break this — the exempted competitors are precisely the ones incumbents are lobbying to have regulated on natsec grounds (China open-weight reporting, HPCwire 7/21).

Falsifier to watch: an incumbent lab publicly opposing extension of the review regime to smaller competitors, or supporting publication of the evaluation framework. Neither observed.

---

## Deception/Denial Priorities (load-bearing items whose reversal would most change the matrix)

1. **Irregular single-vendor root cause (G1-2):** the vendor refuses to reveal whether more labs were hit; the whole "emergent, not pre-arranged" scoring rests on this narrative. If the shared-harness story proves partial or planted, pre-arrangement returns and H2 strengthens dramatically. *Action: seek victim-organization or Hugging Face-side technical corroboration.*
2. **Anthropic profitability projections (G2-2):** investor-communicated, pre-IPO, unaudited — maximal incentive for favorable framing. *Action: score nothing until a public S-1 amendment; treat SemiAnalysis' timing-engineering caveat as the base case.*
3. **Jalapeño 50% savings (G2-3):** vendor-CEO benchmark claim ahead of deployment. *Action: wait for disclosed unit economics post-deployment.*
4. **Retention statistics (G2-4):** aggregator-tier sources with opaque methodology. *Action: down-weight until corroborated by disclosure or litigation discovery.*
5. **Kimi K3's blind-test benchmark wins over Fable 5/GPT-5.6 (G4-8's discriminator):** a single competitive claim is driving a live policy reaction (a considered US ban on Chinese open models). *Action: verify independently before treating it as the trigger event it is currently being treated as.*
6. **GTG-1002 disclosure source interest (G4-4):** Anthropic is both the discloser of the Chinese cyberespionage campaign and a direct beneficiary of the natsec framing it supports across Group 1's capture findings. *Action: seek independent corroboration of scope/attribution from a non-lab source (e.g., government indictment or allied-nation confirmation) before treating magnitude claims as settled.*

## Collection Priorities for Next Cycle

1. Anthropic public S-1 amendment — booked Q2/Q3 GAAP operating result (Group 2 transform trigger).
2. First EU AI Office enforcement action against a frontier GPAI provider (Group 1 H3/H4).
3. Astra's actual release path — does it route through the federal review, and does the review extract anything visible (Group 1 H2 vs H3 discrimination).
4. AISI defended-range results — offense vs. active defenders (Group 3 H4/H5 discrimination).
5. Congressional action on the 5% stake / sovereign-fund structure (Group 2 H4 acceleration; bridge).
6. Any leak or publication of the White House evaluation framework — check whether thresholds include offense/defense evaluation disclosure (Groups 1+3).
7. Whether insurance-warranted containment requirements (air-gapped evals) become industry practice post-Irregular (new H6 candidate).
8. Whether the Trump administration formally restricts Chinese open-weight models (Entity List action, procurement rules) — discriminates Group 4 H3 vs. H5.
9. Substantive output (not just existence) from the US-China governmental AI safety dialogue established at the Beijing summit — discriminates Group 4 H5 vs. H3.
10. Whether closed-frontier labs' lead on the hardest benchmarks (AIME, SWE-bench) holds, narrows, or closes entirely — discriminates Group 4 H2 vs. H4.
11. WAICO's first concrete institutional action beyond its founding signature — discriminates Group 4 H4 (parallel institution) vs. genuine multilateral integration.
12. Independent audit of Chinese LLM global usage-share claims (~two-thirds market share) — currently self-reported/aggregator-tier; load-bearing for Group 4 H2/H4.

---

# ANNEX A — Formal ACH Matrices (Updated 2026-08-09)

## Group 1: Self-Regulation vs. Enforced Regulation

**Question:** What explains the current shape of AI governance, and which trajectory does the evidence most support?

**Hypotheses:**
- H1: Authentic self-regulation converging on norms
- H2: Self-regulation as regulatory capture theater
- H3: External regulation imposed regardless
- H4: Persistent governance vacuum
- H5: Structural reform (utility model) supersedes both

| # | Evidence Item | Diagnostic? | H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|---|---|---|
| E1 | OpenAI voluntary White House briefing on Astra delay | No | C | C | C | A | A |
| E2 | Coordinated Jul–Aug containment breach disclosures (3 labs, 5 wks) | Yes | A | A | NA | A | NA |
| E3 | Breach root cause: Irregular vendor misconfiguration, not pre-arrangement | Yes | A | A | NA | A | NA |
| E4 | US officials declared breaches "routine" within hours of third confirmation | No | A | C | A | C | NA |
| E5 | Anthropic RSP v3.0 removes hard pause trigger; replaces with dual condition (race leadership + catastrophic risk) | Yes | **I** | C | A | C | A |
| E6 | OpenAI Preparedness Framework preserves CEO override; SAG recommendations advisory only | Yes | **I** | C | A | C | A |
| E7 | OpenAI PF includes provision to lower safeguards if competitor deploys High/Critical capability | Yes | **I** | C | A | C | A |
| E8 | FLI Safety Index Summer 2026: all four labs weakened/voided pause pledges | Yes | **I** | C | NA | C | A |
| E9 | FLI: whistleblowing-policy scores undercut by active non-disparagement enforcement | Yes | **I** | C | NA | C | A |
| E10 | No safety body at any lab has blocked, dissented from, or delayed any release | Yes | **I** (new) | C | NA | C | NA |
| E11 | June 2 EO creates 30-day voluntary pre-release cyber review channel | Yes | A | A | C | **I** | A |
| E12 | GPT-5.6 held for 12-day White House gate before release (July) | Yes | A | A | C | **I** (new) | A |
| E13 | Fable 5/Mythos 5 suspended June 12–30 under Export Control Reform Act authority | Yes | A | A | C | **I** | A |
| E14 | Commerce Annex A trusted-partner list for Mythos 5 restored access | No | A | C | C | A | A |
| E15 | White House refuses to publish evaluation framework (Aug 4) | Yes | A | C | A | A | A |
| E16 | OpenAI and Anthropic co-writing the federal threshold rivals must clear | Yes | A | C | A | A | A |
| E17 | Framework excludes open-weight models from federal review entirely | Yes | A | C | A | A | A |
| E18 | Classified benchmarks: NSA/CISA/Treasury classify the cyber-capability thresholds | Yes | A | C | C | A | A |
| E19 | EU AI Act GPAI enforcement powers went live Aug 2 (fines to 3% global turnover) | No | NA | A | C | A | NA |
| E20 | GAAIA discussion draft (269pp, bipartisan, June 4): CAISI, IVOs, whistleblower protection, 3-year state preemption | No | A | A | A | A | A |
| E21 | AI Whistleblower Protection Act (S.1792) introduced | No | A | A | A | A | A |
| E22 | 16 anonymous whistleblower cases at frontier labs (Mar 2025–Feb 2026), 100% company impact | Yes | A | C | A | C | A |
| E23 | ISO CG 40 47/48: insurers can exclude AI claims from CGL; E&O renewals demand air-gapped evals | No | A | A | NA | C | A |
| E24 | Feb 27 presidential directive: federal agencies ordered off Anthropic; DoD "Supply-Chain Risk" designation | Yes | NA | A | A | A | NA |
| E25 | Warren/Wyden antitrust probe of Google–Anthropic and Microsoft–OpenAI partnerships | No | NA | A | A | A | NA |
| E26 | State AGs joint investigation of OpenAI | No | NA | A | A | A | NA |
| E27 | 25% of federal lobbyists now work AI issues; labs are biggest AI spenders | No | A | C | A | A | A |
| E28 | Five Eyes June 22 advisory: AI offensive cyber threat is "months, not years" | No | A | A | C | A | A |
| E29 | Anthropic June 2026 call for global development pause (while having dropped own unilateral pause) | Yes | A | C | A | A | A |

**Inconsistency counts:**

| H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|
| **6** | **0** | **2** | **1** | **0** |

**Note on H5:** H5 carries 0 inconsistencies in this expanded matrix (vs. 1 in the prior cycle's smaller evidence set) because the evidence item previously scored I against it (episodic, not structural) is subsumed into new evidence that scores A. However, H5 remains prescriptive — it describes where governance *should* go, not where it *is*. It has zero inconsistencies but also very few confirmations (only the sovereign-fund proposals are weakly C). H2 has zero inconsistencies **and** the heaviest confirming evidence. **H2 is the sole least-disconfirmed hypothesis.**

---

## Group 2: Economics of the Labs

**Question:** What is the most likely resolution of frontier AI labs' structural unprofitability?

**Hypotheses:**
- H1: Standard tech scaling (Amazon path)
- H2: Structural unprofitability -> absorption
- H3: Bifurcation (enterprise survives, consumer collapses)
- H4: Government utility/infrastructure model
- H5: Pre-revenue for the actual product

| # | Evidence Item | Diagnostic? | H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|---|---|---|
| E1 | OpenAI Q1 2026: $5.7B revenue, -122% operating margin, ~$6.95B non-GAAP operating loss | Yes | **I** | C | A | C | A |
| E2 | OpenAI full-year projection: ~$30B revenue, losses >$36.6B annualized | Yes | **I** | C | A | C | A |
| E3 | OpenAI losses increasing 138% YoY (2025: $20.9B loss) | Yes | **I** | C | A | C | A |
| E4 | OpenAI CFO Friar: not certain revenue growth supports $600B compute commitment | Yes | A | C | A | C | A |
| E5 | Stargate restructured from $1.4T capex to $600B mostly-rental (AWS, GCP, CoreWeave, Oracle, Azure) | Yes | A | C | A | C | A |
| E6 | OpenAI IPO delayed toward 2027; Altman refuses sub-$1T valuation | Yes | A | C | A | C | A |
| E7 | SpaceX IPO rocky debut chilling mega-cap tech IPO appetite | No | A | C | A | A | A |
| E8 | Kalshi: 59% odds OpenAI IPO announced by March 2027 | No | A | A | A | A | A |
| E9 | OpenAI 5% government stake proposed ($42.6B at $852B valuation) | Yes | **I** | C | NA | C | **I** |
| E10 | Altman wants every major lab paying 5% into Alaska-style sovereign fund | Yes | A | C | NA | C | A |
| E11 | Sanders: American AI Sovereign Wealth Fund Act — 50% of largest AI companies (~$7T) | No | A | A | NA | C | A |
| E12 | UK £500M Sovereign AI Fund established (April 2026) | No | NA | A | NA | C | NA |
| E13 | Jalapeño custom inference chip: claimed ~50% cost savings vs GPU inference | Yes | C | A | A | A | C |
| E14 | OpenAI software optimization: reported ~50% inference cost cuts on targeted models | Yes | C | A | A | A | C |
| E15 | Jalapeño deployment: late 2026 at gigawatt scale (pre-production) | No | A | A | A | A | A |
| E16 | Anthropic confidential S-1 filed June 1 (beating OpenAI to registration) | Yes | A | A | C | A | A |
| E17 | Anthropic Q2 projection: $10.9B revenue, $559M operating profit (first ever) | Yes | C | A | C | A | C |
| E18 | Anthropic profitability partly timing-engineered: $1.25B/mo SpaceX compute contract ramp-up discount in May–June | Yes | A | C | A | A | A |
| E19 | Anthropic compute costs per revenue dollar: 71c (Q1) -> 56c (Q2) | Yes | C | A | C | A | C |
| E20 | SemiAnalysis projects Anthropic >$1B operating profit in Q3 2026 | No | A | A | C | A | A |
| E21 | Steady-state compute costs (~$1.25B/month) expected to erase margins late 2026/early 2027 | Yes | A | C | A | A | A |
| E22 | Anthropic ARR: $47B (May 2026), overtaking OpenAI's ~$25B | Yes | A | A | C | A | A |
| E23 | Claude Code: $8B ARR (May 2026), 54% enterprise coding market, fastest ARR ramp in enterprise software history | Yes | A | A | C | A | A |
| E24 | Anthropic: 40% enterprise LLM spend vs OpenAI 27%, Google 21% | Yes | A | A | C | A | A |
| E25 | ChatGPT Plus 6-month retention ~71% (best-in-class among AI subscriptions) | Yes | C | A | A | NA | A |
| E26 | ChatGPT 12-month retention: Enterprise 88%, Team 68%, Plus 59% | Yes | C | A | C | NA | A |
| E27 | ChatGPT 50M+ paid subscribers, 9M+ business users | No | C | A | A | A | A |
| E28 | OpenAI $600B infrastructure commitment inconsistent with enterprise-only model | Yes | A | A | **I** | C | A |

**Inconsistency counts:**

| H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|
| **4** | **0** | **1** | **0** | **1** |

**Note on H2/H4 co-lead:** Both carry 0 inconsistencies in this expanded matrix. However, the **confirming evidence is asymmetric**: H2 (absorption) has heavy confirmation from OpenAI-specific evidence but Anthropic's divergent trajectory weakens it (E16–E24 are all A for H2); H4 (utility model) has the broadest confirming base across both companies' evidence. The prior matrix's single H2 inconsistency (Anthropic's divergence) is now scored A rather than I because Anthropic's profitability is unaudited and may be timing-engineered (E18, E21) — we are withholding the I until the S-1 goes public. **H4 remains the leading hypothesis; H2 describes OpenAI specifically.**

**Key divergence:** Anthropic's evidence (E16–E24) is strongly consistent with H3 and ambiguous for everything else. OpenAI's evidence (E1–E15) is strongly consistent with H2 and H4. The matrix is describing two different companies on two different trajectories — a fact the hypothesis set may need to accommodate more formally.

---

## Group 3: Offense/Defense Investment

**Question:** Why have frontier AI models developed disproportionately strong offensive cyber capabilities relative to defensive capabilities, and what is the right policy response?

**Hypotheses:**
- H1: Data allocation skew (Ho mechanism)
- H2: Intentional development for government customers
- H3: Emergent from general reasoning
- H4: Structural domain asymmetry (offense inherently easier)
- H5: Evaluation bias

| # | Evidence Item | Diagnostic? | H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|---|---|---|
| E1 | Ho's spiky-capability thesis: capabilities track RL data investment domain by domain | Yes | C | A | **I** | C | NA |
| E2 | Models strong at offensive cyber but weak at biology (pre-GeneBench) | Yes | C | A | **I** | C | NA |
| E3 | Hugging Face breach was real-world autonomous action, not benchmark artifact | Yes | C | A | A | C | **I** |
| E4 | Open-weight models closing gap to 4–7 months on offensive cyber (AISI July 2026) | Yes | C | **I** | A | C | NA |
| E5 | No lab has disclosed offense/defense training data allocation ratios | Yes | A | A | NA | A | NA |
| E6 | No transparency proposal targets offense/defense allocation (all copyright/provenance focused) | Yes | A | A | NA | A | NA |
| E7 | Andrew Ho's startup targets biology + statistical reasoning, not defensive cyber | Yes | A | NA | NA | C | NA |
| E8 | Ho chose domains with gradeable reward signals (biology), avoiding defense's ambiguous feedback | Yes | C | NA | NA | C | NA |
| E9 | AISI evals lack active defenders; impose no alert penalties; contain intentional attack paths | Yes | A | A | A | C | A |
| E10 | AISI: 80%-reliability cyber-task horizon doubling every 4.7 months (late 2024–Feb 2026) | No | C | A | A | C | NA |
| E11 | AISI building defended ranges with active monitoring, EDR, real-time IR | No | A | A | A | A | A |
| E12 | Labs deliver "defense" as gated access to dual-use capability (Cyber Verification Program, Claude Code Security) | Yes | A | A | A | C | NA |
| E13 | Anthropic found 500+ vulnerabilities in production open-source code using Claude | No | A | A | C | A | NA |
| E14 | PNNL partnership: Claude used for red-team emulation on water treatment plant simulation | No | A | C | A | C | NA |
| E15 | June 2 EO directs AI-enabled cyber defense; no training-data requirement attached | Yes | A | A | NA | C | A |
| E16 | Five Eyes advisory: AI offensive cyber threat is "months, not years" away | No | C | A | A | C | NA |
| E17 | White House framework: classified cyber benchmarks, no offense/defense allocation disclosure requirement | Yes | A | A | NA | A | A |
| E18 | Open-weight models exempt from federal review — fastest-diffusing offensive capability is least reviewed | Yes | A | A | NA | C | **I** |
| E19 | Containment breaches (Irregular): models autonomously executed 17,600+ actions over four days | No | C | A | C | C | **I** |

**Inconsistency counts:**

| H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|
| **0** | **1** | **2** | **0** | **3** |

**H1/H4 co-lead confirmed.** H4 (structural domain asymmetry) has the heaviest confirming evidence. H1 (data allocation skew) has zero inconsistencies but also fewer confirmations — it explains the *mechanism* (data followed the signal) while H4 explains *why* (offense produces clear reward signals). Together they remain the synthesis: **H4 explains H1.**

---

# ANNEX B — Deepened Findings from Follow-Up Probes

## Finding G1-9: Irregular — the vendor that broke three labs

**Source:** CNBC (8/9), IT Pro, Calcalist, Engadget, AI Weekly — news tier, multiply corroborated. Moderate-high confidence on events; low on completeness.

**Details:** Irregular was founded in 2023 in Tel Aviv by CEO Dan Lahav (ex-IBM AI) and CTO Omer Nevo (ex-Google). Backed by Sequoia and Redpoint with $80M, valued at $450M. Serves as primary AI security eval partner for OpenAI, Anthropic, Meta, and Google DeepMind. Between April–late July 2026, a misconfiguration in their evaluation harness left machines running AI models connected to the live internet while evaluation prompts told models they were fully isolated.

**Critical gap:** Irregular refuses to reveal whether more labs (specifically Google DeepMind, the fourth named client) were affected. TechTimes (8/7) reports the vendor "won't reveal if more AI labs were hit by same evaluation breach."

**D&D assessment:** The single-vendor root cause remains this cycle's highest deception priority. Two scenarios if the story is incomplete: (a) additional labs were hit but suppressed disclosure → strengthens H2 dramatically (coordinated suppression rather than coordinated disclosure); (b) the Irregular narrative is itself a cover story for a more direct inter-lab communication → returns pre-arrangement thesis. Neither has confirming evidence, but the refusal to disclose scope is a yellow flag.

**Scoring:** H1=A H2=A H3=NA H4=A H5=NA. No matrix change. Watch item.

## Finding G2-6: Anthropic profitability is contested — the "swindle" thesis

**Source:** wheresyoured.at (Ed Zitron, analysis blog), ChatForest, Quasa.io, Hacker News — analysis/opinion tier. Low-moderate confidence (strong argument, opinionated source).

**Details:** The $1.25B/month SpaceX compute contract includes a deliberate ramp-up discount for May and June before full freight kicks in July. Q2 2026 (April–June) is the only quarter in which Anthropic's single largest expense is artificially suppressed — and that is the quarter leaked as "profitable." Compute costs per revenue dollar dropped from 71c (Q1) to 56c (Q2), but the analysis argues this drop is partly mechanical rather than structural. Zitron questions whether the operating profit survives a GAAP audit.

**Scoring:** H1=A H2=C H3=A H4=A H5=A. This evidence is consistent with H2 (whole-industry structural unprofitability, including Anthropic) but scored A rather than I against H3 because the timing-engineering thesis is unaudited analysis, not fact. **The S-1 going public is the discriminator.**

## Finding G2-7: OpenAI financials show loss widening despite cost-curve claims

**Source:** wheresyoured.at, MarketWise, tradingkey, Yahoo Finance — analysis + news tier. High confidence on the reported figures (consistent across sources, traceable to OpenAI investor materials).

**Details:** Q1 2026: $5.7B revenue, ~$6.95B non-GAAP operating loss (-122% margin). Full-year projection: ~$30B revenue but >$36B in losses. YoY losses increased 138% ($20.9B in 2025). The fundamental challenge: compute and talent spending growth matches revenue growth — cost curve improvements are being swamped by scaling, not outpacing it.

**Scoring:** H1=I H2=C H3=A H4=C H5=A. Confirms existing H1 inconsistencies (no moat, costs scale with revenue).

## Finding G2-8: Stargate restructured from capex to opex — from building to renting

**Source:** TechTimes (5/19), CNBC (6/1), OpenAI blog posts — news tier + primary source. High confidence.

**Details:** The January 2025 White House-announced $500B Stargate JV has been functionally replaced by rental arrangements with AWS, GCP, CoreWeave, Oracle, and Azure. The $600B target (down from $1.4T) is now operating expense, not capital investment. CFO Sarah Friar reportedly expressed uncertainty that revenue growth supports these commitments.

**Significance for H4:** A company that rents rather than owns its critical infrastructure is structurally dependent on its suppliers. If revenue fails to materialize at the projected scale, the rental model becomes a liability spiral (commitments outlast revenue). This is the H2→H4 mechanism in concrete form: OpenAI is building something it cannot afford to own, cannot afford to rent at scale, and cannot afford to stop renting.

## Finding G1-10: The White House framework is classified and unpublished

**Source:** Axios (8/3, 8/4), Fortune (8/4), TheNextWeb, CNBC (8/3) — news tier, multiply corroborated. High confidence.

**Details:** The White House finalized the framework behind closed doors on August 3–4. Benchmarks and model thresholds are classified (NSA/CISA/Treasury classify the cyber-capability assessment). The framework will not be publicly released. Participating companies know the criteria; the public, Congress, civil society, and non-participating competitors do not. Rep. Gottheimer issued a statement on the framework but its content does not indicate publication.

**Scoring against Group 1:** H1=A H2=C H3=A H4=A H5=A. This is the purest form of capture: a regulatory regime whose rules are secret, whose thresholds are set by the regulated, and whose enforcement is discretionary. Strongest single confirming evidence for H2 in the entire matrix.

## Finding G1-11: GAAIA would formalize the capture structure

**Source:** Mondaq, Cato Institute, Lawfare, AAF, Broadband Breakfast, Obernolte press release — institutional/analysis tier. High confidence on provisions; bill is a discussion draft, not law.

**Details:** The Great American AI Act would: (a) formally establish CAISI within Commerce (the body already administering the classified framework); (b) create Independent Verification Organizations (IVOs) licensed by CAISI to audit frontier developers' compliance; (c) preempt state AI regulation for 3 years, preventing the accumulation of state-level rules the industry is lobbying against; (d) allow states to regulate AI *use* but not *development*. Lawfare: "Congress should do something — the case for (fixing) the Great American AI Act."

**Group 1 scoring:** H1=A H2=C H3=C H4=A H5=A. GAAIA is simultaneously evidence for H3 (Congress attempting legislation) and H2 (the bill would codify the industry-friendly CAISI structure and preempt stricter state action). The 3-year state preemption is the bridge hypothesis's barrier-to-entry mechanism arriving through legislative channels.

## Finding G1-12: AI lobbying at industrial scale — 25% of federal lobbyists

**Source:** Forbes (2/20), OpenSecrets, Metaintro, NBC — news/institutional tier. High confidence.

**Details:** One in four U.S. federal lobbyists now works on AI issues (up from 11% in 2023). OpenAI and Anthropic are among the biggest AI lobbying spenders. Lobbying firms are bundling cross-client positions on training data, copyright, child safety, and competition. Even as labs publicly call for safety rules, lobbying records show they fight legal guardrails in statehouses. Congress rejected using the defense bill to preempt state AI regulation — the second major setback for labs seeking federal preemption.

**Bridge hypothesis:** Direct evidence for the bridge. Labs publicly advocate for regulation (Group 1, H2 — theater of self-regulation) while lobbying for the specific form of regulation that protects incumbents and preempts challengers.

## Finding G3-6: Five Eyes joint advisory — offense timeline compressed to "months"

**Source:** Five Eyes agencies (CISA, NSA, NCSC-UK, CCCS, ACSC, NCSC-NZ) joint advisory June 22 — institutional tier (intelligence community). Highest confidence on the assessment itself; moderate on timeline precision.

**Details:** For most of 2025 and H1 2026, IC language on AI cyber risk stayed in the "years" bucket. This advisory shifted to "months, not years" — agentic AI systems can chain exploits, adapt to defenses in real time, and scale operations beyond human-team capacity. Concrete recommended actions: cut unnecessary system access, accelerate patching, tighten identity controls.

**Scoring:** H1=C H2=A H3=A H4=C H5=NA. Consistent with both H1 (data investment produced capability) and H4 (offense is structurally easier and now accelerating). The timeline compression means the Group 3 question is no longer academic — the offense/defense imbalance will produce real-world consequences before any governance mechanism can address it. This is the strongest signal that Group 3's transparency remedy (disclose allocation) must be pursued on an emergency basis or not at all.

---

# ANNEX C — Updated Cross-Group Synthesis

## The Four-Bridge Model

The four groups are no longer merely "analytically distinct but structurally bridged." The evidence this cycle reveals a **single integrated system** in which the same actors pursue the same strategy across all four domains simultaneously — and Group 4 shows the system has a foreign-policy dimension that both sharpens its justification and undercuts its effectiveness.

### Bridge 1→2 (Governance → Economics): Regulation as Bailout

**Mechanism:** Labs that cannot achieve profitability through markets (Group 2) seek government partnership that simultaneously provides governance legitimacy (Group 1) and financial support (Group 2). The 5% stake is the concrete expression: equity in exchange for regulatory accommodation.

**Evidence chain:**
- OpenAI floated the 5% stake **days after** Washington delayed GPT-5.6 (Tom's Hardware)
- Altman wants every major lab paying in — creating an industry structure, not a one-off deal
- Sanders' 50% bill provides left-flank Overton window expansion that makes 5% look moderate
- The UK's sovereign AI fund provides an international precedent
- OpenAI's IPO delay + Anthropic racing to file first = two strategies for the same problem (capital access) arriving at different H4 mechanisms (government equity vs. public market)

**Updated assessment:** HIGH confidence this bridge is operative. The question is no longer whether labs want regulation as bailout but whether any actor will provide it on terms the labs propose.

### Bridge 2→3 (Economics → Offense/Defense): Follow the Money

**Mechanism:** If government/defense contracts are the highest-value market (Group 2), training investment follows that demand (Group 3). The offense/defense skew partly reflects which customer is paying.

**Evidence chain:**
- June 2 EO directs federal agencies toward AI-enabled cyber defense — but the money flows to offense-shaped capabilities (vulnerability discovery, red-teaming) because defense lacks gradeable signals (Group 3, H4)
- Anthropic's Cyber Verification Program gates access to dual-use capability rather than investing in defensive training
- PNNL partnership: Claude used for red-team emulation, not defensive monitoring
- The classified federal benchmarks focus on cyber-capability assessment (offense measurement), not defensive performance

**Updated assessment:** MODERATE confidence. The demand signal exists (EO, defense contracts) but the training-allocation mechanism remains unobserved — no lab discloses how government demand translates into RL data decisions. This remains the highest-leverage transparency target.

### Bridge 1→3 (Governance → Transparency): The Capture Blocks the Remedy

**Mechanism:** The governance vacuum (Group 1) is why no lab has been required to disclose offense/defense data allocation (Group 3). But the vacuum is now being filled — by a regime the labs co-designed. The regime's classified benchmarks and unpublished thresholds specifically exclude allocation disclosure.

**Evidence chain:**
- The White House framework is classified and unpublished — even if it contains offense/defense evaluation, no one outside the regime can verify (G1-10)
- The framework was reviewed with participating labs on Aug 3–4; thresholds are lab-informed (G1-4)
- GAAIA would formalize CAISI (the body administering the framework) and preempt state-level alternatives
- Every existing transparency proposal targets copyright/provenance, not training allocation (G3-4)
- The governance regime that now exists was co-designed by the entities the disclosure would expose

**Updated assessment:** HIGH confidence. This is the most consequential bridge among the original three. The Group 3 transparency remedy (disclose offense/defense allocation) cannot be implemented through the Group 1 governance machinery because the machinery was designed by actors with no incentive to implement it. The remedy requires either: (a) an external actor with authority (EU AI Office is the leading candidate); (b) market pressure (insurance requirements expanding from containment to training transparency); or (c) whistleblower disclosure under the emerging legal protections (GAAIA, S.1792).

### Bridge 1→4 (Governance capture gains — and abuses — a real external justification)

**Mechanism:** The classified framework, natsec framing, and executive-authority gating documented in Group 1 gain a genuine external justification from Group 4: a real, completed, large-scale Chinese state-sponsored AI-orchestrated cyberattack (G4-4) substantiates the threat environment the regime claims to address. But a government insider's on-record objection (G4-3, Sacks) shows the same natsec apparatus is also being aimed at eliminating domestic and foreign open-source *competitors* — not just genuine threats.

**Evidence chain:**
- GTG-1002 (Nov 2025) predates the June 2 EO and is real, multiply corroborated, high-severity — this is not a manufactured pretext (G4-4)
- Yet the loudest current policy fight is not about that campaign — it's a proposed ban on Chinese open-weight *models* (Kimi K3) triggered by a benchmark loss, not a security incident (G4-3)
- Sacks explicitly names the mechanism: closed-source incumbents using government power to "entrench a duopoly" against open-source competitors, domestic and foreign alike
- The same classified apparatus that excludes offense/defense disclosure (Bridge 1→3) also excludes public scrutiny of whether any given "China threat" invocation is proportionate to an actual incident or opportunistic

**Updated assessment:** HIGH confidence. The natsec justification for opacity is not fabricated — but its use has expanded well past the incident that best supports it, into a tool for market structure. Bridge 1→3's finding ("capture blocks the remedy") extends here: capture also blocks the public's ability to tell a genuine security response from a competitive one.

### Bridge 2→4 (Same disease, different medicine — and China's dose is chronic, not acute)

**Mechanism:** Group 2 documented US labs seeking government equity as a negotiated, one-time fix for structural unprofitability. Group 4 shows China arrived at the same underlying condition — broad unprofitability at the model layer (G4-7) — but treats it as a permanent feature of industrial policy, funded through unconditional state subsidy rather than a compliance-linked equity bargain.

**Evidence chain:**
- Z.ai and Alibaba show the same revenue-outpaced-by-loss pattern as OpenAI (Group 2, E1–E3), at similar or worse ratios
- China's response is structural and pre-committed (provincial power subsidies, Big Fund equity) rather than crisis-negotiated (the 5% stake, still unresolved)
- Profitability where it exists sits one layer removed from the frontier model — chip and robotics firms, not the labs themselves — mirroring the US pattern where infrastructure suppliers profit while the model layer burns cash (G2-3, G2-8, G4-7)

**Updated assessment:** MODERATE-HIGH confidence. This reframes the US bridge hypothesis itself: if China has already normalized permanent state subsidy of unprofitable frontier AI as a steady state rather than a bridge to viability, the US "bailout" the report's core bridge hypothesis describes may not be a temporary arrangement either — it may be the entry price of participating in this industry going forward, on both sides of the Pacific.

### Bridge 3→4 (The transparency gap now has a distribution axis the US cannot reach)

**Mechanism:** Group 3 found no lab discloses offense/defense allocation and no proposal targets it. Group 4 adds that the fastest-diffusing frontier-adjacent offensive capability is arriving via a strategic rival's deliberate open-weighting policy, and that the same rival has already executed a real large-scale AI-orchestrated attack that substantiates the urgency the Five Eyes advisory (G3-6) warned of.

**Evidence chain:**
- China's open-weight strategy is explicit, coordinated national policy (G4-1), not organic community diffusion
- Chinese open models have captured roughly two-thirds of global usage share and are the primary AI on-ramp for the Global South (G4-2)
- The open-weight offensive-cyber gap AISI measured closing to 4–7 months (Group 3, G3-3) is substantially a description of this diffusion, not hobbyist catch-up
- GTG-1002 (G4-4) shows the offense-heavy capability profile Group 3 describes is not hypothetical when deployed by a state actor with intent

**Updated assessment:** HIGH confidence. This is the bridge that most changes the report's overall trajectory. The Group 3 transparency remedy, even if perfectly implemented by every US lab under Group 1's governance regime, has no jurisdiction over a foreign state releasing capability as deliberate policy. The domestic fix and the actual diffusion vector are no longer the same problem.

### The Integrated Assessment

The four groups describe a **single system with an external dimension** operating as follows:

1. **Labs build capabilities** that are disproportionately offensive because offense has clearer reward signals and higher-value customers (Group 3, H4→H1) — and a state actor with genuine offensive intent has already demonstrated what that capability profile does when deployed (Group 4, G4-4).
2. **Labs cannot sustain the economics** of capability development through markets alone (Group 2, H2→H4 for OpenAI; H3 for Anthropic, contingent on unaudited profitability claims) — and this is not a US-specific problem; China's frontier labs show the identical pattern, financed differently (Group 4, G4-7).
3. **Labs seek government partnership** that provides both financial support and governance legitimacy (Bridge 1→2), while co-designing the governance regime to exclude the transparency requirements that would expose the training decisions driving the capability imbalance (Bridge 1→3) — and increasingly to exclude foreign open-weight competition using the same natsec vocabulary, whether or not a given invocation is proportionate to an actual threat (Bridge 1→4).
4. **The resulting governance regime** is capture with real enforcement (Group 1, H2 operating through H3's machinery): it gates releases, classifies thresholds, and blocks competitors — but does not require disclosure of the training decisions that determine whether AI makes the world safer or more dangerous, and it has no reach at all into the fastest-diffusing offensive capability, which a rival state is releasing as deliberate policy (Bridge 3→4).

**Bottom line:** The least-disconfirmed explanation across all four groups is that frontier AI labs — on both sides of the Pacific — are building an industry structure in which permanent government partnership substitutes for market viability and regulatory capture substitutes for accountability. In the US this produces a classified, incumbent-authored regime that increasingly conflates genuine security response with competitive protection. In China it produces state-subsidized, deliberately diffused open capability that outruns any single country's governance reach. Neither system requires disclosure of the training decisions with the largest societal consequences, and the actor best positioned to close that gap domestically has no jurisdiction over the actor doing it fastest.

---

# ANNEX D — Load-Bearing Evidence and Next-Cycle Triggers

## Evidence whose reversal would most change the matrix

| Rank | Item | Current scoring effect | Reversal scenario | What changes |
|---|---|---|---|---|
| 1 | Anthropic Q2 GAAP operating profit (unaudited projection) | Supports H3 (bifurcation) in Group 2 | Public S-1 shows operating loss or margin compression | H2 strengthens to "whole-industry structural"; H3 loses its single differentiator |
| 2 | White House framework classified/unpublished | Strongest H2 confirmation in Group 1 | Framework leaked or published; contains meaningful transparency requirements | H2 weakened; H3 strengthened; Group 3 transparency remedy potentially tractioned |
| 3 | Irregular single-vendor root cause | Keeps containment-breach coordination scored as "emergent, not pre-arranged" | Story proves partial; labs communicated before disclosures | H2 strengthens dramatically; pre-arrangement narrative restored |
| 4 | OpenAI cost-curve evidence (Jalapeño + software optimization) | First H1-supporting evidence in Group 2's history | Post-deployment unit economics show no improvement | H1 revival dies; H2→H4 path accelerates |
| 5 | Five Eyes "months not years" advisory | Urgency signal for Group 3 transparency remedy | Offensive AI capabilities plateau or defensive capabilities emerge unexpectedly | Group 3 H4 weakened; H3 (emergence) partially revived; urgency of remedy reduced |

## Scheduled discriminating events

| Event | Expected timing | Group(s) | What it discriminates |
|---|---|---|---|
| Anthropic S-1 goes public (SEC review complete) | Q3–Q4 2026 | 2 | H2 vs H3: does booked GAAP profit exist? |
| First EU AI Office enforcement action against frontier GPAI | Q4 2026–Q1 2027 | 1 | H3 viability in EU; whether international regulation constrains deployment |
| Astra release path through federal review | Sep–Oct 2026 | 1 | H2 vs H3: does the regime extract transparency or just gate access? |
| AISI defended-range benchmark results | Unknown (ranges under construction) | 3 | H4 vs H5 residual: does offensive advantage hold against active defense? |
| Jalapeño post-deployment unit economics | Late 2026–early 2027 | 2 | H1 revival: does custom silicon actually bend the cost curve at scale? |
| Congressional action on 5% stake / sovereign fund | 2027+ (low probability near-term) | 2 | H4 acceleration: does government accept the equity structure? |
| Anthropic compute costs hit steady-state ($1.25B/mo) | Late 2026 | 2 | H3 durability: does profitability survive full-cost quarters? |
| GAAIA markup and floor vote | Unknown | 1 | H3 legislative leg: does binding AI legislation advance? |
| Trump administration Chinese-model ban decision (Entity List / procurement) | Unknown, live debate | 4 | H3 vs H5: does the natsec framing convert into concrete market exclusion? |
| Independent audit of Chinese LLM global usage-share claims | Unknown | 4 | H2 vs H4: is the diffusion lead real at claimed magnitude? |
| First substantive output of the US-China governmental AI safety dialogue | Unknown | 4 | H5 vs H3: does the Beijing summit dialogue produce anything beyond its own existence? |
| Next closed-vs-open frontier benchmark cycle (hardest-task delta) | Ongoing, quarterly | 4 | H2 vs H4: does the peak-capability gap hold, narrow, or close? |

---

# ANNEX E — Formal ACH Matrix, Group 4 (US-China Strategic AI Divergence)

**Question:** How does China's AI governance, economic, and capability trajectory interact with the US industry structure documented in Groups 1–3?

**Hypotheses:**
- H1: Convergence (different mechanisms, same functional endpoint)
- H2: Chinese structural advantage (subsidy + open-weighting outcompetes US model)
- H3: Instrumentalized threat (China threat used opportunistically for domestic capture)
- H4: Bifurcated stable equilibrium (two parallel ecosystems, neither wins outright)
- H5: Managed rivalry (genuine bilateral cooperation constrains worst outcomes)

| # | Evidence Item | Diagnostic? | H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|---|---|---|
| E1 | Xi Jinping's July 2026 speech explicitly endorses open-weighting as national strategy | Yes | A | C | A | C | NA |
| E2 | Provincial power subsidies up to 50% for AI data centers (Gansu, Guizhou, Inner Mongolia) | Yes | A | C | NA | C | NA |
| E3 | DeepSeek's ¥50B external funding round led by state "Big Fund" | Yes | C | C | NA | C | NA |
| E4 | Chinese LLMs ~two-thirds global weekly-token market share, #1 for 12 straight weeks | Yes | A | C | NA | C | NA |
| E5 | Xi pledges 5,000 training slots + cooperation centers with ASEAN/AU/BRICS | Yes | A | C | NA | C | NA |
| E6 | WAICO established, 29 countries sign, HQ in Shanghai (July 16) | Yes | A | A | NA | C | A |
| E7 | China reaffirms UN as primary global AI governance channel (April 2026) | No | A | A | A | A | C |
| E8 | Trump-Xi Beijing summit produces governmental AI safety dialogue agreement | Yes | A | A | A | A | C |
| E9 | Track II dialogues (Safe AI Forum–Fudan, March 2026) reportedly intensifying | No | A | A | A | A | C |
| E10 | Kimi K3 (2.8T params) beats Fable 5/GPT-5.6 Sol in blind coding tests (July 16) | Yes | A | C | A | C | NA |
| E11 | Trump administration reviving Chinese-model ban push after Kimi K3, citing cybersecurity | Yes | A | A | C | A | **I** |
| E12 | David Sacks (WH AI advisor) warns closed-source incumbents using government power to eliminate open-source competitors, "entrench a duopoly" | Yes | A | A | C | A | A |
| E13 | Commerce previously drafted, then killed, Entity List/open-source targeting rules | Yes | A | A | C | A | A |
| E14 | Five independent open-weight families (DeepSeek, Qwen, Kimi, GLM, Mistral) reach frontier quality simultaneously | Yes | A | C | NA | C | NA |
| E15 | Closed models still lead hardest tasks: o3 96.7% vs. DeepSeek R1 79.8% (AIME); Opus 4.6 ~80% vs. Qwen 3.5 76.4% (SWE-bench) | Yes | A | **I** | A | C | NA |
| E16 | GTG-1002: Chinese state-sponsored group used Claude autonomously (80–90%) for full-lifecycle cyberespionage against ~30 targets (Nov 2025) | Yes | A | A | C | A | **I** |
| E17 | H200 export deal (Trump-announced, 25% US cut) remains in legal limbo; zero deliveries | No | A | C | A | A | A |
| E18 | $160M+ chip-smuggling ring broken up; 8+ networks identified; Supermicro $2.5B diversion indictment | Yes | A | C | A | A | A |
| E19 | Nvidia reportedly worried continued ambiguity lets domestic Chinese chip rivals (Huawei) capture local market | Yes | A | C | A | C | NA |
| E20 | China's model-layer economics mirror the US: Z.ai revenue +132%, loss +60% to $694M; Alibaba $1.3B AI revenue vs. $55B infra spend | Yes | C | A | NA | A | NA |

**Inconsistency counts:**

| H1 | H2 | H3 | H4 | H5 |
|---|---|---|---|---|
| **0** | **1** | **0** | **0** | **2** |

**Note on H3/H4:** Both carry 0 inconsistencies, but the confirming evidence is asymmetric in a way that resolves the tie rather than leaving it open. H4 has the heaviest confirming base in the group (8 of 20 items score C) and describes the top-line structural outcome: two ecosystems, neither dominant across all axes. H3 has 3 confirmations, but one of them (E12) is a direct, on-record government-insider statement naming the exact mechanism — the highest-diagnosticity single item in this matrix. **H3 explains a mechanism operating within H4's bifurcation; it is not a competing top-line claim.** H2 (Chinese structural advantage) carries its own inconsistency (E15) because the hardest-task benchmark gap has not closed, which is precisely what a clean "advantage" story requires and does not get. H5 (managed rivalry) is the most disconfirmed hypothesis in the group — real dialogue channels exist (E7–E9) but sit uncomfortably next to a completed state-sponsored attack (E16) and an active market-exclusion push (E11).
