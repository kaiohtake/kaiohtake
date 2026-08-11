## Kai Ohtake

Building trading infrastructure and consumer products. UC Berkeley.

I spent the last few months building a system that watches every token launched on a Solana memecoin venue in real time, scores each one within seconds, and simulates the trade — then spent most of that time on the harder half, which is knowing whether any of it means anything.

It has never been armed for live execution, and I have not found a cost-surviving edge. The interesting output is the measurement system and the four things it took away from me:

**→ [solana-trading-engine](https://github.com/kaiohtake/solana-trading-engine)** — architecture, and a research note on what happens when you point a careful instrument at your own ideas.

Two results turned out to be artifacts of how I'd defined the outcome. One signal looked real for two days and died on data it hadn't seen. One test couldn't be run at all, because the data that was missing went missing *because* of the variable I was testing.

Interested in quantitative research and early-stage investing. `kaiohtake@berkeley.edu`
