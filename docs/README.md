# How to build docs

This adds a template for creating formalized documentation using pandoc templates, latex, and markdown.

Building requires pandoc and tex-live.

To build, run the github action or from the root directory of the repository run:

```
pandoc ./docs/floation_device.md -o ./docs/floation_device.pdf --template rust_docs.template --data-dir=./docs/
```

