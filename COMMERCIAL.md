# Awesome SQLite  - The Commercial Edition


A collection of awesome commercial  sqlite tools, scripts, etc.


## SQLite Admin Tools

Desktop
- [1bench](https://1bench.dev/sqlite) — Native cross-platform desktop GUI with first-class SQLite support alongside Postgres, Redis, Elasticsearch, ClickHouse, Qdrant, and more.
- [VizSQL](https://www.vizsql.io) — Instant SQLite browser that **automatically generates ER diagrams** via drag-and-drop. Features reverse engineering of schemas, and DDL generation. 100% private and WASM-based.
- [SQLite Expert](http://www.sqliteexpert.com) - note: free personal edition and commercial "professional" edition
- [SQLiteSpy](https://www.yunqa.de/delphi/apps/sqlitespy/index)
- [SQLite Administrator](http://sqliteadmin.orbmu2k.de)


<!--

no longer available ??
- [SQLite Analyzer :moneybag:](http://www.kraslabs.com/sqlite_analyzer.php) by Kraslabs
- [SQLiteAdmin :moneybag:](http://www.lcsql.com/sqliteadmin.html) by lcSQL Software
-->

## SQLite Web Services

- **Airsequel** (web: [airsequel.com](https://airsequel.com)) - SQLite hosting platform with instant GraphQL API, SQLite workbench, spreadsheet UI, and dashboards



- **IndieStack** (web: [indiestack.fly.dev](https://indiestack.fly.dev)) - A curated directory of indie-built SaaS alternatives powered by SQLite FTS5 full-text search. 100+ tools cataloged.
- **QueryGlow** (web: [queryglow.com](https://queryglow.com/), demo: [demo.queryglow.com](https://demo.queryglow.com)) - Self-hosted, web-based database GUI with AI SQL generation, EXPLAIN visualizer, and schema-aware autocomplete. Supports PostgreSQL, MySQL, MariaDB, SQLite, CockroachDB, TimescaleDB. $79 one-time.
- **Intellrise CSV to SQL converter** (web: [intellrise.com/tools/csv-to-sql-converter](https://intellrise.com/tools/csv-to-sql-converter/)) - Turns a CSV or Excel workbook into `CREATE TABLE` plus batched `INSERT`s, one table per non-empty worksheet, for PostgreSQL, MySQL, SQL Server, SQLite or generic SQL -- pick the dialect, it opens on PostgreSQL. On SQLite it writes SQLite's own vocabulary: `TEXT`/`INTEGER`/`REAL`, booleans as `1`/`0`, dates as `TEXT`. Column types come from the values, not the header, read from the first 500 data rows -- so a value that contradicts the inferred type and first appears after row 500 is still written into the column. One question is asked of every row instead: a leading zero anywhere in the column keeps it `TEXT`, so ZIP codes and SKUs written `00501` do not lose their zeros. Identifiers that already read as numbers are typed as numbers, and on SQLite a 20-digit reference number becomes a float. Parses in the browser tab -- no upload, no signup. Free.
## Meta

**License**

The awesome list is (c) Planet Commercial Data, 2010-2020. All rights reserved. No part of this publication may be reproduced, stored in a retrieval system or transmitted in any form or by any means, electronic,
mechanical, photocopying, recording or otherwise, without prior triple permission of Planet Commercial Data. 

**Questions? Comments?**

Send them along to the sqlite-users mailing list. Thanks!
