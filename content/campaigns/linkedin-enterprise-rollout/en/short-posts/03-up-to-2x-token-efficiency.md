# Post 03: up to 2x token efficiency through query-driven context

## Copy

One of the most underrated questions in AI engineering tooling is:

how much noise are you dragging into the prompt?

After moving from a static context pack to query-driven retrieval, we saw a very practical effect.

In a set of internal benchmark scenarios, token consumption went down by up to 2x on typical engineering tasks.

Why:

- we stopped sending everything “just in case”
- we separated human-authored maps from machine-generated index layers
- we retrieved only relevant docs, code surfaces and memory
- we added cheap local retrieval with `rg` and optional `ast-grep`

The important part is not just smaller prompts.
The important part is more precise context.

And that usually helps quality as much as cost.

## Image Prompt

Create a LinkedIn illustration about reducing token waste in AI developer tooling.
Show a bloated noisy prompt contrasted with a compact relevant context pack containing task, docs, code, memory and search hits.
Style: mature engineering infographic, light background, deep green, graphite and muted blue.
Format: vertical 4:5.
