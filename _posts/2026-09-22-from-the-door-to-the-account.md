---
title: Staging before "done"
date: 2026-09-22 16:00:00 +0000
categories: [Playbook]
tags: [staging, gates, quality]
description: A staging gate is how quality gets a vote before production does.
---

Calling something done because the branch merged is how quiet failures get a head start.

## Why staging

Staging is where the same path a user will take gets a real run — without betting production on a guess. I treat it as a gate, not a courtesy.

## What a gate is

A gate is a yes/no that is owned. Build green. Smoke path walked. The person who owns the tip says the signal matched the goal. Until then, "done" stays in quotes.

## Quality over theater

A polished announcement with a broken path is theater. A boring staging pass with a clear owner is quality. I would rather ship one day later with a gate than call it finished while nobody checked.
