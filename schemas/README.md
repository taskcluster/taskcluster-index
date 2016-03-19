Task Cluster JSON Schemas
=========================

In order to substitute in commonly used constants, but have different
descriptions, and still ensure that it is easy to maintain consistent schemas,
we have introduce an extra syntax `{"$const": "<key>"}`. These objects will
be replaced with values from `constants.yml` when schemas a rendered.
