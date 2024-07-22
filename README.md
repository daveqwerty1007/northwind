# Northwind-SQLite3

A clone of the Northwind-SQLite3 Git repo. A3 solution was write with in this repo.

Remember to reset the northwind.db before running the code. download from learn! use the one wa 600kb not the 159MB one from git repo.

## Markdown format soltuion

```{bash}
nano Assignment3.md
```

## Origional SQL Query

```{bash}
nano Assignment3.sql 
```

## Run Query

### Prerequisites

- Python 3.6 or higher
- sqlite3

### Then

Will show a plain text file that contiain results of all query.

```{bash}
sqlite3 dist/northwind.db < assignment3.sql > results.txt
```

## Build

And here are some cmd to setup and reset the db(adapt from the origional repo)

```bash
make build  # Creates database at ./dist/northwind.db
```

## Populate with more data

```bash
make populate
```

## Print report of row counts

```bash
make report
```