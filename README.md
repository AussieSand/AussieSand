# Built solo with AI. Verified before it counts.

I run a coaching business, and I build research-grade software by directing AI. I have no formal STEM education. I started working with AI in November 2022 and started writing software in mid-2025.

Everything on this page was built by one person directing AI, on a MacBook Pro with consumer AI subscriptions. There's no team, no institution and no custom models. That's by design.

> **All my project repositories are currently private.** The contribution graph below counts that private work as daily totals only, with no repo names and no code. I can give walkthroughs of any project here on request.

## How I measure the work

Generating code is cheap now. Trusting it is the hard part. So the measure I track is **velocity of verification**. Work only counts once it is either **operational**, meaning it's running in my business or as a working MVP, or **cross-matched against real data**, such as published measurements, real catalogues or real experiments.

Every project is built against four sources of failure: my own ignorance, my own bias, poor data, and the ways AI fails (confident fabrication, hallucination and cutting corners).

In practice that means:

- Before anything merges, an independent AI reviewer that didn't write it tries to break it, and I approve every merge myself.
- Pass marks and predictions are fixed before any results are seen.
- Research results are fingerprinted, and replays have to reproduce them.
- Missing data is labelled as missing. It's never filled in and never shown as a silent zero.
- Every claim is labelled for what it is: validated, not yet validated, or a teaching aid.
- Where a project has a plain-English guide and a workflow diagram, automatic checks tie them to the code, so the explanation can't quietly drift from what's built.

## Built for my business

**Digital twin** · *reached production in 2026*

One of my most advanced builds. It turns a decade of coaching judgement into a governed knowledge base that frontier AI models load directly as context. There's no vector database, no fine-tuning and no proprietary platform, just curated, version-controlled files that are tested in CI like code. It's coach-facing only: it helps me draft and reason through coaching decisions, and the coaching clients receive is still mine. Safety is layered and fails closed, with permanent rules written from real incidents. Specialist AI reviewers (medical, psychology, dietetics, and strength and conditioning) attack the knowledge itself, not just the code. Corrections I make are weighted over time, and the ones that prove themselves are promoted into the knowledge base.

A separate upstream pipeline will feed the twin new lessons from coaching material. Its first pieces exist: local text extraction, item tracking, scrubbing of certain identifiers, and processing records. The rest is mapped as an eleven-step plan that ends in lineage, so every accepted lesson traces back to a source it was allowed to come from. Its guide and workflow diagram label every part as built, proof, planned, draft or on hold, and automatic checks fail if the code, guide and diagram drift apart. The gate for real client material stays closed until I sign it off. The twin is designed to call deterministic tools, such as the Nutrition Planner below, so the numbers it relies on are never invented.

**Coach Desk** · *latest version merged Oct 2026*

My check-in review desk. It turns a client's check-in into drafted feedback on results, goals, nutrition and training, prepares branded nutrition documents, and saves the approved result back to the client record. Approval has to mean something: I can't approve a document unless every page of its current version was actually shown to me. The server enforces that as well as the screen, and evidence from an older version can't unlock a corrected one. The software proves the pages were shown; reading them stays my job. Its latest change was blocked by an independent review that found a timing bug the original tests had missed, then fixed and passed.

**Video tool** · *in use since Sept 2026*

It runs on my Mac and I drive it entirely from chat. Green-screen recordings and client photos go in, and finished Instagram-ready Reels and before-and-after posts come out. The cut-out, word-by-word captions, closing card and music are all done for me. Anything that breaks the house video standard is refused until I answer in my own words, and the tool never posts anything itself. Its 800+ automated tests use made-up videos and photos, never client media. My business had wanted a tool like this for over a decade.

**Nutrition Planner** · *since June 2026*

A phone-first nutrition app built on Australian food data. It has about 4,870 foods from AUSNUT 2023, checked Open Food Facts Australia products and my own approved list. Barcode scanning accepts exact matches only, so an unknown product goes to manual entry instead of a "close enough" guess. If a label doesn't list a value, the app shows "Not listed", never zero. The database itself keeps each person's data separate, not just the screens. It has about 1,300 automated tests. The core app is live in private alpha, and barcode and label-photo scanning are in final checks.

## Research builds

**Dyson** · *since Oct 2025*

A reproducible search tool that screens real star catalogues (ESA Gaia DR3 matched with NASA AllWISE) for the mid-infrared waste heat a Dyson sphere would have to give off. Its first real-data pilot ran on 1,000 stars within about 100 parsecs of the Sun. Of those, 746 couldn't be tested, 69 were removed by quality cuts, 185 were tested and none were selected. Every one of those counts matched the prediction written down before the run, and the run replays offline from its recorded evidence. It has 4,000+ automated science tests, with nearly twice as much test code as science code. Its own audit once found an inverted Bayes factor in one statistical gate. The gate was shut and the claims built on it were withdrawn.

**Impact** · *since May 2026*

Rebuilds a published 2024 Taylor impact experiment, in which an AISI 4340 steel rod hits a rigid wall at 245 m/s. It runs inside OpenRadioss, a free, open-source crash solver, on a MacBook. Twenty numerical-health checks were frozen before any run. Every input is labelled and every output is fingerprinted, and the results come with a plain-English report and a real-time 3D replay. A fine-mesh run takes about 6–8 minutes and costs nothing, so each new physics idea is one cheap experiment that can be audited.

**Jet Engine Lab** · *since Sept 2026*

A 3D jet-engine test cell in the browser covering turbojet, afterburner, turbofan, turboprop and rocket. At its core is a model of a real engine, the J79-GE-17 from the F-4 Phantom, sized from General Electric's published figures. 27 of 28 published readings held back from tuning fall within two error bars (typical miss 4.9%, reduced χ² 1.10). Its reference engine matches NASA's pyCycle data in 70 of 70 comparisons, with a worst gap of 0.72%. A built-in list names every game rule that has no published backing, so nobody mistakes a game aid for science.

## Coming into the open

Impact and Jet Engine Lab are the first candidates for open release. Each will have three ways in: one a 10-year-old can use, one for adults without a STEM background, and one for researchers.

## Work with me

I'm open to AI consulting work. Most AI projects stall at trust, not at writing the code. My work is the part that comes after: getting AI-built software to where people can rely on it, because it's running for real or it has been checked against real data. The method stays in-house. What you get is the verified result and the evidence behind it.

**Contact:** swarm+intelligence+2022@norton.me

<sub>Figures are as of October 2026 and are taken from the repositories themselves.</sub>
