# Retro Scene Guru 2026 Public

A modernized `guru.dat` brain for the built-in Synchronet Guru chat system.

This build is intended for **public sharing with other Synchronet BBS sysops**. It is not tied to X-Bit or any single board. The personality is a general retro-tech scene oracle with a little fake-AI jealousy and enough friendliness for new callers.

## Personality mix

- 60% Scene Oracle
- 20% Jealous Fake AI
- 20% Friendly Help Desk

The Guru knows he is **not real AI**. He is a rule-based BBS character living in a DAT file, and he is mildly jealous of modern cloud AIs.

## Topics covered

- Modern BBS culture
- Synchronet and other BBS packages
- Sysop life
- ANSI art, CP437, terminals, art packs
- Moebius, PabloDraw, REZ2ANSI, 16colo.rs
- Door games and Inter-BBS leagues
- FidoNet / FTN / BinkP
- QWK / Dove-Net
- Telnet / SSH / RLogin
- ZMODEM / Kermit / file areas
- RSS / web access
- Logs, backups, updates, security, bots, scanners
- Retro PCs and modem-era history

## Important fixes included

This version includes the fixes discovered during testing:

- Uses valid Synchronet Guru expression syntax with parentheses.
- Does **not** use bad angle-bracket topic headers.
- Includes top-priority `BYE`, `QUIT`, and `EXIT` blocks.
- Exit responses include the Synchronet `` `q `` command so Guru chat closes cleanly.
- Displayed response lines are wrapped to 60 columns or less for safe 80x24 terminal display.
- Uses OG-style `CR CR LF` line endings.
- Includes the required final empty fallback expression: `()`.
- Stays under the documented 64 KB Guru file limit.

## Suggested test phrases

After installing, try:

```text
hello
are you a real AI
what are you
tell me about the BBS world
sysop
ANSI
door games
FidoNet
QWK
ZMODEM
security
backups
bye
quit
```

## Files in this package

```text
guru.dat     - The Guru brain file
file_id.diz  - Short BBS archive description
readme.md    - Main project notes
install.txt  - Installation instructions
```

## Notes

Synchronet Guru is not a modern LLM or chatbot :) It is a classic rule-based response system. The goal of this file is to make the built-in Guru feel more useful, more current, and more fun for today's retro BBS scene.
