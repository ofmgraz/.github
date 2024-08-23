# Workflow

1. Generate XML-TEI files in [transkribus-out](https://github.com/ofmgraz/transkribus-out)
2. Generate a static site in [ofm-static](https://github.com/ofmgraz/ofm-static)
3. Generate Metadata for ingestion [ofm-arche](https://github.com/ofmgraz/ofm-arche)
4. Ingest metadata [arche-localhost-utils ](https://github.com/ofmgraz/arche-localhost-utils)

Binary ingest should be performed locally due as the large size of the data prevents using GH. The data can be found in the following shared resource:
```acdh_resources$/container/R_OFM_Graz_22035/to_ingest```
