# AI for Academic Research Society

## Session 6 · Working with Databases

A JupyterLite lesson exploring football data with SQLite. The notebook uses the Python standard library and runs in the browser with the **Python (Pyodide)** kernel; no custom packages are needed.

### Get started

1. Download the [Session 6 notebook](session-6/AI%20for%20Academic%20Research%20-%20Session%206%20-%20Working%20with%20Databases.ipynb) and open it in JupyterLite.
2. Wait for the Python kernel, then run the **Get a workspace copy of the lesson database** cell.
3. The cell downloads and unpacks the lesson data beside the notebook. If the browser blocks the download, download [`transfermarkt-lesson.sqlite.gz`](session-6/transfermarkt-lesson.sqlite.gz), upload it into the JupyterLite File Browser beside the notebook, and run the cell again.

The automatic download needs the repository to be public and the browser to have internet access. The compressed file is about **33.9 MB**; the uncompressed SQLite database is about **91.5 MB**.

### Session 6 resources

| Resource | What it contains |
|---|---|
| [Working with Databases notebook](session-6/AI%20for%20Academic%20Research%20-%20Session%206%20-%20Working%20with%20Databases.ipynb) | Gradual SQLite introduction, table and column inspection, player and club searches, a fuzzy-search activity, a fictional insert, transfer-spend and player-value analyses, and a copyable Copilot prompt. |
| [Lesson database (`.sqlite.gz`)](session-6/transfermarkt-lesson.sqlite.gz) | Compressed SQLite file containing four linked tables: `players` (50,149 rows), `clubs` (796), `player_valuations` (656,301), and `transfers` (175,165) — **932,411 rows** in total. The notebook unpacks it as `transfermarkt-lesson.sqlite`. |

### Full database

The complete 13-table SQLite database is about **1.05 GB** and is not stored in this repository. It is available from the teacher on request.

### A note on interpretation

Recorded transfer fees are incomplete: missing or zero fees do not prove that no fee was paid. Values are not adjusted for inflation, and the source includes some future-dated records. Treat rankings and charts as measurements of the available records, not complete accounts or proof of cause.
