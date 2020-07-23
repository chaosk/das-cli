# Decks Against Society card importer

## Usage

Install using pipsi:
```shell
$ pipsi install das-import
```

Prepare separate files for black and white cards, each card text in separate line and run:
```
$ das-import -u <your username> -p <password> -e <target deck ID> -c <card color> <path to file>
```
