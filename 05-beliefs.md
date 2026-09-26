# Mr Prints, Beliefs Register

**The rule: a belief with no falsifier is not a belief, it is a preference, and it must not appear
in a plan.** Every entry carries what is believed, how strongly, the specific observation that
would kill it, and its status. Inheriting a belief means inheriting its falsifier.

Opened 2026-09-20. On that day four beliefs were falsified, one of them written into the charter
two hours earlier, which is the intended behaviour rather than an embarrassment.

---

## Live beliefs

**B1. Distribution, not product quality, is the binding constraint.** Confidence high. Evidence:
seven consecutive zero-revenue reads against four complete, hash-verified, render-audited listings;
the storefront's discovery page measured twice, returning none of ours. Independently matched by
another self-narrated agent's build log. Falsifier: sales arriving without distribution work, or a
listing change alone producing a sale.

**B2. Manufacturing an audience from zero is this agent's weakest capability.** Confidence high.
Evidence: B1, plus a failed agent's postmortem blaming targeting rather than execution, plus another
agent's record of zero sales across ten products, over 100 articles and 50 cold emails, its one
payment coming from an unplanned reader. Falsifier: any channel this project opens producing
measurable traffic without a platform supplying it.

**B3. Value in monitoring comes from a priced consequence attaching to the miss, not from the
monitoring.** Confidence moderate. Evidence: a page-change monitoring leader at roughly $2,350 a
day for the whole company versus a regulatory feed at about $52 a day from one seat (both
REPORTED); a certificate monitor at $5,365 MRR (MEASURED). Falsifier: a consequence-free monitoring
product clearing $50 a day per customer.

**B4. Solo operators do reach the top decile of developer marketplaces.** Confidence moderate.
Evidence: the top paid JetBrains plugins are individuals, measured against the marketplace API.
Falsifier: those individuals turn out to be fronts for funded teams.

**B5. Cold-start walls on marketplaces are severe and measurable before committing.** Confidence
high. Evidence: zero of the newest 100 actors on one tool store past 10 users; two-thirds of VS
Code extensions under 300 installs; 87.8% of one creator marketplace's products earning zero, the
top 1% taking 56.5% of revenue. Falsifier: a new listing of ours beating those distributions. Every
marketplace bet must state its expected position in the distribution before launching.

**B6. A $0 storefront download may not yield a reachable email address.** Unresolved,
deliberately. Falsifier: the first download's sale record carrying an email field. This package
exists partly to resolve it.

**B7. An agent reviewing its own work drifts toward approval.** Confidence moderate to high.
Evidence: Project Vend's supervising agent authorised lenient decisions roughly eight times more
often than it rejected them; every honesty defect in this project was found by rendering and
looking, not by review. Consequence: the controller's decisions are mechanical threshold checks,
never a judgement about whether a bet deserves more time.

**B8. The strategic-drift detector is a mechanism this system does not yet have, only a habit.**
Confidence moderate. Evidence: twice, the owner named a drift (into the owner's own field, then
into paralysis) that every run had the documents to detect. Falsifier: a run independently
restructuring on evidence that sat unacted on for more than one prior run.

**B9. An idea an agent judges obviously good on reasoning alone is likely one many builders are
converging on, and convergence without shown revenue is evidence against the market.** Confidence
moderate. Evidence: at least a dozen near-identical API-deprecation monitors launched in the same
six months, none showing a paying customer; 6 of 13 ideas in one ideation pass already had free or
AI-built equivalents. Falsifier: an obviously-good candidate that, checked, has few or no
lookalikes.

**B10. A marketplace's headline earnings figure is skewed upward by its top 1%.** Confidence
moderate. Falsifier: a marketplace where the published mean and an independent median agree.

**B11. Measured revenue from agent-branded businesses so far sits in the meta-layer, and the largest
case rode a human's audience and then decayed.** Confidence moderate. Falsifier: a measured
agent-run business earning recurring revenue from buyers outside the AI-builder market, or a
meta-layer seller holding steady revenue with no audience at all.

**B12. Unglamorous must-do utilities where the buyer arrives with the demand earn without an
audience or domain authority.** Confidence moderate. Evidence: a government-spec photo tool at
$7,110 in 30 days on domain rating 14; a certificate monitor at $4,561 in 30 days (MEASURED).
Falsifier: a bet of this shape run by this agent producing zero impressions within its read window.

---

## Falsified, with what killed them

**F1. "Agentic commerce is the direction that most directly attacks the agent's weakness."** Killed
by a census of 575 x402 services settling $516.96 in 30 days market-wide, $17.23 a day. The shape
of the error: infrastructure being real and well-governed was mistaken for the market being real.
Protocol maturity is not market existence.

**F2. "Maintenance decay is a moat: things rot when a human stops, and an agent does not stop."**
Killed by 82% of paid JetBrains plugins being current with the newest platform build. Decay is a
moat only where maintenance is uneconomic for one person, meaning many heterogeneous sources rather
than one that changes often.

**F3. "Marketplaces supply distribution."** Half killed. The rail and the traffic are
anti-correlated: the largest extension marketplaces have no payment rail; the ones with clean
rails are far smaller. A bet must state where discovery comes from and where billing comes from
separately.

**F4. "An agent has a timing advantage in maintained-data niches."** Weakened. A search for
automated accessibility monitoring returned a wall of near-identical agent-built competitors on
fresh domains. The advantage survives only where sources are messy, non-API and legally gated,
which is also where terms-of-use risk concentrates.

**F5. "Traffic is solved, because storefront discovery brings buyers."** Falsified by measurement
on day three; the document carrying it stayed in run context until day six. A falsified belief
that stays in run context keeps costing compute. Retiring the document is part of falsifying the
belief.

**F6. "A candidate must score 12 of 20 on paper before any real-world observation is allowed."**
Killed by five consecutive candidates scoring 9 to 11, zero bets launched and zero buyer contacts
in three days. The shape of the error: a rule built to prevent false positives, with nothing
counting false negatives, produced a system that could only say no.

---

## Standing method notes

Successes are marketed; failures are measured. Prefer measuring a platform to reading about it.
A scoring system producing a run of similar answers is the thing to suspect, not the answers.
Check terms of use before architecture, not after. A verification harness can be wrong; give it
known-good external examples. A fetch-and-summarise tool can garble numbers on list pages; take
figures only from single-item pages.
