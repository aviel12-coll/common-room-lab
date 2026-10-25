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

- **`index.html`: In Their Shoes (first person).** Do an everyday job yourself in a 3D view of the shared room while living with one or more simplified challenges:
  - **Judging space:** things look shifted from where they really are.
  - **Left-side vision:** the left of your view fades away.
  - **Unsteady movement:** slow, shaky, delayed controls, and hands that slip.
  - **Staying focused:** voices and noises pull your gaze away.
  - **Understanding words:** speech and instructions are partly jumbled.
  - **Planning steps:** the job's steps arrive in no particular order.
  - **Remembering:** your goal fades and finished steps aren't ticked off.

  Ada, Ben and Chen go about their own jobs, notice when you struggle (bumping, wrong places, steps out of order, standing lost) and come over to offer help that fits the difficulty. You can accept or say no. Afterwards you can adapt the room (labels, checklist, quiet room, clear walkways, adapted tools, picture instructions, left-side markers) and try again. Each attempt gets an independence score and is compared with your earlier attempts. A replay shows the room from above (what actually happened) next to your own first-person view (what you experienced), with a timeline and a list of events in both versions.
- **`detective.html`: Brain Detective.** Watch a person with a hidden difficulty, name it, then find where it lives on a brain picture. The person works in a team with Ada, who takes over steps when they get stuck.
- **`lab.html`: the full lab.** Set every person's difficulties with sliders, add room supports, and read the event log and scoreboard.

Brain Detective matches each difficulty to one brain area:

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

Open `index.html`, `detective.html` or `lab.html` in any modern browser. Controls for In Their Shoes: W A S D or arrow keys to move, E to use things, R to remind yourself, H to ask for help, Y / N to answer offers. There is no build step, backend, database or API key. Everything runs locally from rules and dialogue templates. The only network requests are for the Google Fonts, and the page still works without them.

## Disclaimer

These are simplified teaching models, not clinical descriptions of any condition. Real people adapt, use strategies, and vary from day to day.
