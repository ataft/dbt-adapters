# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html),
and is generated by [Changie](https://github.com/miniscruff/changie).

## dbt-adapter 1.0.0 - April 01, 2024

### Fixes

* Add field wrapper to BaseRelation members that were missing it.
* Add "description" and "meta" fields to RelationConfig protocol

### Under the Hood

* Lazy load agate to improve dbt-core performance
* add BaseAdapater.MAX_SCHEMA_METADATA_RELATIONS

### Security

* Pin `black>=24.3` in `pyproject.toml`
