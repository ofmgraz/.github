# OFM Graz

Almost every step is automated through GitHub Actions. Nonetheless, the binary ingest must be performed locally due to the size of the data. 

# Workflow

1. Generate XML-TEI files in [transkribus-out](https://github.com/ofmgraz/transkribus-out)
2. Generate a static site in [ofm-static](https://github.com/ofmgraz/ofm-static)
3. Generate Metadata for ingestion [ofm-arche](https://github.com/ofmgraz/ofm-arche)
4. Ingest metadata [arche-localhost-utils ](https://github.com/ofmgraz/arche-localhost-utils)
5. Perform locally a binary ingest of the data located ```acdh_resources$/container/R_OFM_Graz_22035/to_ingest```
