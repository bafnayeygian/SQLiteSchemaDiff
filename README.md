# SQLiteSchemaDiff

Compare two SQLite database schemas and report added, removed, or changed tables, columns, and indexes.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/SQLiteSchemaDiff.git
cd SQLiteSchemaDiff
python -m pip install .
```

## Quick start

```bash
sqlite-schema-diff --help
```

Useful for migration reviews and catching accidental schema drift.

```bash
sqlite-schema-diff old.db new.db --json schema-diff.json
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
