## David Schabert

MSc Data Engineering @ TUM · interested in how queries behave and how that behaviour can be reproduced · database engines in C++, benchmarking


### Projects

| | |
|---|---|
| **[LiteOLAP](https://github.com/DM-Schabert/LiteOLAP)** | Vectorized column-store analytical engine in C++17. Columnar chunks with RLE/dictionary/bit-packing, zone-map pruning, hash join & aggregation, SQL parser and planner. ~766k rows/s bulk load, 2.4× smaller on disk than a row store. |
| **[LiteQueryDB](https://github.com/DM-Schabert/LiteQueryDB)** | Row-store OLTP engine in C++17. Slotted pages, LRU buffer pool, disk-resident B+-tree, write-ahead log with crash recovery, Volcano executor. ~1.5× faster than SQLite3 on indexed point lookups. |
| **[qsim](https://github.com/DM-Schabert/behaviourOfQueries)** | Which query representation predicts PostgreSQL execution behaviour? 18,479 plans from JOB-Complex/IMDB, 112 pre-registered tests. |

### Stack

`C++17` `Python` `SQL` `PostgreSQL` · CMake, Catch2, pytest, Git

📫 david_schabert@gmx.de · [LinkedIn](https://linkedin.com/in/david-schabert)
