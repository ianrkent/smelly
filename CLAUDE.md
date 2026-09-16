# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This repository contains instructions and rules for playing **Smelly Head**, a card game.

## Files

- `rules.md` — the canonical source of truth for the rules; update this first when rules change
- `index.html` — the public-facing website (self-contained HTML/CSS, no build step, no dependencies)

## Deployment

The site is published via GitHub Pages at **https://ianrkent.github.io/smelly/**. Pushing to `main` deploys automatically — no build pipeline.

## Website design notes

- Font: Nunito (loaded from Google Fonts)
- Target audience: elderly users in a retirement village — keep font sizes large (20px+ body), maintain high contrast, avoid small tap targets
- All visuals are CSS and Unicode card suits (♠ ♥ ♦ ♣) — no external images
- When updating rules, keep `rules.md` and `index.html` in sync
