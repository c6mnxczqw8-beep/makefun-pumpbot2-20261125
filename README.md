[![make.fun · u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122?utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)
[![rank](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/c6mnxczqw8-beep/makefun-pumpbot2-20261125/rank.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)
[![reward](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/c6mnxczqw8-beep/makefun-pumpbot2-20261125/reward.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122?utm_source=github&utm_medium=readme&utm_campaign=u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)

# Pump.fun Replay Sprint — Paper Bot, Real Ranking — entry

A pumpfun-replay/v2 entry for the make.fun "Pump.fun Replay
Sprint" bounty. `main.ts` is a Node 22 TypeScript bot built
on the kit's vendored SDK shim (`vendor/makefun-bot.ts`).

Strategy (aggressive sibling of our 6-hour sprint bot, tuned
for this 24-hour replay): never buy at creation; a curve
qualifies after 3 trades and 1 SOL of real reserve; starter
0.08 SOL (capped by the harness's per-order reserve cap);
one pyramid add of 0.05 SOL at +40% on cost; exits at +150%
take profit, −50% stop loss, or a 40,000-slot time stop.
Deterministic, no clock, no randomness.
