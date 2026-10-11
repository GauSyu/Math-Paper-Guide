---
name: math-paper-guide
description: "Create or revise mathematical paper reading guides (论文导读), preferably as interactive websites centered on logical relationship diagrams, preserving original terminology. Use for a paper guide, a proof-route map, or an explanation of how a paper's results fit together."
---

# Math Paper Guide

Use a logical relationship diagram as the guide's main explanatory scaffold. Help the reader see how the paper's question, constructions and results connect, then explain those connections. Match the requested language, background and scope; a focused question may need only its relevant subgraph.

## Sources and available capabilities

Work from the supplied paper or an accessible original source. Identify its title or identifier, version and usable content; keep exact section, result, equation or proof-passage locators with the guide. Check the original statements and argument, and make unavailable passages or version differences explicit.

Use available source-reading, mathematical rendering, web-authoring and browser-inspection tools. Continue the supported parts when content or a tool is unavailable, and identify the specific missing passage or unperformed check.

Default to direct reading of the original argument when explaining its key reasoning or making the logical relationship diagram. Reuse a suitable statement/reference index already available for the same source version. Create a new extraction only when the task calls for an inventory of numbered results and explicit references across a whole paper or multiple papers and a suitable extraction tool is available. An ordinary guide does not require that extra inventory. Extracted entries are navigation candidates; establish logical relationships by reading the original passages.

Keep the guide's source inventory and qualifications with its editable materials; a tool's output does not add a mathematical verification status.

## Save and maintain the guide

Save the guide at the requested destination, or in the existing folder for that paper or project. Otherwise use the task's output location. Keep editable sources, diagrams, entry HTML and assets together, and revise the same guide in place with a stable descriptive name.

Record dates and source revisions in the guide's metadata rather than changing its name. Create an additional snapshot or archive only when requested. Preserve the original paper and related manuscripts while preparing the guide.

## Preserve original terminology

**Keep mathematical terms in the paper's original language throughout the guide, including diagram labels and captions. A Chinese guide must not silently replace technical terms with Chinese translations.** Preserve names of properties and constructions, abbreviations, notation, and original result identifiers so the reader can locate them in the source.

Explain the concepts and their role in the requested narrative language around the original terms. For example, keep `faithfully flat` and `étale morphism` as written in an English source while explaining their use in Chinese. If the user explicitly requests a translation or supplies an approved equivalent, show it alongside the original term and keep the original visible in the corresponding diagrams. When equivalence or usage is uncertain, retain the source wording and explain the specific uncertainty rather than inventing a translation.

## Research context and cited inputs

Explain the relevant prior work: where the question comes from, which results or methods the paper inherits, and what it changes or extends. Keep this context bounded to the requested argument. Distinguish the author's account of prior work or claimed novelty from comparisons actually checked in the sources; do not infer historical priority or novelty from an incomplete search.

Classify important citations by their actual role: an imported result, construction or proof method; comparison or inspiration; or background and notation. Include an external input in the logical diagram when the original argument uses it, with the cited work's identity, original result identifier and concrete use. Explain contextual prior work in the surrounding prose or clearly distinguish contextual links from proof-use arrows. A citation occurrence alone does not establish a proof dependency.

For an imported result, prefer a usable existing local copy or full text of the relevant version. Work from the supplied or accessible original sources. Check the result's exact statement, hypotheses and notation against the place where this paper uses it. Give locators for both the invocation and the cited result. If only the invocation has been read, state that the external statement or applicability remains unchecked.

When external theorem discovery or dependency retrieval is needed, make a bounded search of accessible original literature using the required mathematical formulation and hypotheses. Available theorem-search services may supply candidates, whose statements and proof roles still require source checking. A service failure or empty result does not establish absence, independence or novelty. Resolve a known reference's uncertain identity or citation record against authoritative bibliographic records before citing it.

## Build the logical relationship diagram

- Choose the main goal and the constructions, reductions and intermediate results that explain the requested argument. The goal may be a theorem, proposition, corollary or construction. Expand a dense overview into focused diagrams only when that helps explanation; retain node identities across the overview and local views.
- Give important result nodes their original identifiers and a short faithful description using the original terminology. Add an object, definition or hypothesis node when it makes a connection intelligible. Show exact statement fragments when needed to clarify a condition or conclusion.
- Turn an unnumbered intermediate assertion into a Claim node only when it helps explain an important connection. Give it a stable local identifier tied to its parent argument and exact source passage, and mark it as guide-added; do not present it as an original paper label.
- Distinguish jointly needed inputs from alternative proof routes. Preserve case branches and induction base/step where they matter; keep different proof variants separate. Represent a shared input once in the overview, or clearly reuse its identity across local diagrams, so tree layout does not hide a shared dependency.
- Trace important connections to exact original passages and check how the required hypotheses are supplied. Extracted references are navigation candidates: comparison, notation and restatement references may have no proof role. Include connections expressed in prose when the source supports them.
- Orient arrows consistently as **input → result or step using it**, and give a short caption explaining that convention. These arrows describe the author's argument under its hypotheses. Label central edges with their concrete role, such as constructing a map, establishing well-definedness, identifying a kernel, obtaining finiteness or applying descent.
- Use visual distinctions for mathematical roles, and keep materially uncertain connections visibly qualified. Put source details beside the corresponding explanations so they remain available without dominating the main figure.

Prefer a readable Mermaid diagram for a small static relation map. Choose another suitable rendering method when the requested medium or layout requires it. Keep labels short, crossings limited and any mathematical notation legible.

## Explain along the diagram

Introduce the mathematical question, objects and relevant prior work briefly, show the main diagram early, then walk through its important connections. Explain what each input supplies, what obstacle it resolves and how several inputs combine at a key step. Put source locators beside the relevant explanation so the reader can return to the actual statement or proof passage. Use formulas, examples and local detail where they help the reader follow that route. Distinguish the author's explicit motivation from a reconstructed explanation when the distinction affects understanding.

For a difficult connection, return to its exact proof passage through the available source-reading workflow and expand just the needed definitions or intermediate steps. Carry the same node identifiers and original terms into that local explanation. Adapt any suggested reading route to whether the reader wants to work backward from the goal or forward from its prerequisites.

Geometric sketches can support particular nodes or maps when useful. State what they depict (for example a real locus, a schematic model or an analogy), and check their mathematical relationships. Use an available image-generation capability for a requested generated illustration; exact formulas, arrows and parameter plots need an appropriate controlled drawing method.

Adapt any reading-order advice to the reader's purpose rather than imposing a fixed outline or a complete paper map.

## Interactive delivery

For a saved full guide, default to a local standalone interactive HTML paper-guide website; honor an explicitly requested format. ChatGPT Sites private hosting is supported only when the user explicitly requests that delivery and the capability is available. A request to create, preview or save a website does not itself request hosting. Organize the site around the paper or series and its arguments. Use visual design, site navigation and interaction to support mathematical understanding and source access. Do not impose a learning-platform structure of curricula, learning tasks or progress management unless the user asks for it. A focused conversational explanation may remain a small diagram and text. When creating a website, read [interactive guide delivery](references/interactive-guide.md). Use interaction to navigate between the logical diagram, its explanations and source passages, keeping the same mathematical identities and qualifications throughout.

## Check and deliver

Before delivery, check important node identities, source-backed connections, hypothesis use, citation roles, external result locators, arrow direction, original terminology and agreement between the figures and their explanations. Check that guide-added Claims remain distinct from original labels and that joint inputs and alternative routes are not confused. Report only the verification actually performed. Render or preview the diagrams when the medium permits; inspect exported figures for readable labels and unclipped content. A diagram or an extraction result does not itself certify the proof.

Deliver the figures, explanations and editable sources together in the requested format. For a saved website, include the entry HTML and assets and follow the save-and-maintain rules above.
