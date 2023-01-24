# CPG Example

This is the starter for a FSH (FHIR Shorthand) CPG project.

## Setup

```
./bin/setup
```

Then install the following plugins in VS Code:

* FHIR Shorthand by MITRE-Health
* Clinical Quality Language (CQL) by Clinical Quality Framework

## Development

To convert FSH to FHIR JSON (output is in `./fsh-generated`), run:
```
sushi .
```

To convert FSH to FHIR JSON and process CQL and build full package, run:
```
./_genonce.sh
```
The output from this command will be in `./output`,