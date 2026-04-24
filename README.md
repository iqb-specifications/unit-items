[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

Unit-items are an addendum to the data of an assessment unit. This repository contains the JSON schema and generated documentation for the `Items` block.

Read more:

* [All specifications of IQB](https://iqb-specifications.github.io/) (German only)
* [Learn about TBA](https://iqb-berlin.github.io/tba-info/) (German only)
* [Verona-Interfaces](https://verona-interfaces.github.io/)

Change log: see releases.

## For developers

After modifying the spec, update the version number in `unit-items.schema.json` (`$id`).

Validate the schema and example files locally:

```
npm ci
npm run validate-schema
npm run generate_docs
```

After merging to `main`, create a new release using the new version number as tag. This way, the new spec is accessible via w3id.org. Example:

```
https://w3id.org/iqb/spec/unit-items/0.1
```
