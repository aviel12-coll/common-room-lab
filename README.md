# Common Room Lab

An interactive, browser-only simulation of people sharing a kitchen-lounge. Each person talks, moves and works through everyday jobs (making tea, watering the plant, setting the table and so on). You can give each of them a different mix of difficulties and watch how their behaviour changes:

- **Spatial perception**: misjudges where things are and how much room there is around furniture
- **Visual field (left side)**: tends not to notice things on the left
- **Movement**: slower, less steady walking; hand tasks take longer and can slip
- **Attention**: pulled off task by voices and things around the room
- **Language**: word-finding pauses, swapped words, misunderstanding others
- **Planning**: steps out of order or skipped, then backtracking
- **Memory**: losing the goal, repeating steps, forgetting names

The page also has room supports (labels, a checklist, a quiet room, clear walkways, adapted tools), a perception overlay, a "compare everyone on one job" mode, an event log and a scoreboard.

## Brain detective (game mode)

Press **Start a case** and one person in the room gets a hidden difficulty. Their difficulty settings, log tags and overlay are hidden. Watch how they behave compared with the two people without difficulties, give them jobs to test your ideas, then choose which brain area you think is involved:

| Difficulty | Brain area in the game |
|---|---|
| Spatial perception | Parietal lobe |
| Visual field (left side) | Occipital lobe (visual cortex) |
| Movement | Cerebellum |
| Attention | Thalamus |
| Language | Broca's and Wernicke's areas |
| Planning | Prefrontal cortex |
| Memory | Hippocampus |

A correct first guess scores 3 points, the second 2, then 1. Solving a case shows a large illustration of the brain with that area highlighted, what it does, and the clues the person showed in the room. Areas you find are collected in a brain atlas you can reopen. Cases get subtler as you go.

## Run it

Open `index.html` in any modern browser. There is no build step, backend, database or API key. Everything runs locally from rules and dialogue templates. The only network requests are for the Google Fonts, and the page still works without them.

## Disclaimer

These are simplified teaching models, not clinical descriptions of any condition. Real people adapt, use strategies, and vary from day to day.
