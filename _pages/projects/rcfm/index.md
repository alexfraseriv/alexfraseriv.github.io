---
layout: default
title: "RCFM"
permalink: /projects/rcfm/
description: "Rose City Friendly Manager — the IRL-friendship competition tracker. Now superseded by theForm."
---

# RCFM

**Rose City Friendly Manager**

---

## Status: replaced by [theForm](https://theform-6bea6.web.app)

RCFM started as a Streamlit prototype, then a React/Next rebuild, before becoming a proper cross-platform app. The current incarnation is **theForm** — a Flutter app for iOS, Android, web, and macOS that tracks FIFA/EA FC games, runs deep player analytics, and uses Gemini to auto-generate goal highlights from YouTube uploads.

→ **[Open theForm ↗](https://theform-6bea6.web.app)**

---

## Original concept

A tool to facilitate competition amongst IRL friends — leaderboards, head-to-head, season management, and just enough structure to make casual gaming feel like a league.

## What theForm adds on top

- **AI highlight generation:** paste a YouTube link of a recorded game; Gemini watches the video and timestamps every goal.
- **Head-to-head comparison:** stats side-by-side across any subset of players, with charts.
- **Format-aware analytics:** 1v1 vs 2v2 splits, win-rates by club, performance trends over a season.
- **Custom tactics repository:** the "Tadić" page for sharing in-game formations.

Built with Flutter, Supabase (auth + data), and the Google Gemini API.
