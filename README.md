# Kai Ohtake

Trading infrastructure. UC Berkeley.

Since May 2026 I have been building a system that watches every token launched on a Solana memecoin venue in real time, scores each one within seconds, and simulates the trade. Over 23 days it recorded 261,896,353 trades across 412,637 token launches. It has never been armed for live execution, it has never placed a real order, and I have not found a cost-surviving edge.

The interesting output is the measurement system. Of the five results it produced, three were taken away by a check — one by a stop condition I can show was committed ten days before the run that failed it, one by a control I only added because an earlier failure had made me suspicious, and one by a criterion I wrote into the script but cannot prove I wrote before the run. The other two it could not settle either way, and saying which is which is most of the point:

**→ [solana-trading-engine](https://github.com/kaiohtake/solana-trading-engine)** — architecture, and a research note on what happens when you point a careful instrument at your own ideas.

Two of the results look like artifacts of how I'd defined the outcome — and in one of those, the criterion I wrote to test it refutes my own explanation, so I report the suspicion anyway. One signal looked real for two days and failed to replicate on data it hadn't seen; I retracted it, though unreplicated is not the same as absent. One ranking result has a rival explanation I never tested. And one test couldn't be run at all, because the data that went missing went missing *because* of the variable I was testing.

Interested in quantitative research. `kaiohtake@berkeley.edu`
