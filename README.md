# toml-merge

Merges TOML files into TOML or JSON

## Usage

```
$ toml-merge
Usage: toml-merge toml-file [ toml-file ... ]
  -output-json
    	Output JSON instead of TOML
```

## Examples

```
$ toml-merge file1.toml file2.toml > merged.toml

$ toml-merge -output-json file1.toml file2.toml > merged.json
```
