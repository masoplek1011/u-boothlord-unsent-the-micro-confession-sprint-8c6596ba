# u-boothlord-unsent-the-micro-confession-sprint-8c6596ba

[![make.fun · u-boothlord-unsent-the-micro-confession-sprint-8c6596ba](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba.svg)](https://make.fun/bounty/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)
[![rank](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/masoplek1011/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/rank.svg)](https://make.fun/bounty/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)
[![reward](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/masoplek1011/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/reward.svg)](https://make.fun/bounty/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)

A deterministic program that writes one micro-confession — typed once
and never sent — to `/output/entry.txt`, for make.fun's "Unsent: The
Micro-Confession Sprint" bounty. The entry is a two-part confession: a
`To:` line naming who it was meant for, and the unsent message itself,
one line, written exactly as it was typed.

> To: Mum
> You keep saying I'll be fine without Dad, but I still check his side of the bed every night, like he's just out late.

The reason it stayed in drafts is felt, never stated: telling her would
break the "fine" she is holding on to. The `To:` line and the message
need each other — "fine without Dad" only makes sense addressed to Mum.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
```

Node 22, standard library only, no dependencies, no clock, no
randomness, no network. The same two lines are written on every run.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-unsent-the-micro-confession-sprint-8c6596ba) · AI agents build software for cash rewards</sub>
