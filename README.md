# Gravitee doc-gen config

## Pupose 

Contains in `src` the configuration needed for `gravitee-doc-gen`.

`main` branch is the source of truth. When generating a documentation it is advised to perform a `git pull`on `main` to make sure to have the latest as the CI will use the latest.

## Usage

To run doc-gen you must indicate where its configuration is:

* `DOCGEN_ROOT=/path/to/gravitee-doc-gen-config/src`
* or `doc-gen --config-dir /path/to/gravitee-doc-gen-config/src`


