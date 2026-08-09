## David Schabert


MSc Data Engineering & Analytics @ TUM (2025–2027), based in Munich.

I'm interested in how queries behave and in how reliably that behaviour can be
reproduced. Benchmark numbers are easy to produce and hard to trust: they move with
the machine, the data, the plan the optimizer happened to pick that day. So I work
from both ends. I build engines from scratch (LiteQueryDB, LiteOLAP) to see where
execution time actually goes, and I measure query behaviour empirically (qsim) with
pre-registered predictions and deterministic re-runs, so a result means something
after the fact.

**Currently:** looking for a working student role / internship in database
internals or data infrastructure, from January 2027.


### Projects

| | |
|---|---|
| **[LiteOLAP](https://github.com/DM-Schabert/LiteOLAP)** | Vectorized column-store analytical engine in C++17. Columnar chunks with RLE/dictionary/bit-packing, zone-map pruning, hash join & aggregation, SQL parser and planner. ~766k rows/s bulk load, 2.4× smaller on disk than a row store. |
| **[LiteQueryDB](https://github.com/DM-Schabert/LiteQueryDB)** | Row-store OLTP engine in C++17. Slotted pages, LRU buffer pool, disk-resident B+-tree, write-ahead log with crash recovery, Volcano executor. ~1.5× faster than SQLite3 on indexed point lookups. |
| **[qsim](https://github.com/DM-Schabert/behaviourOfQueries)** | Which query representation predicts PostgreSQL execution behaviour? 18,479 plans from JOB-Complex/IMDB, 112 pre-registered tests. |

### Stack

`C++17` `Python` `SQL` `PostgreSQL` · CMake, pytest, Git

📫 david_schabert@gmx.de · [LinkedIn](https://linkedin.com/in/david-schabert)
