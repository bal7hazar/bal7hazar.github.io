<div align="center">

# Bal7hazar

**Onchain Game Engineer** · Cairo · Starknet · Dojo

Former mechanical engineer, now building games whose rules, and physics, can be proven.

[GitHub](https://github.com/bal7hazar) · [X / Twitter](https://x.com/bal7hazar) · France · Remote

*Open to new opportunities in onchain gaming and provable computation.*

</div>

---

## Summary

Onchain game engineer with 4+ years on Starknet and seven years of mechanical engineering
before that. I design and ship fully onchain games and the infrastructure around them: Cairo
contracts, game engines, SDKs and player-facing apps. I currently port Rust's game-math and
physics stack to Cairo, so that a whole game, physics included, can be proven and settled
onchain. Every change is measured in gas.

- **2,400+ merged pull requests** across 60+ repositories, and 11,500+ contributions since 2022.
- **#1 contributor** to Cartridge's [Arcade](https://github.com/cartridge-gg/arcade), to
  [Paved](https://github.com/stolslilabs/paved) and to Dojo's [Origami](https://github.com/dojoengine/origami), which I started.
- **Dojo Game Jam winner** with zKnight, zDefender, zKlash and Athanor, and **1st place** at the Node Guardians CTF.
- **8 Cairo libraries** published on [scarbs.xyz](https://scarbs.xyz), including a provable physics stack whose core math uses 7 to 12× less gas than a cubit-style scalar.
- **1,200+ PRs merged in Sept–Oct 2026** with orchestrated coding agents, every change gated by CI gas budgets.

---

## Experience

### Open-source R&D: Provable games and Cairo libraries
<sub>2026 – present · Remote, France</sub>

- **Ported** Rust's game-math and physics crates to Cairo on a custom Q32.32 fixed-point scalar:
  [`fixed`](https://github.com/bal7hazar/fixed-cairo), [`simba`](https://github.com/bal7hazar/simba-cairo),
  [`nalgebra`](https://github.com/bal7hazar/nalgebra-cairo), [`glam`](https://github.com/bal7hazar/glam-cairo),
  [`glamx`](https://github.com/bal7hazar/glamx-cairo) and [`rapier2d`](https://github.com/bal7hazar/rapier-cairo). All of them are published on scarbs.xyz.
- **Reached 99.9 % API parity** with nalgebra 0.35 (1,885 of 1,886 items), including the LU, QR,
  Cholesky, SVD and eigen decompositions.
- **Cut gas 7 to 12×** compared with a cubit-style sign-magnitude scalar on dot products, matrix
  products and quaternion products. Fused kernels rescale each output only once.
- **Built [Slingfall](https://github.com/bal7hazar/slingfall)**, a 2D slingshot game deployed on
  Starknet Sepolia. Each level is replayed in cairo-vm (WASM, in a Web Worker), proven, then settled
  onchain.
- **Porting [hexx](https://github.com/bal7hazar/hexx-cairo)**, the Rust hexagonal-grid crate, for
  [Grim World](https://github.com/bal7hazar/grimworld), a fully onchain tick-based RPG. Boards are
  stored as bitmaps in a single felt; release candidates are on scarbs.xyz.
- **Wrote [Quiver](https://github.com/bal7hazar/quiver)**: quests and achievements as native Starknet
  components, the Dojo-free successors of my Arcade packages.
- **Exploring** [Hellproof](https://github.com/bal7hazar/doom), a Doom-like FPS proven in the browser
  with Stwo and verified on Starknet.
- **Ran the work with orchestrated coding agents.** Each task has a committed brief and its own agent
  in its own worktree. PRs are audited and merged on green CI, with gas snapshots for every test.

### Cartridge: Software Engineer
<sub>2024 – 2026 · Remote</sub>

Gaming infrastructure for Starknet: the Controller wallet, Arcade and the Marketplace.

- **Built [Arcade](https://github.com/cartridge-gg/arcade)**, the onchain layer that connects Dojo
  worlds to the Controller: achievements, quests, leaderboards, game editions and starter packs.
  I am its #1 contributor, with 387 commits.
- **Shipped 150+ PRs to the [Controller](https://github.com/cartridge-gg/controller)**: trophies and
  quests, ERC-20 and ERC-721 transfers, collections, the Arcade UI components and the purchase flow.
- **Wrote the [Marketplace](https://github.com/cartridge-gg/marketplace)** contracts and SDK: order book,
  royalties, client fees, integrity model and the fixes from the internal audit.
- **Developed [Nums](https://github.com/cartridge-gg/nums)**, a fully onchain number-placement game:
  Dojo contracts, staking, quests and theming, in 100+ merged PRs.
- **Maintained the session presets** (policies and assets) of partner games such as Eternum, Nums and
  Glitch Bomb. Integrated Controller achievements into [Eternum](https://github.com/BibliothecaDAO/eternum).

### Stolsli Labs: Paved
<sub>Lead contributor · 2024 – present</sub>

- **Built most of [Paved](https://github.com/stolslilabs/paved)**, an onchain tile-laying game: #1 contributor, with 660+
  commits and 400+ merged PRs.
- **Rebuilding it in 2026** on native Cairo contracts without Dojo. The off-chain engine matches the
  contracts' golden vectors, and the new client has a Storybook design system.

### zKorp: Game Designer & Smart Contract Developer
<sub>2023 – 2024</sub>

- **Designed and built fully onchain games** with Dojo: [zKnight](https://github.com/z-korp/zknight-contracts),
  [zDefender](https://github.com/z-korp/zdefender-contracts), [zConqueror](https://github.com/z-korp/zconqueror-contracts)
  (a Risk-like), [zKlash](https://github.com/z-korp/zklash), [zKastle](https://github.com/z-korp/zkastle)
  and [zKube](https://github.com/z-korp/zkube).
- **Won 1st place at three Dojo Game Jams**: #1 with zKnight, #2 with zDefender and #4 with zKlash.
- **Wrote zConqueror's game loop**: lobbies, card draws, battles, bets, events and kicking inactive
  players.

### Carbonable: Smart Contract Developer
<sub>2022 – 2023</sub>

- **Wrote the [Carbon Protocol](https://github.com/Carbonable/carbon-protocol)** in Cairo, in 60+ merged
  PRs. It tokenizes carbon projects, with Merkle-whitelisted minting, offsetting, yield farming and
  vesting.
- **Migrated projects from ERC-721 to ERC-3525** semi-fungible tokens, and contributed to Carbonable's
  Cairo libraries for ERC-3525, ERC-2981 and ERC-4906.
- **Reached the finals of two Starknet Hacker Houses**, in Tel Aviv with Sybil Shield and in Paris with Pufu.

### Michelin: Mechanical Engineer
<sub>2015 – 2022</sub>

- Seven years of mechanical engineering before moving to software full-time in 2022. The same
  numerical-methods background now drives my fixed-point and physics work.

---

## Open source

### Cairo libraries

All of them are published on [scarbs.xyz](https://scarbs.xyz), with gas measured on every test.

| Package | Port of | What |
|---|---|---|
| [`fixed`](https://github.com/bal7hazar/fixed-cairo) | `f64` | Signed Q32.32 fixed-point scalar: bit-exact, fused kernels, loop-free trigonometry |
| [`simba`](https://github.com/bal7hazar/simba-cairo) | simba | Scalar traits (`Real`, `Transcendental`) for generic linear algebra |
| [`nalgebra`](https://github.com/bal7hazar/nalgebra-cairo) | nalgebra | Linear algebra: 99.9 % of the API, from static matrices to SVD and eigen decompositions |
| [`glam`](https://github.com/bal7hazar/glam-cairo) | glam | Vectors, matrices and quaternions: 7 to 12× less gas than a cubit-style scalar |
| [`glamx`](https://github.com/bal7hazar/glamx-cairo) | glamx | Rotations, poses and symmetric matrices, the layer Rapier is written against |
| [`rapier2d`](https://github.com/bal7hazar/rapier-cairo) | Rapier | 2D physics: rigid bodies, colliders, joints, sensors, events, world save and restore |
| [`hexx`](https://github.com/bal7hazar/hexx-cairo) | hexx | Hexagonal grids, with boards stored as bitmaps in a single felt |
| [`quiver_quest`, `quiver_achievement`](https://github.com/bal7hazar/quiver) | Arcade | Quests and achievements as native Starknet components |

In progress: [`types-cairo`](https://github.com/bal7hazar/types-cairo), one package per numeric type,
starting with `u252`.

### Contributions

| Project | What | Role |
|---|---|---|
| [Origami](https://github.com/dojoengine/origami) | Game library for Dojo: ELO rating, maze generation, pathfinding | Started it, #1 contributor |
| [Shinigami](https://github.com/bal7hazar/shinigami) | A design pattern for autonomous worlds in Cairo | Author |
| [Alexandria](https://github.com/keep-starknet-strange/alexandria) | Numerical, linear algebra, Merkle tree and bitmap modules | Contributor |
| Upstream fixes | [Dojo](https://github.com/dojoengine/dojo), [OpenZeppelin Cairo](https://github.com/OpenZeppelin/cairo-contracts), [Kakarot](https://github.com/kkrt-labs/kakarot), [Pragma](https://github.com/astraly-labs/pragma-oracle), [cubit](https://github.com/influenceth/cubit), [Orion](https://github.com/gizatechxyz/orion) | Contributor |

<sub>All merged pull requests:
[search on GitHub](https://github.com/search?q=author%3Abal7hazar+is%3Apr+is%3Amerged&type=pullrequests).</sub>

---

## Awards

| Date | Event | Result | Project |
|---|---|---|---|
| 03/2026 | Dojo Game Jam VIII | 🏆 Winner | [Athanor](https://github.com/djizus/athanor), with djizus |
| 04/2024 | Dojo Game Jam #4 | 🥇 1st | [zKlash](https://github.com/z-korp/zklash) |
| 11/2023 | Dojo Game Jam #2 | 🥇 1st | [zDefender](https://github.com/z-korp/zdefender-contracts) |
| 09/2023 | Dojo Game Jam #1 | 🥇 1st | [zKnight](https://github.com/z-korp/zknight-contracts) |
| 07/2023 | Node Guardians CTF, Paris | 🥇 1st | |
| 07/2023 | Starknet Hacker House, Paris | Finalist | [Pufu](https://github.com/carbonable-labs/pufu) |
| 06/2023 | Pragma Hackathon #1 | Competitor | [Explore](https://github.com/StarkExplore/Explore) |
| 02/2023 | Starknet Hacker House, Tel Aviv | Finalist | [Sybil Shield](https://github.com/carbonable-labs/sybil-shield) |
| 10/2022 | Starknet CC CTF, Lisbon | 6th | |

---

## Skills

**Onchain**: Cairo · Starknet · Scarb · Starknet Foundry · Dojo (Sozo, Torii, Katana) · Cartridge Controller · SNIP-36 proofs<br>
**Client**: TypeScript · React · PixiJS · Storybook · Vite · WebAssembly<br>
**Other**: Rust (porting, cairo-vm tooling) · Python · Fortran 77<br>
**Practice**: gas budgets and snapshots in CI · golden vectors against Rust references · test-driven development · orchestrated coding agents

**Languages**: French (native) · English (professional)

---

<div align="center">
<sub>Last updated October 2026 · <a href="https://github.com/bal7hazar">github.com/bal7hazar</a></sub>
</div>
