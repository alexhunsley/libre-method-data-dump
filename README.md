# Libre Method data dump
This repo contains JSON and CSV method data generated by the [libre-method-json-place-notation](https://github.com/alexhunsley/libre-method-json-place-notation) tool, for folks who just want the data without running the tool.

The zip files containing the data are in [generated_data](generated_data/).

For small unzipped samples of the data formats, look in [data_samples](data_samples/).

The data is a modified version of data produced by, and Copyright of, [Anthony P. Smith](http://www.methods.org.uk).

# Cloning only the most recent data

To clone just the most recent data (commit), without pulling the older versions, use `--depth 1`:

```
git clone --depth 1 https://github.com/alexhunsley/libre-method-data-dump
```

# Versioning

Data updates are tagged with both the semantic version of [libre-method-json-place-notation](https://github.com/alexhunsley/libre-method-json-place-notation) used and the date the processing was performed.

Example: `release/0.1.0_2023-10-26`

# Original data Copyright notice

```
These method collections are the copyright of Anthony P. Smith. You are welcome
to make copies of the material for your own use. You may distribute copies to others
provided that you do not do so for profit and provided that you include this copyright
statement. If you modify the material before distributing it, you must include a clear
notice that the material has been modified.
```
