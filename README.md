# QuotesDream

## BinOld

Copy `keys.conf-template` over to `keys.conf`, then paste your own API key, auth
token and shared secret into it.

A read-only key covers every script in here.

<details>
<summary>Where each output lands</summary>

- `counts.txt` comes out of `SlideSwitch.js`
- `weekly.txt` comes out of `BottomSheets.js`

</details>

## machine-learning-docker-image

`node ColorTree.js`

Fold fresh counters into the local store. Run it even on a machine that has
never seen this repo — the store is created on demand.

`node SlideSwitch.js`

Rank the busiest 150 posters; the table lands in `counts.txt`.

`node BottomSheets.js`

Two rank tables at once, one for the past day and one for the past week, both
written to `weekly.txt`.

## spring-cloud-config-demo

Small scripts that tally the rolling counters behind a QuotesDream-style
gallery group, then dump the numbers into flat text for charting.

Before a long run, tick these off:

- [x] keys filled in
- [x] cache cleared under `proxies/`
- [ ] archive copied into `beanfactory/archive/`