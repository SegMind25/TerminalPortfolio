# SegMind25 — Simple Terminal Portfolio

A small blue terminal with plain text output and a command prompt. No external
libraries, cards, navigation tabs, games, audio, boot animation, or visual effects.

Open `index.html` directly in a browser. No build step or network access required.

## Commands

- Portfolio: `about`, `skills`, `projects`, `contact`, `socials`.
- Links: `gaming`, `coding`, `youtube`, `tiktok`, `discord`, `github`.
- Navigation: `ls [-la] [path]`, `cd [path]`, `pwd`, `tree`.
- Virtual files: `cat [file]`, `touch [file]`, `mkdir [path]`, `rm [-r] [path]`.
- Utilities: `help`, `echo`, `history`, `date`, `whoami`, `neofetch`, `clear`.
- `home` clears the output and shows the welcome message; `exit` also resets the path.
- `resetfs confirm` restores the original virtual files.

File operations only affect an in-memory simulation and reset on reload.
`cat resume` shows the profile; no downloadable resume has been supplied.

Tab completes commands and paths. Arrow keys navigate the last 50 commands.
Ctrl+L clears output; Ctrl+C cancels input; Escape dismisses suggestions.

The original SegMind25 biography, skills, project descriptions, social links,
and virtual file contents are retained. The layout adapts to mobile screens.

MIT License. © 2026 SegMind25.
