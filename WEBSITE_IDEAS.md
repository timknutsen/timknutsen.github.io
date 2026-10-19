# Website Ideas and Version Log

This document is the working record for future updates to `timknutsen.no`.
It should improve as the site improves: ideas, decisions, source checks, and
committed changes belong here.

## Working Rules

- Keep the public site sparse and factual.
- Prefer public, verifiable facts over positioning language.
- Do not invent a personal brand, mission statement, or broad AI narrative.
- AI claims are fine when tied to a talk, a publication, a working tool, or a
  public repository. Describe AquaGen work at the level of approach, not
  internal numbers, costs, or colleagues' names.
- Use plain language. The page should sound like a scientist wrote it, not a
  marketing system.
- Every public claim should trace back to a source, a publication, or a commit
  in this repository.

## Public Source Baseline

Reviewed on 2026-06-16. This is the current source set to use for a stripped
down version of the page.

- GitHub profile: `timknutsen`, Tim Knutsen, public repositories.
  Source: https://github.com/timknutsen
- Frontiers Loop profile: Tim Martin Knutsen, Senior Researcher, AquaGen
  (Norway), Trondheim, Norway.
  Source: https://loop.frontiersin.org/people/870625/overview
- Google Scholar profile: Tim Martin Knutsen, AquaGen AS.
  Source: https://scholar.google.com/scholar?q=Tim+Martin+Knutsen
- LinkedIn profile: Tim Knutsen at AquaGen, with NMBU background.
  Source: https://www.linkedin.com/in/tim-knutsen-02567871
- NAR Genomics and Bioinformatics article, 2025: Tim Martin Knutsen listed with
  AquaGen AS, Trondheim, Norway, on a deep-learning paper for functional
  genomic prediction in farmed animals.
  Source: https://doi.org/10.1093/nargab/lqaf139
- Kyst.no profile note, 2017: Tim Martin Knutsen was hired as a researcher at
  AquaGen from 1 August 2017.
  Source: https://www.kyst.no/aquagen/tim-martin-knutsen-blir-forsker-i-aquagen/644343

## Idea Backlog

### 1. Bare-bones public profile

Status: superseded on 2026-10-19 by the October refresh (see Decision Log)

Simplify the website to a bare-bones public profile based only on what can be
found about me on the internet now. Remove inflated positioning, generic AI
language, and anything that feels like filler. The first version should be
simple enough that every sentence can be defended from a public source.

Likely page structure:

- Name: Tim Martin Knutsen.
- Role and affiliation: Senior Researcher or Senior Scientist at AquaGen AS,
  Trondheim, using the most defensible public wording.
- Short factual focus line: genomics, aquaculture breeding, bioinformatics, and
  practical data tools, only if supported by public sources or publications.
- Links: GitHub, Google Scholar, LinkedIn.
- Publications: keep a short selected list, or link out to Scholar instead of
  maintaining a long local list.
- Remove contact email unless there is a deliberate reason to publish it.
- Remove broad claims about LLM workflows, dashboards, APIs, and computer vision
  unless each item is tied to a specific public project or publication.

Open questions:

- Should the page say Senior Scientist or Senior Researcher? Public sources use
  both. Choose the wording that matches the current preferred title.
- Should the page mention AI at all? The 2025 deep-learning paper supports a
  narrow genomics-specific reference, but not a broad AI-tools identity.
- Should the domain be allowed to stay blocked by the AquaGen network until the
  category ages out, or should IT be asked to reclassify it?

## Decision Log

| Date | Decision | Reason |
| --- | --- | --- |
| 2026-06-16 | Start a living ideas and version-log document. | Future edits need a stable place for intent, source constraints, and commit history. |
| 2026-06-16 | Treat public sources as the constraint for the next simplification pass. | The next version should avoid unsupported self-description and generic AI phrasing. |
| 2026-10-19 | Re-centre the page on quantitative genetics plus AI tools for breeding, instead of a bare-bones cut. | Job applications coming up; the Geno talk (AI in breeding and everyday work, 2026) drew strong interest in the AI work. |
| 2026-10-19 | Title Senior Researcher; location Ås; canonical domain timknutsen.no. | Matches current title and where Tim works; the custom domain is live. |
| 2026-10-19 | Keep the Geno bull catalogue demo off the public site. | Built on Geno's data and images. |
| 2026-10-19 | No AquaGen case studies; AI section kept general. Tools list = most recently updated public repos. | Specific AquaGen examples revealed too much internal work. |
| 2026-10-19 | Do not link ukeoppgaver. | Household app; may show family members' names. |

## Committed Changes

Record commits here after they are made.

| Date | Commit | Change | Notes |
| --- | --- | --- | --- |
| 2026-10-19 | `bfa6ee1` | Refocused site on quantitative genetics and AI in research; general AI section, Talks, recent repos, timknutsen.no metadata. | Current deployed version. |
| 2026-06-12 | `97388b7` | Refocused personal site on AI/computer vision; added LinkedIn, deep-learning paper, metadata. | Superseded by the October 2026 refresh. |

## Working Notes

| Date | Status | Note |
| --- | --- | --- |
| 2026-06-16 | Uncommitted | Added this document and first simplification idea. |
| 2026-10-19 | Committed | October refresh: new intro, What I work on, AI in breeding, Tools and code, Talks; stock_dashboard dropped; thesis notes Geno collaboration; metadata moved to timknutsen.no. |
