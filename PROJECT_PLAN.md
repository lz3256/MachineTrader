# MachineTrader Development Outline

This is a proposed plan, not a list of completed features.

| Milestone | Deliverable | Completion criterion |
| --- | --- | --- |
| Data contract | Validated bar/event schema with timestamps and source metadata | Missing, duplicate, and out-of-order records produce an explicit audit |
| Signal interface | Common prediction output with decision time and horizon | Every signal identifies the information available when it was created |
| Historical evaluation | Chronological splits, simple baselines, position accounting | Same inputs and configuration reproduce metrics and cost assumptions |
| Paper adapter | Separate execution interface with explicit paper mode | Order lifecycle, restart behavior, position limits, and reconciliation are tested |
| Reporting | Saved configurations, model/data fingerprints, charts | A reader can connect each figure to its inputs and experiment settings |

The AAPL prototype provides a starting example of a classifier and broker adapter. Its target/backtest alignment and label consistency need to be addressed before integrating its reported performance into a broader system.
