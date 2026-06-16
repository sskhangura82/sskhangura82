# Dr. Sarwinder Khangura

**Internal Medicine physician. AI governance builder.**

I build tools that make AI-built products reviewable before release.

AI can generate apps, content, and workflows in minutes. But in fields where being wrong matters — medicine, law, finance, education — working code is not enough. The product also makes claims, gives guidance, and may affect real decisions.

Most AI builders help you create. I'm building the review layer: claim extraction, risk classification, expert review, release gates, and an Authority Manifest showing what was reviewed.

## What I'm working on

**Governed Builder** — extracts claims from AI-built products, classifies risk, routes expert review, gates release, and produces an Authority Manifest.

**Evidence Support Review** — the next layer: gathering sources, extracting evidence spans, assessing whether evidence supports a claim, and presenting the case to the expert.

**The core insight:** A source is not evidence. Evidence is not judgment. Judgment belongs to the qualified expert. The manifest proves what happened.

## The three-layer model

1. **Source existence** — does the source exist? *(machine checks)*
2. **Evidence assessment** — does the source support the claim? *(machine assists)*
3. **Expert judgment** — is the claim appropriate for the intended context? *(qualified human decides)*

Medicine has a mature version of this separation through evidence-to-decision frameworks like GRADE. I'm applying the same principle to AI-built products.

## Projects

| Project | What it does |
|---|---|
| [governed-builder](https://github.com/sskhangura82/governed-builder) | Claim extraction, risk classification, release gate, Authority Manifest |
| [agent-factory](https://github.com/sskhangura82/agent-factory) | Governance doctrine, agent specs, mission contracts, research |
| [cliniccalc](https://github.com/sskhangura82/cliniccalc) | Clinical calculator proof app with governed claims |
| [heydoc-site](https://github.com/sskhangura82/heydoc-site) | Experimental clinical source-pack research; not in clinical use |

## Background

Practicing Internal Medicine physician in California. I build in evenings and weekends using AI tools. Every health claim in my governed apps stays Draft until reviewed by a qualified human.

This project is also dogfooding the problem: AI helps build the software, and Governed Builder governs what the software claims.

Views are my own.
