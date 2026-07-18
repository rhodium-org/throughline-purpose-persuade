# Purpose — Persuade — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates
it in CI. The prose headings are hand-owned — everything between `tl:*` markers is
injected from the YAML items, so the published spec can never drift from the graph.

This source is the **genre / purpose axis** for one purpose: **persuade**. It governs
what the writing is *for* — leading the reader to accept a claim or take an action of
their own informed choice, honestly — not readability, spelling, punctuation,
tone/register, medium or brand voice, each of which is its own throughline source.
Purpose variants are mutually exclusive: **inform**, **instruct** and **persuade** are
sibling sources and a consumer composes exactly one under the `purpose` namespace.
Every principle is a `user_requirement`; every rule is a `system_requirement` that
`implements` its principle. The throughline UIDs are this source's own and immutable —
a consumer cites a rule as `purpose:SR-0001`.

It carries
<!-- tl:count type == 'user_requirement' -->
5
<!-- tl:end --> principles and
<!-- tl:count type == 'system_requirement' -->
10
<!-- tl:end --> rules.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — Text moves the reader toward a decision or action, honestly** — `intent`, status `approved`

> Persuading means leading the reader to accept a claim or take an action of their own free and informed choice. It suits proposals, recommendations, campaigns and marketing, where the reader needs to be convinced rather than merely informed. Persuasion here never means to mislead: an honest case is the whole point. This axis governs the communicative purpose — claim, evidence, benefit and call to action — not readability, spelling, punctuation or register, each of which is a separate source. Purpose variants are mutually exclusive: a consumer composes exactly one of the inform, instruct or persuade sibling sources.

**source_ref**: TBS Purpose — Persuade
<!-- tl:end -->

## 1. Make the single claim explicit

<!-- tl:item UR-0001 -->
**UR-0001 — Make the single claim explicit** — `user_requirement`, status `approved`

> State the one proposition you want the reader to accept.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Persuade — Clear claim
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0001' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | approved | State the main proposition in one sentence |
| SR-0002 | system_requirement | approved | Keep every section serving that one claim |
<!-- tl:end -->

## 2. Support the claim with honest evidence

<!-- tl:item UR-0002 -->
**UR-0002 — Support the claim with honest evidence** — `user_requirement`, status `approved`

> Back the claim with verifiable evidence, and drop what you cannot substantiate.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Persuade — Evidence
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0002' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0003 | system_requirement | approved | Support each claim with verifiable evidence |
| SR-0004 | system_requirement | approved | Drop any claim you cannot substantiate |
<!-- tl:end -->

## 3. Frame the case around the reader's benefit

<!-- tl:item UR-0003 -->
**UR-0003 — Frame the case around the reader's benefit** — `user_requirement`, status `approved`

> Show what the reader gains, in their terms.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Persuade — Reader benefit
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0003' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0005 | system_requirement | approved | Frame the case around what the reader gains |
| SR-0006 | system_requirement | approved | Make the benefit concrete, not a superlative |
<!-- tl:end -->

## 4. Meet the strongest objection honestly

<!-- tl:item UR-0004 -->
**UR-0004 — Meet the strongest objection honestly** — `user_requirement`, status `approved`

> Acknowledge the main counter-argument or risk rather than hiding it.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Persuade — Objections
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0004' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0007 | system_requirement | approved | Acknowledge the strongest objection openly |
| SR-0008 | system_requirement | approved | Answer the objection, or concede it fairly |
<!-- tl:end -->

## 5. Ask for one clear next action

<!-- tl:item UR-0005 -->
**UR-0005 — Ask for one clear next action** — `user_requirement`, status `approved`

> Tell the reader exactly what to do next and make it easy.

*Derives from:* INT-0001

**source_ref**: TBS Purpose — Persuade — Call to action
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0005' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0009 | system_requirement | approved | Ask for one primary action |
| SR-0010 | system_requirement | approved | Remove friction from that action |
<!-- tl:end -->
