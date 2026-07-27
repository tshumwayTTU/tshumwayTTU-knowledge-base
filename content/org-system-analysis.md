---
title: AniList — Organizing System Analysis
date: 2026-07-26
---

# AniList: An Analysis of Its Organizing System

AniList is a public platform for tracking and discovering anime and manga.
It works as both a database and a personal list manager.

---

## Primary Resources

The main resources are anime and manga entries. Each title has its own page
with metadata: format (TV, Movie, OVA), episode count, airing status, genre
tags, and a description. That is the core of what the system organizes.

Beyond the titles, there are character profiles and staff pages for voice
actors and directors. Each of those is its own page that connects to other
entries. Users also add resources of their own: personal lists, scores, and
written reviews, all attached to specific titles and visible to others.

---

## Primary Interactions

Three things drive how people use AniList:

- **Tracking**: Users log what they are watching, completed, or planning to
  watch, episode by episode. Titles are organized by status: Watching,
  Completed, Planning, Dropped, or Paused.
- **Discovery**: The Browse page lets you filter by genre, year, season,
  and format at the same time. Sections like *Trending Now* and
  *Popular This Season* support browsing without a specific title in mind.
- **Evaluation and community**: Users score titles, write reviews, and
  follow others to compare lists and activity.

Tracking is the main use case. The list interface has the most options: filters,
sort controls, and view modes. That shows where the system puts its focus.

---

## Classification System

AniList uses a faceted classification system. Titles are not organized
into a single hierarchy. Instead, multiple attributes are assigned to each
entry and can be filtered in combination:

| Facet | Examples |
|---|---|
| Format | TV, Movie, OVA, ONA, Special |
| Genre | Action, Romance, Fantasy, Slice of Life |
| Season / Year | Fall 2024, Winter 2025 |
| Status | Finished, Airing, Not Yet Released |
| Country | Japan, China, South Korea |

This works for the audience because anime fans rarely search through a
single filter. Finding a completed fantasy TV show from 2023 means
cutting across format, genre, status, and year at once. A strict hierarchy
would not handle that without a lot of duplication.

> The faceted system fits because it matches how fans actually look for shows, not by a single folder, but by a combination of what something is and what it feels like.

It can get noisy when a title carries a lot of genre tags, but that is
more a reflection of the medium than a problem with the system.

---

## Relationships Between Resources

AniList represents relationships in a few different ways.

The most direct is the Relations section on each entry page. It uses
typed, labeled links (*Source*, *Prequel*, *Alternative*, *Sequel*) to
connect related works. *Mushoku Tensei: Jobless Reincarnation Season 3*
links to its original light novel as the Source, its previous season as
the Prequel, and a manga spin-off as an Alternative. The labels matter.
They tell you not just that two things are connected, but how and in
which direction, which helps when figuring out where to start a franchise.

The Characters and Staff tabs take it further. A voice actor's
page lists every role they have played across the entire database. That
lets you follow a voice actor or director across everything they have
worked on, not just one title.

Community stats add a third layer. Rankings like *#44 Highest Rated
All Time* and score distributions pulled from all users connect titles in
ways the system never explicitly drew. The system did not create those connections. They come from how people actually use it.

---
