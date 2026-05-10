# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is an "Awesome List" style repository for **Human-View Video Understanding** research, hosted at `lxtGH/Awesome-HumanView-VideoUnderstanding`. It is a curated list of papers/resources, not a software project.

At present the repository contains only:
- `README.md` — currently just the title; this is the primary deliverable and is where the curated list belongs.
- `paper/arxiv.pdf` — a source paper that likely seeds the list's taxonomy and entries.

## Working in this repo

- There is no build, lint, or test tooling. Do not invent commands or scaffolding (package managers, CI configs, etc.) unless the user explicitly asks.
- The expected workflow is editing `README.md`: adding paper entries, sections, tables, and links. Follow conventions of established awesome-lists (grouped sections, paper title + venue/year + links to arxiv/code/project page) unless the user specifies a different structure.
- `paper/arxiv.pdf` is a reference document. Read it (via the `Read` tool, which supports PDFs) when the user asks to seed sections, extract a taxonomy, or pull citations from it — don't guess at its contents.
- The repository is published on GitHub; Markdown should render correctly on github.com (GFM, no HTML hacks unless needed).
