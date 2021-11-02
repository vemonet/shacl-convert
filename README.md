# SHACL Convert

A program to easily convert [SHACL Compact](https://w3c.github.io/shacl/shacl-compact-syntax/) to SHACL RDF.


## How to use

Download the `.jar` file from the release page on GitHub.

Convert SHACL Compact to SHACL RDF:

```bash
java -jar shaclconvert.jar compact_shape.shaclc rdf_shape.shacl
```

Convert SHACL RDF to SHACL Compact:

```bash
java -jar shaclconvert.jar rdf_shape.shacl compact_shape.shaclc
```

## Credits

It was retrieved from https://gitlab.ontotext.com/yasen.marinov/shaclconvert and moved to GitHub because gitlab.ontotext.com was down. It seems to be the only thing that has been released to work with SHACL Compact.
