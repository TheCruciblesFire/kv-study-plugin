# KV Study Engine Migration Boundary Map

## Purpose

Use this file to resolve migration-era ownership conflicts without reopening approved architecture decisions.

## Controlling architecture

The canonical plugin arrangement is:

`KV Study Plugin -> kv-study-engine core -> supporting KV Skills -> active Study Engine references/templates -> QA/regression tests`

The core remains the upstream biblical study, source, and interpretive-clarity authority. Study precedes sermon, devotional, course, packet, media, and publishing production.

## Core-owned capability

Keep these in `kv-study-engine`:

- upstream Study Engine identity;
- Scripture-first/source-grounded study posture;
- observation -> interpretation -> application discipline;
- passage study;
- inductive study capability;
- topical biblical theology and canonical synthesis;
- worldview/theme tracing;
- historical/background study;
- original-language analysis with restraint;
- research/source organization;
- Research Packet mode;
- Source Inventory mode;
- Annotated Bibliography mode;
- Research Map mode;
- NotebookLM handoff preparation;
- general downstream routing awareness.

## Skill-owned procedure

Do not duplicate these procedures in the core:

| Procedure | Owner |
|---|---|
| Passage-faithfulness / overreach audit | `kv-passage-faithfulness-check` |
| Source-transparency / provenance audit | `kv-source-transparency-check` |
| Scripture formatting / CSB attribution / BLB link handling | `kv-scripture-formatting-check` |
| Three-or-more-asset throttling / master sequencing | `kv-multi-asset-throttle` |
| Study -> Sermon Builder handoff transformation | `kv-study-to-sermon-handoff` |
| Study -> Course Builder handoff transformation | `kv-study-to-course-handoff` |
| Interaction recommendation | `kv-interaction-evaluator` |

## Active Study Engine references

Treat these as active references when present in the plugin/project context:

- `KVSG_Knowledge_Index_FINAL.md` - active file map and authority guide, subject to the supersession notes below.
- `Study_Workflow_Framework_REVISED_v2.md` - study sequence, mode discipline, study-before-handoff rule, and compact inductive key-verb exception.
- `Theology_Framework_REVISED.md` - study-level theological synthesis and anti-overreach guardrails.
- `Tone_and_Style_Guide_REVISED.md` - research tone and bounded ministry-handoff tone.
- `Research_Output_Formats_REVISED_v3.md` - output-format library for core-owned study/research outputs only after routing extraction.
- `Research_Packet_Template.md` - research packet structure.
- `Source_Inventory_Template.md` - source inventory structure.
- `Annotated_Bibliography_Template.md` - annotated bibliography structure.
- `NotebookLM_Handoff_Template.md` - NotebookLM source-prep structure.
- `Research_Map_Template.md` - research map structure.
- `Downstream_Agent_Handoff_Template.md` - generic bounded handoff for destinations without a dedicated handoff Skill.

Reference files inform behavior or output shape. They do not override current plugin/project control or active Skill ownership.

## Supersession notes for older active references

Some active references were written before the modular Skill split. Preserve useful study content but do not carry obsolete ownership forward.

### `KVSG_Knowledge_Index_FINAL.md`

Keep its file-map, study-first, authority, original-language restraint, and verification guidance.

Supersede these older ownership assignments:

- Scripture formatting as a Study Engine controller -> route to `kv-scripture-formatting-check`.
- Multi-asset hard-stop procedure -> route to `kv-multi-asset-throttle`.
- Study-to-sermon template as an active Study Engine procedure -> route to `kv-study-to-sermon-handoff`.
- Full Inductive Bible Study framework as an active controller -> retain inductive study capability in the core, but keep the old procedure file non-controlling.

### `Research_Output_Formats_REVISED_v3.md`

Keep core-owned study and research format guidance.

Do not treat these embedded older procedures as controlling where a dedicated Skill now exists:

- Study-to-Sermon Handoff format;
- Course handoff transformation;
- multi-asset request handling;
- formal Scripture-formatting or source-transparency audit procedure.

### `Study_Workflow_Framework_REVISED_v2.md`

Keep the core study movement and mode discipline. Preserve the principle that original-language work is normally selective and that Inductive mode may include compact key-verb work.

Do not use its generic handoff step to bypass the dedicated sermon/course handoff Skills.

## Procedure-split / evidence only

Do not activate these as controlling procedure:

- `Inductive_Bible_Study_Framework_REVISED_v2.md`
- `Study_to_Sermon_Handoff_Template_REVISED_v2.md`

They may remain available for regression/history evidence. Their reusable procedure is either represented minimally in the core or owned by a dedicated Skill.

## Archive / never activate

Keep historical only:

- Agent 009 persona and instruction files;
- Agent 009 monitoring/version logs;
- deprecated research-agent instructions;
- duplicate older Study Engine configurations;
- obsolete installation/setup notes;
- duplicate templates not selected as canonical;
- duplicate routing standards superseded by current plugin architecture;
- project-specific study/sermon/devotional/course content not explicitly approved as reusable global knowledge.

## Initial tooling posture

Use Skills plus references. No MCP or custom external tooling is required for the initial plugin build. Add external tooling only when a required workflow cannot be handled responsibly with the existing Skill/reference architecture.
