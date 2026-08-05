# Fellowship of the Ring — Chapter Checklist

Tracks which chapters have real dialogue scenes vs. still-empty placeholders.
Update this alongside `index.html` whenever a batch of chapters is filled in.

Legend: ✅ done · 🚧 needs revisit · ⬜ not started yet

| # | Chapter | Status | Notes |
|---|---------|--------|-------|
| 1 | Prologue | 🚧 | Has content, but flagged for a rewrite with the show/hide balance + action-cue style used from ch. 11 onward |
| 1b | Concerning Hobbits | ✅ | |
| 2 | Gandalf's Arrival | ✅ | |
| 3 | The Incident with the Dragon | ✅ | |
| 3b | Gandalf and Bilbo at Bag End | ✅ | |
| 4 | Gandalf and Bilbo Smoking | 🚧 | Drafted from memory, not yet checked against the .srt |
| 5 | Bilbo's Birthday Party | 🚧 | Drafted from memory, not yet checked against the .srt |
| 6 | Bilbo's Speech | 🚧 | Drafted from memory, not yet checked against the .srt |
| 7 | Gandalf and Bilbo Discuss the Ring | 🚧 | Drafted from memory, not yet checked against the .srt |
| 8 | Frodo Arrives at Bag End | 🚧 | Drafted from memory, not yet checked against the .srt |
| 9 | Gandalf Explains the History of the Ring | 🚧 | Drafted from memory, not yet checked against the .srt |
| 10 | Frodo Learns Gollum's Story | 🚧 | Drafted from memory, not yet checked against the .srt |
| 11 | Gandalf Sends Frodo Away From the Shire | ✅ | Sourced from .srt |
| 12 | Gandalf Confronts Saruman at Isengard | ✅ | Sourced from .srt |
| 13 | Saruman Reveals His Betrayal | ✅ | Sourced from .srt |
| 14 | Frodo and Sam Leave Hobbiton | ⬜ | |
| 15 | Merry and Pippin Join the Journey | ⬜ | |
| 16 | Fleeing the Black Rider in the Cornfield | ⬜ | |
| 17 | Hiding From the Nazgûl Under the Tree Roots | ⬜ | |
| 18 | The Hobbits Reach the Ferry | ⬜ | |
| 19 | Arriving at Bree | ⬜ | |
| 20 | The Prancing Pony Inn | ⬜ | |
| 21 | Meeting Strider | ⬜ | |
| 22 | The Nazgûl Attack the Empty Room | ⬜ | |
| 23 | Leaving Bree With Strider | ⬜ | |
| 24 | Camping at Weathertop | ⬜ | |
| 25 | Aragorn's Tale of Beren and Lúthien | ⬜ | |
| 26 | The Witch-king Attacks Frodo at Weathertop | ⬜ | |
| 27 | Arwen Rescues Frodo | ⬜ | |
| 28 | The Ford of Bruinen | ⬜ | |
| 29 | Frodo Wakes in Rivendell | ⬜ | |
| 30 | Bilbo and Frodo Reunite | ⬜ | |
| 31 | The Council of Elrond | ✅ | |
| 32 | Frodo Volunteers to Take the Ring | ✅ | |
| 33 | The Fellowship of the Ring Is Formed | ✅ | |
| 34 | Leaving Rivendell | ⬜ | |
| 35 | Boromir Trains Merry and Pippin | ⬜ | |
| 36 | The Attempt to Cross Caradhras | ⬜ | |
| 37 | Saruman's Storm on the Mountain | ⬜ | |
| 38 | The Decision to Enter Moria | ⬜ | |
| 39 | The Watcher in the Water | ⬜ | |
| 40 | Frodo Confides in Gandalf | ✅ | |
| 41 | Finding Balin's Tomb | ⬜ | |
| 42 | Reading the Book of Mazarbul | ⬜ | |
| 43 | The Orc Ambush in the Chamber | ⬜ | |
| 44 | Frodo's Mithril Shirt Saves Him | ⬜ | |
| 45 | Fleeing Across the Bridge of Khazad-dûm | ⬜ | |
| 46 | Gandalf and the Balrog — "You Shall Not Pass!" | ✅ | |
| 47 | Gandalf Falls into the Chasm | ✅ | |
| 48 | Mourning Gandalf | ⬜ | |
| 49 | Arriving in Lothlórien | ⬜ | |
| 50 | Galadriel's Warning to the Fellowship | ⬜ | |
| 51 | Boromir and Aragorn Discuss the Ring's Temptation | ⬜ | |
| 52 | Frodo and the Mirror of Galadriel | ⬜ | |
| 53 | Frodo Offers Galadriel the Ring | ⬜ | |
| 54 | Leaving Lothlórien by Boat | ⬜ | |
| 55 | Passing the Argonath | ⬜ | |
| 56 | Camp at Amon Hen | ⬜ | |
| 57 | Boromir Tries to Take the Ring | ⬜ | |
| 58 | Frodo Puts on the Ring to Escape | ⬜ | |
| 59 | Aragorn Lets Frodo Go | ⬜ | |
| 60 | The Uruk-hai Attack at Amon Hen | ⬜ | |
| 61 | Boromir's Last Stand | ⬜ | |
| 62 | Boromir's Death | ⬜ | |
| 63 | Merry and Pippin Are Captured | ⬜ | |
| 64 | Sam Catches Up to Frodo | ⬜ | |
| 65 | The Fellowship Is Broken | ⬜ | |

## Sourcing note

Chapters 11-13 were built by searching the uploaded .srt for the relevant
lines. Going forward, new chapters are drafted from memory instead of
systematically working through the full subtitle file — flagged 🚧 until
double-checked. If a specific line's wording matters, paste the short
excerpt you want double-checked and it'll get verified against that.

## Style notes (from ch. 2 / ch. 11-13)

- Default: full line hidden and guessable — this is the norm.
- Use `hide: [...]` when a line is long or hard to recall verbatim; keep the
  memorable/quotable fragment in the hide list and let the rest show as
  context, instead of masking the whole thing.
- Use `shown: true` for short action cues in parentheses — e.g.
  `(laughing)`, `(both hug)`, `(Frodo stands up)` — usually placed after a
  `pause: true` beat, right where the film has a beat of silence or action.
- Keep the truly iconic, most-rewatched lines fully hidden even if long —
  that's the fun part to guess.
