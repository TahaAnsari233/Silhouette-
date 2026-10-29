# Silhouette

A top-down pixel-art survival game that runs in the browser. You are a shadow with twin daggers in a ruined castle. Survive 15 waves of the old king's soldiers, then defeat your own betraying clone to claim the throne.

Every wave is fought in a different room of the castle: the dungeon cells, the barracks, the kitchen, the armory, the banquet hall, the courtyard, the library, the long gallery, the chapel, the crypt, the alchemy lab, the treasury, the ballroom, the rain-soaked battlements and the royal antechamber. Each room has its own layout and furniture to fight around. Archers can't shoot through shelves, statues or pillars, but their arrows fly over tables, pews and tombs. The exit door is sealed until every enemy in the room is dead. Then it opens and you walk through to the next room. The 15th door leads to the throne room.

After each of the first 14 rooms you choose one of three blessing cards. Each card is Common, Rare or Legendary, and rarer cards give bigger numbers. Blessings stack and last the whole run, even through deaths:
- Vitality: more max health
- Keen Edge: more slash damage
- Wellspring: extra energy at the start of each room
- Siphon: stronger heal orbs
- Swiftness: faster movement
- Tumbler: shorter roll cooldown
- Riposte: more energy per parry
- Steady Hand: a longer parry window
- Mending Guard: heal on every parry
- Cruelty: a chance to deal double damage
- Bloodthirst: heal on every kill
- Hunger: the ultimate charges faster
- Focus: cheaper Shadow Blast
- Kinship: the Shadow Clone lasts longer

The pause menu lists your blessings.

## Controls

| Input | Action |
| --- | --- |
| W A S D | Move |
| Left click | Hold to keep slashing (every 3rd swing is a heavy finisher) |
| Right click | Parry when the ! above an enemy turns red (+30 energy, up to +50 for parries in a row without getting hit) |
| Space / X | Roll: you're untouchable mid-tumble, so arrows and strikes miss |
| E | Shadow Blast (50 energy) |
| R | Shadow Clone (100 energy) |
| 1 | Ultimate, once the bar is full (20 kills) |
| Esc · M | Pause · Sound and music |

Every 3 kills a green heal orb drops near you. Walk over it for +15 HP and +25 energy before it fades (8 seconds). Energy past 100 isn't wasted: every 25 extra counts as a kill toward your ultimate. The final boss drops one at 75%, 50% and 25% health.

The ultimate bar fills as you kill. Press 1 to wreathe yourself in shadow flame for 30 seconds or until the wave ends. Your slashes reach much farther, you move faster, and a 100-point shield absorbs damage before your health does.

Needs a mouse and keyboard. The whole game is the single file `index.html`.
