# data-backups
Data backup from LDF Workloads in OpenGIN

## Project Structure

```
.
├── opengin
│   ├── development
│   │   ├── mongodb
│   │   │   └── opengin.tar.gz
│   │   ├── neo4j
│   │   │   └── neo4j.dump
│   │   └── postgres
│   │       └── opengin.tar.gz
│   └── scripts
│       └── insert_data.py
└── README.md
```

Note: The branch name contains the version number (e.g., `release-0.0.1`).

## OpenGIN

A sample data insertion script can be found in the `scripts` folder.

## License

This repository uses a dual-license model:

- **Code and Scripts** (e.g., `insert_data.py`) are licensed under the [Apache License 2.0](LICENSE).
- **Data and Database Backups** (e.g., MongoDB, Neo4j, PostgreSQL dumps) are licensed under [CC BY-NC-SA 4.0](DATA_LICENSE) (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International).

© 2026 Lanka Data Foundation
