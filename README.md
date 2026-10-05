# MachineTrader

A project index and development outline for machine-learning trading prototypes. The original repository contained only this project name. It currently has no independent trading engine, data pipeline, or performance results.

## Existing related work

| Project | Implemented scope |
| --- | --- |
| [AAPL LSTM prototype](https://github.com/lz3256/aapl_lstm_trading) | Return-sequence classification, offline training, model persistence, and an Alpaca paper-trading adapter |
| [TAQ Event Lab](https://github.com/lz3256/taq-event-lab) | Small Transformer experiments on trade-event tokenization and controlled training budgets |
| [IV Surface Lab](https://github.com/lz3256/iv-surface-lab) | Implied-volatility surfaces and rolling return/variance forecast comparisons |
| [ETH modularity research](https://github.com/lz3256/eth-modularity-volatility) | Transaction graphs, event studies, and exploratory equity-volatility associations |

These are separate repositories. Their implementations and recorded results do not establish that MachineTrader itself contains a working system.

## Proposed direction

The next development stage would separate data validation, signal generation, historical evaluation, paper execution, and monitoring. See [the development outline](PROJECT_PLAN.md) for concrete milestones and acceptance criteria.

## Credits

Repository maintained by [@lz3256](https://github.com/lz3256). The project index and development outline were prepared with OpenAI Codex. No new trading results are claimed.
