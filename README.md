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

## Pages

- **`index.html`: Brain Detective (the game).** A random person in the room gets one hidden difficulty. Watch them next to two people without difficulties, then:
  1. choose what they find hard (judging space, seeing one side, moving smoothly, staying focused, words, planning, remembering);
  2. click where that lives in the brain on an interactive brain picture.

  The person to watch does every job as a team with Ada. They share one list of steps and each takes the next step that is ready. When one partner gets stuck (forgets, gets distracted, fumbles, can't find something or gives up), they let go of that step and the other one takes it over, so the job still gets finished. A dotted line links the two partners.

  A correct answer shows the area glowing and labelled, with the clues the person gave. Each step scores 2 points on the first try and 1 on the second.
  - **Add things to the room:** a TV, radio, cat, birthday cake, fish tank, flowers or piano. Pick one and click a free spot on the floor, or put the TV, radio, cake, fish tank or flowers on the table or coffee table. People nearby react, and conversations near it turn to it ("Whose birthday is it?"). The TV and radio make noise that distracts people with attention difficulties, and the cat wanders around. Click a thing you added to remove it.
  - **Click a person to see their brain.** The affected area is marked with a pulsing red symbol. People without difficulties show no marks; the person to watch stays hidden ("?") until you solve the case. After solving, use "Back to the room" to click them.
- **`lab.html`: the full lab.** Set every person's difficulties with sliders, add room supports, and read the event log and scoreboard.

| Difficulty | Brain area in the game |
|---|---|
| Judging space | Parietal lobe |
| Seeing one side | Occipital lobe |
| Moving smoothly | Cerebellum (motor cortex also accepted) |
| Staying focused | Thalamus |
| Words | Broca's and Wernicke's areas |
| Planning | Prefrontal cortex |
| Remembering | Hippocampus |

## Run it

Open `index.html` (the game) or `lab.html` (the full lab) in any modern browser. There is no build step, backend, database or API key. Everything runs locally from rules and dialogue templates. The only network requests are for the Google Fonts, and the page still works without them.

## Disclaimer

These are simplified teaching models, not clinical descriptions of any condition. Real people adapt, use strategies, and vary from day to day.
