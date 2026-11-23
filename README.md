# Ember Court — Duel of the Four Suits

[![make.fun · best-card-game-20261122-1826](https://make.fun/badge/best-card-game-20261122-1826.svg)](https://make.fun/bounty/best-card-game-20261122-1826)

An original card battler for make.fun's "Make the best card game" bounty ($50). Playable offline in a desktop browser from static files — no network requests, no libraries.

## Run it

```sh
node serve.ts
# open http://localhost:8080
```

## The game

You are the **Ember Fox**, duelling **Archmage Pyra** for the Ember Throne. 30 life each.

- Each round: +1 max energy (up to 8) and draw a card.
- Click a card in your hand to select it (costs ⚡ energy), then click **Pyra's portrait** to hit her directly, or click **one of her field cards** to destroy it.
- Elemental advantage: **Flame > Gale > Stone > Tide > Flame** — advantage deals +50% damage.
- First to 0 life loses. Win/loss screens show the final score and session record.

Keyboard: `1–7` selects a card, `Enter` ends turn.

## Screenshots

`?shot=start` title · `?shot=play` mid-duel · `?shot=win` victory · `?shot=loss` defeat. See `shots.json`.

## Originality

Original idea, art, names and rules. Nothing copied from any commercial card game.

## License

MIT — see `LICENSE`.
