# Contributing

Thanks for helping keep this list short and high-signal. Please read this before opening a pull request.

This is a curated awesome-list of **playable browser games**. Match the style and legends already in [README.md](README.md). Do not invent games, tweets, or launch dates.

## Games only

Entries must be **actual playable games** people can have fun with.

**Do not add:**

- Tech demos
- Shader showcases
- World flythroughs
- “Presentations” or cinematic scenes with no real gameplay

If someone cannot play it (controls, goals, challenge, fun), it does not belong here — even if it looks impressive.

## High quality / well-loved

Prefer games with strong public reception. Practical bar used by maintainers:

- Discovery via X/Twitter with roughly **600+ likes**
- Positive comments (people enjoying *playing*, not just the visuals)
- A **working playable link** that still loads when you check it

Skip dead links and games that are not landing with players.

## Source tweet

Every entry needs a primary discovery **Source** tweet.

- Prefer high-engagement posts (quiet first posts are usually the wrong Source)
- `@threejs` amplifies are useful Source links
- Write it exactly like the README: `Source: [Tweet](https://x.com/…)`
- The Source tweet is the discovery post. It is **not** always the earliest announcement (see Possible launch)

If you cannot find a real Source tweet, do not add the game. Do not fabricate tweet URLs.

## Possible launch date

Each entry includes an **estimate** with a tilde:

`Possible launch: ~YYYY-MM-DD`

- Base the date on the **earliest public tweet** that announces or shares the playable game
- Keep the tilde (`~`); these are estimates, not exact ship dates
- Source tweets may be later high-engagement posts, so Possible launch can be earlier than the Source tweet’s date

Do not guess a date with no tweet to back it.

README legend (do not reword it in the README):

> Possible launch dates (`~YYYY-MM-DD`) are estimates from the earliest public tweet found that announces or shares the playable game. Source tweets may be later high-engagement discovery posts.

## Originals marker

- **Original** games (not remakes or clones of a classic) use the ✨ emoji and go under `### Originals`
- **Remakes / inspired-by** name the classic (`Inspired by …`) and go under `### Remakes / inspired-by`

README legend (keep this wording):

> ✨ = Original game (not a remake/clone of a classic)

## Category ordering (remakes)

Under `### Remakes / inspired-by`, order by category. Use these groupings, in this order:

1. **Racing**
2. **First-person shooters**
3. **Others** — leftover genres that do not warrant their own section

Follow the heading names already in the README when they exist (`#### Racing`, `#### First-person shooters`, `#### Others`). Put a remake in the matching category. Use **Others** instead of creating a one-game heading.

Originals stay in a single `### Originals` list.

## Entry shape

Keep the list concise. One bullet per game, in this order:

1. Name linked to the **play URL**
2. Inspired-by classic **or** ✨ Original
3. Short features (semicolon-separated; no essays)
4. `Possible launch: ~YYYY-MM-DD`
5. `Source: [Tweet](…)`

**Remake (schematic — placeholders only):**

```markdown
* [Game Name](https://example.com/play) - Inspired by Classic Title. Short features. Possible launch: ~YYYY-MM-DD. Source: [Tweet](https://x.com/handle/status/…)
```

**Original (schematic — placeholders only):**

```markdown
* ✨ [Game Name](https://example.com/play) - Original short description. Short features. Possible launch: ~YYYY-MM-DD. Source: [Tweet](https://x.com/handle/status/…)
```

Copy punctuation, field order, and legends from existing README entries. Do not add extra badges, tables, or screenshots.

## How to contribute

1. Fork this repository and branch from the default branch (`main`).
2. Edit [README.md](README.md). Follow the criteria and formatting above.
3. **Verify the play link still works** before you open a PR.
4. Confirm the Source tweet is real, and that Possible launch is estimated from the earliest playable-game tweet you found.
5. Open a pull request that says why the game meets the quality bar (likes, comments, working link).

PRs that invent games or tweets, add non-games, or ignore README style will be rejected.
