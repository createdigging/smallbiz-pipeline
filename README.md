# Small-Business Idea Pipeline

> Eight standard startup frameworks (JTBD, Mom Test, Lean, Hooked, Sean Ellis 40%, AARRR, April Dunford, Van Westendorp) stitched into one gate-based flow — a checklist that kills a weak idea *before* you build it, cheaply.

Eight standard frameworks assembled — **faithful to their originals** — into a single gated pipeline. It prevents the classic death of "had an idea → wanted to build it → built it → somehow it doesn't sell" at a checkpoint on each gate. This is a generic version, not tuned to any one person or business, and it works across any domain (apps / web / content / services / physical goods).

> How to use it: run a business idea through the gates from G0 in order. The core is **forcing "stop if there's no evidence" at every gate**. If you're having an AI assistant make the calls, hand it the rule "don't advance past any gate without evidence" — that's what makes it bite.

## Pipeline at a glance

```
S1 Discovery     JTBD              — people hire "progress," not products
S2 Validation    Mom Test          — take past behavior and commitment, not opinions
S3 Build         Lean Startup      — the MVP is validated learning, not a product
S4 Habit         Hooked            — Trigger → Action → Variable Reward → Investment
S5 Measure PMF   Sean Ellis 40%    — 40% "very disappointed" + the retention curve
S6 Growth        AARRR             — Acquisition → Activation → Retention → Referral → Revenue
S7 Positioning   April Dunford     — 5+1 components (competitive alternatives → market category)
S8 Pricing       Van Westendorp    — measure WTP with 4 questions
```

The order is the lifecycle. In practice, though, S7 (positioning) and S8 (pricing) are set provisionally *before* S3 and locked in *after* passing S5 — you can't write MVP copy without positioning, and you can't build unit economics without a price.

## S1. Discovery — Jobs to be Done (Christensen / Moesta / Ulwick)

People don't buy features. They **"hire" a product to make progress in their life.**

- The unit of analysis is the **job** ("situation × motivation × desired outcome"), not customer demographics.
- What decides the switch is the **four Forces of Progress**:
  - **Push** — dissatisfaction with the status quo (the force to leave)
  - **Pull** — the appeal of the new solution (the force that draws you in)
  - **Anxiety** — fear of switching (a force that kills)
  - **Habit** — inertia of the status quo (a force that kills)
- A switch happens only when Push + Pull outweigh Anxiety + Habit. Adding features only touches Pull — **lowering Anxiety (refund guarantees, migration support) is often more effective.**
- Instrument: the **Switch interview** (reconstruct, chronologically, why someone who recently switched did it *on that day*). Without interviews, estimate push/pull from 1★/5★ analysis of competitor reviews, churn-reason data, and search queries (lower precision).

## S2. Validation — The Mom Test (Rob Fitzpatrick)

The three rules of "asking in a way even your mother can't lie about":

1. Don't talk about your idea — talk about **their life**.
2. Don't ask about hypotheticals or the future — ask about **specific past events** ("Last time that happened, what did you do?").
3. Stop talking, listen.

- Three kinds of bad data to throw out: **compliments / hypothetical fluff ("I'd probably use it if it existed") / feature wish-lists.**
- Always close a conversation with a **commitment ask** (money, time, a referral). They aren't a prospect until you've given them a concrete chance to say no.
- The essence isn't "interview technique," it's "**don't trust opinions, trust behavior**." Without interviews the principle is the same — capture commitment as behavioral data: **pre-orders / landing-page email signups / paid waitlists / actual payments.** Only "signed up / paid" counts as a Yes; likes, downloads, and impressions are all on the compliment side.
- But behavioral data only tells you **what**. The **why** (why they dropped off, what they compared you to) stays a permanent blank unless a human asks somewhere — accept that as the cost of skipping interviews.

## S3. Build — Lean Startup (Eric Ries)

- Spin the **Build → Measure → Learn** loop as fast as possible. What you're building isn't a product, it's **validated learning.**
- MVP = "the smallest experiment that yields learning fastest." An MVP you're not embarrassed by shipped too late.
- **Innovation accounting**: measure with metrics that can change behavior (cohort conversion/retention), not vanity metrics (cumulative downloads/signups).
- At the end of each loop, explicitly decide **pivot or persevere** (dragging it out is the worst outcome).

## S4. Habit — Hooked (Nir Eyal)

Retention is the real body of revenue. A four-stage loop:

1. **Trigger** — start with external (notifications), grow it into internal (emotion, context).
2. **Action** — minimize the friction of doing it (Fogg: motivation × ability × trigger).
3. **Variable Reward** — make rewards **variable**. Three kinds: Tribe (social validation) / Hunt (search, acquisition) / Self (achievement, mastery).
4. **Investment** — have users pour in time, data, customization, and social capital, creating **something they'd lose by quitting** (stored value strengthens the next trigger).

Design check: if you can't immediately answer "what emotion is this product's internal trigger," "which of the rewards is variable," and "what does a user accumulate over 30 days," there's no habit design in place.

## S5. Measure PMF — Sean Ellis test + retention curve

- **One question**: "How would you feel if you could no longer use this product?" — very disappointed / somewhat disappointed / not disappointed.
- **Over 40% "very disappointed"** is the PMF watershed. But limit the audience to **users who used it 2+ times in the last 2 weeks** (asking everyone dilutes it).
- **Superhuman PMF Engine** (Rahul Vohra): don't discard it even below 40% — loop through ① **re-segment** around the persona of those who said "very disappointed" (the number rises without changing the product) ② kill only the obstacles that trip up the "somewhat disappointed" group ③ deepen the core the "very disappointed" group loves.
- **The retention curve is the strongest instrument**: plot cohort retention daily. **A curve that keeps falling = a leaky bucket (no PMF). A curve that flattens somewhere = that height is the retained core = the true size of the segment that genuinely wants it.** Even at a scale too small to run surveys, the curve doesn't lie.
- Implementation: an in-app one-question survey (one modal tap) is enough. No interviews required.

## S6. Growth — AARRR / Pirate Metrics (Dave McClure)

A five-stage funnel. **Identify where it's clogged, then fix only that one stage:**

| Stage | Question | Representative metric |
|---|---|---|
| Acquisition | Where do they come from? | inflow by channel |
| Activation | Did they reach the first value experience? | onboarding completion, aha-moment rate |
| Retention | Do they come back? | D1/D7/D30, curve flattening |
| Referral | Do they bring others? | invite-send rate, k-factor |
| Revenue | Do they pay? | conversion rate, ARPU, LTV |

- Pick **one North Star Metric** (a behavioral metric tied directly to the value you deliver). AARRR is its diagnostic system, not dashboard decoration.
- The ordering trap: fix Retention before pouring money into Acquisition (don't pour water into a leaky bucket).
- **Lock in one distribution channel before building.** "Figure it out after building" is the most frequent cause of death.

## S7. Positioning — April Dunford (Obviously Awesome)

Run the 5+1 components **in this order** (the order is the point):

1. **Competitive alternatives** — what would the customer do without you? ("make do with Excel," "do nothing" are competitors too).
2. **Unique attributes** — capabilities you have that the alternatives don't.
3. **Value + proof** — the customer value those capabilities create, and the evidence for it.
4. **Target market** — the segment that feels that value most strongly.
5. **Market category** — choose the "shelf" where the value becomes self-evident (change the shelf and the same product changes meaning).
6. **(+1) Relevant trends** — the tailwind that makes this matter right now.

The output feeds everything: store description, landing page, the first screenshot, paywall copy. You shouldn't be able to write copy without settled positioning — if you can, the positioning is empty.

## S8. Pricing — Van Westendorp PSM

Measure WTP (willingness to pay) with four questions:

1. At what price is it so expensive you wouldn't consider it?
2. At what price is it so cheap you'd doubt the quality?
3. What price is expensive but still worth considering?
4. What price feels like a bargain?

The intersections of the four curves give the acceptable price range (RAI/OPP).

- When you can't run a survey: measure it directly with a **price A/B (paywall experiment)**. In the sense that behavior is more trustworthy than intent, this is arguably the primary method.
- Subscription practice benchmarks (RevenueCat / Adapty): aim for Day-1 paywall display rate ≥ 80% / trials are commonly 5–9 days, median trial→paid ≈ 45% / **hard-paywall conversion is several times that of freemium** (only people who've seen the value arrive) / timeline-style paywalls that make "when you'll be charged" explicit improve both start and conversion.
- Pricing isn't set-and-forget — keep cycling value, packaging, paywall, and promos (the Subscription Value Loop).

## Integrated gated flow

```
G0 Discovery       write the job and the 4 forces on one page (S1)
    │ can't articulate the progress → don't proceed
G1 Demand evidence take a commitment (S2: pre-order / signup / payment — opinions don't count)
    │ zero evidence → kill it (free if you haven't built yet)
G2 Channel locked  decide one channel before breaking ground (S6)
    │ can't decide → don't break ground
G3 Build           MVP = smallest learning experiment. Bundle provisional positioning (S7) and pricing (S8)
G4 Early users     recruit by hand (do things that don't scale)
G5 ★PMF★          40% test (S5, on the narrowed segment) + retention-curve flattening
    │ curve keeps falling → pivot or kill (make the S3 decision explicit)
G6 Growth          find the clog with AARRR → lock in positioning & pricing, optimize (S6–S8)
G7 Scale           invest more into the channels and segments that worked
```

## Sources

- Paul Graham — [Do Things that Don't Scale](https://www.paulgraham.com/ds.html)
- Bob Moesta / Christensen — [JTBD & Forces of Progress](https://jobstobedone.org/)
- Rob Fitzpatrick — [The Mom Test](https://www.momtestbook.com/)
- Eric Ries — The Lean Startup
- Nir Eyal — [Hooked Model](https://www.nirandfar.com/how-to-manufacture-desire/)
- Sean Ellis / Rahul Vohra — [Superhuman PMF Engine](https://review.firstround.com/how-superhuman-built-an-engine-to-find-product-market-fit/)
- Dave McClure — [AARRR Pirate Metrics](https://www.productcompass.pm/p/aarrr-pirate-metrics)
- April Dunford — Obviously Awesome
- Van Westendorp PSM / [RevenueCat paywall guide](https://www.revenuecat.com/blog/growth/guide-to-mobile-paywalls-subscription-apps/) / [Adapty trial conversion](https://adapty.io/blog/trial-conversion-rates-for-in-app-subscriptions/)

## License

The original frameworks belong to their respective authors. This document (the integration and prose) is MIT License.
