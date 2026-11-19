# motovlog-editing-skill

A Claude skill for editing motovlogs (motorcycle ride videos) in the nepShoot style. It plans edits, builds cut lists, and reviews drafts.

What it covers:
- Short (5-10 min) and long (up to 30 min) 16:9 ride video templates: hook, logo, title, preview clips, route map, main part, ending
- The 1-minute vertical overview for TikTok, YouTube Shorts and Instagram Reels
- Voice parts are never cut, long clips are cut into pieces for a cinematic feel
- Titles in Nepali and English, subtitles in English
- Route map check when there is no GPS track
- Audio and wind noise, B-roll, color, export, and a final checklist

## Install in Claude Code

The repo root is the skill folder, so one clone installs it.

Windows (PowerShell):

```
git clone https://github.com/Shankarman/motovlog-editing-skill "$env:USERPROFILE\.claude\skills\motovlog-editing"
```

macOS or Linux:

```
git clone https://github.com/Shankarman/motovlog-editing-skill ~/.claude/skills/motovlog-editing
```

Start a new Claude Code session afterwards. Ask for motovlog editing help, or run it by name as /motovlog-editing.

## Update

Windows (PowerShell):

```
git -C "$env:USERPROFILE\.claude\skills\motovlog-editing" pull
```

macOS or Linux:

```
git -C ~/.claude/skills/motovlog-editing pull
```

## Files

- `SKILL.md` - the skill itself
