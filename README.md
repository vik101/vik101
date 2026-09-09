# Vikram Tomar

Software engineer in London. I build the platforms other people work on top of.

**Now:** Head of Deployed Engineering at [Sammy Labs](https://www.sammylabs.com) (YC). I lead the team that takes a signed customer from contract to live: on-site onboarding, integration with whatever legacy system they actually run, and the firefighting in between.

**Before:** Technical lead on **Spectrum** at JPMorgan Asset Management, the Electron desktop platform that 9,000+ employees open every morning. Rebuilt it from a .NET app that took minutes to load into one that takes seconds. Owned time-to-first-paint, the Bridge API for inter-app communication, cross-monitor drag and drop, and the first AI features inside it. Earlier: first graduate cohort at King, where I built the tooling that shipped Candy Crush into 50+ languages. BEng Computing, Imperial College London.

## What I'm building in public

### [wsx](https://github.com/vik101/wsx)

Run several coding agents in parallel, each in its own git worktree, each in its own tmux tab. One bash script over `git` + `tmux` + `fzf`.

```
 ┌──────────────────────────┬───────────────┐
 │                          │   lazygit      │
 │   claude  (50%)          ├───────────────┤
 │                          │   yazi         │
 └──────────────────────────┴───────────────┘
        window/tab name = the worktree
```

- Bare `wsx` is a control panel over every workspace, active and archived, grouped by repo.
- Pane borders show `● claude working…` or `⛔ needs input`, so across six tabs you can see which agent needs a human.
- Archive, don't delete. Branch and notes survive, anything restores.

I use it daily in Ghostty with Claude Code. It exists because I kept running three agents in one checkout and watching them trample each other.

### [skinai](https://github.com/vik101/skinai)

Skiniq: an AI dermatologist for men. Face scan via Haut.AI, personalised routine, PDF report to your inbox. A solo product from research to pricing to code.

## Stack

TypeScript, React, Electron, Java, Node. AWS. Claude Code, Cursor, tmux.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/vikramtomar)
