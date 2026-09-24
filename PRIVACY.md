# Driver's Seat — Privacy Policy

Effective 25 September 2026

Driver's Seat ("the plugin") is developed by Damian Boni (Poland). The plugin runs entirely inside your JetBrains IDE, on your computer.

## What the plugin reads
- AI agent session transcripts that Claude Code writes on your computer (by default `~/.claude/projects`, or the folder you set). Only sessions that worked in the open project are used, and only the parts needed to show a change: your prompts, the agent's messages before each edit, and the edits themselves.
- Version-control state of the open project: which files are modified, and commit times, read through the IDE and local `git` commands.
- The current contents of the files that AI agents changed, to locate each change.

## What the plugin stores
- Which changes you marked "I can explain this change" and your "In my own words" notes, in the project's `.idea/workspace.xml` on your computer.
- Plugin settings, in the IDE's configuration folder on your computer.
- With the Pro options you enable: your notes in the commit messages you create, and in `.drivers-seat/decisions.md` inside your project. These go wherever you push your repository.

## What the plugin sends
Nothing. The plugin makes no network requests of its own, calls no AI or LLM service, needs no API key, and includes no analytics, telemetry, crash reporting or advertising. The developer never receives your transcripts, code, prompts, notes or project data.

## Licensing
Licence validation is performed by the JetBrains platform and JetBrains Marketplace under JetBrains' privacy policy. The developer receives aggregated sales reports from JetBrains that do not include any of your project data.

## Third parties
Claude Code and other AI tools are operated by their providers under their own privacy policies. Driver's Seat is not affiliated with Anthropic, PBC.

## Changes and contact
Changes to this policy will be published with a new effective date. Questions: damianboni@gmail.com
