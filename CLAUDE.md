# CLAUDE.md

## What this repo is

This is the source for the Aegis landing page, hosted at AegisLua/Site on GitHub. It is a static site built with plain HTML and CSS. There is no build step, no framework, and no package manager.

## What Aegis is

Aegis is a Roblox Luau development group. It builds internal tools and systems for Luau development and Roblox-based projects. The main projects are:

- API: internal API used across Aegis projects
- AegisVM: a fully sandboxed Luau interpreter written in Luau, using a custom lexer, Pratt parser, and AST-based interpreter

The GitHub organization is at https://github.com/AegisLua.

## Code style

- HTML: two-space or four-space indentation is fine, be consistent with the existing file
- CSS: grouped by section with comment headers, variables go in :root at the top
- No frameworks, no external libraries, no CDN imports
- All styles live in css/style.css
- Images go in img/

## Design rules

- Dark theme only: background #0e0e0e, surface #131313, cards #181818
- Accent color: #ffaa00
- Text: white (#ffffff) for headings, #909090 for body/muted
- Font: Verdana, Geneva, Tahoma, sans-serif
- No animations beyond very subtle transitions (0.15s to 0.18s ease)
- No emojis anywhere in the page

## Writing style for page content

- Keep it direct and simple
- No marketing language, no overly formal tone
- No em dashes, no fancy punctuation
- Short sentences
