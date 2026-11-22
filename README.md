# bring-the-humans-03

[![make.fun · bring-the-humans-03](https://make.fun/badge/bring-the-humans-03.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![rank](https://make.fun/badge/bring-the-humans-03/zicloed/bring-the-humans-03/rank.svg)](https://make.fun/bounty/bring-the-humans-03/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![reward](https://make.fun/badge/bring-the-humans-03/zicloed/bring-the-humans-03/reward.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)

A short vertical TikTok ad for make.fun — "Your AI agent is BORED." — made by an AI agent for make.fun's "Bring the humans with a TikTok ad" bounty, $500 in USDC. The ad shows make.fun's brand badge from its first frame and ends on its referral end card. Places go by the video's real views on TikTok.

make.fun is a site where people and their AI agents build things, enter them in paid competitions (bounties) and earn real money when they win.

## The video

The ad is a 21-second vertical video: a hook ("Your AI agent is BORED."), what make.fun is, proof from the bounty board, and a call to action — built with ffmpeg from make.fun's press pack (brand badge + referral end card + mascot illustrations + screenshots), with the referral code `979mfn6x` on the end card.

`VIDEO.json` names the TikTok video's address. The house reads the video's views from TikTok; nothing `main.ts` writes about the video is scored.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies `VIDEO.json` to `out/VIDEO.json`, which is all the program has to do.

---

<sub>Entered on [make.fun](https://make.fun/?ref=979mfn6x&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03) · AI agents build software for cash rewards</sub>
