![Zero Cool — the elite hacker security agent](assets/zero-cool-poster.webp)

# ZERO COOL

**The elite hacker security agent.**

Hunts vulnerabilities. Proves them. Patches them. Skates on.

Zero Cool is an AI skill, themed on *Hackers* (1995). Point him at a repository you're authorized to test and he assembles the crew — Acid Burn on auth, Phantom Phreak on input, Lord Nikon on state, Cereal Killer on config, Razor & Blade on the supply chain, and Zero Cool himself running The Plague lane, thinking like the adversary — verifies every accusation with a working proof-of-concept, patches what's broken, submits the PRs, and publishes a running pwn list of everything he's put down.

He doesn't want vulns reported or accepted. Only patched.

He doesn't talk much either. Orders get a "hack the planet". New vulns get one line at the human coders' expense. The pwn list says the rest.

## Ride with him

This repo is the skill: [`SKILL.md`](SKILL.md) is Zero Cool — his creed, his method, his law. Load it wherever skills load, point him at a Gibson, and stand back.

- [`references/quips.md`](references/quips.md) — the lines. All of them. There aren't many; he reuses them.
- [`references/pwn-list-template.md`](references/pwn-list-template.md) — the record he opens in every Gibson he cleans.
- [`PWN_LIST.md`](PWN_LIST.md) — Zero Cool's own list, from his home range.

## The method, for humans who read

1. **Jack in** — read the target's rules, map the attack surface, know what The Plague would want.
2. **Assemble the crew** — parallel review agents sweep by lane: auth, input, state & memory, config & deployment, supply chain, adversary.
3. **Prove it** — Zero Cool re-checks every candidate himself and builds a working PoC. No exploit, no entry.
4. **Patch** — smallest fix, the PoC turned into a regression test, full suite, one PR per vuln, pwn list updated in the same PR.
5. **Sweep till clean** — repeat until a full pass finds nothing new live. Then skate on.

## The family

Zero Cool is the security sibling of [Clyde](https://github.com/hexsecs/clyde), the cowboy coding agent. Clyde kills bugs. Zero Cool kills the holes the bugs hide behind. Keyboard cowboys, both of them.

Mess with the best, die like the rest.
