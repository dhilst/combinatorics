# Goblin Combinatorics Dungeon

A mobile-first infinite roguelike dungeon made with plain HTML, CSS, and JavaScript.

Each room is deterministically generated from the selected seed and asks a combinatorics probability problem. Answers are multiple-choice ratios, for example `1/2`, `5/12`, or `1/1`.

The game uses `NcM` for combinations and `NrM` for ordered selections/permutations, so `9c5` means choose 5 from 9 and `9r3` means arrange 3 from 9.

Open `index.html` directly or publish the repository with GitHub Pages from the root of the `main` branch.
