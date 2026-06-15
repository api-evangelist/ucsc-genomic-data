# UCSC Genomic Data (ucsc-genomic-data)

The UCSC Genome Browser is a widely-used bioinformatics tool providing access to genomic data, sequence information, and annotation tracks for hundreds of organisms. The REST API provides programmatic access to genome assemblies, DNA sequences, annotation tracks, and track hubs. No authentication is required; rate limiting of one request per second is recommended. Data is returned in JSON format.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Genomics
- Bioinformatics
- DNA
- Biology
- Research
- Open Science

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### UCSC Genome Browser REST API

REST API providing programmatic access to the UCSC Genome Browser's genomic data, including genome assemblies, DNA sequences, annotation tracks, and track hubs. All endpoints use HTTP GET and return JSON. No authentication is required. Rate limited to one request per second. Supports hg38, mm39, and hundreds of other assemblies.

- **Human URL:** [https://genome.ucsc.edu/goldenPath/help/api.html](https://genome.ucsc.edu/goldenPath/help/api.html)
- **Base URL:** `https://api.genome.ucsc.edu`

#### Tags

- Genomics
- Bioinformatics
- DNA Sequences
- Annotation Tracks
- Genome Assemblies

#### Properties

- [Documentation](https://genome.ucsc.edu/goldenPath/help/api.html)
- [OpenAPI](openapi/ucsc-genomic-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ucsc-genomic-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ucsc-genomic-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/ucsc-get-dna-sequence-example.json)
- [Example](examples/ucsc-list-tracks-example.json)
- [JSON Schema](json-schema/ucsc-genomic-data-sequence-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ucsc-genomic-data-track-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [GitHub Organization](https://github.com/ucscgenomebrowser)
- [LinkedIn](https://www.linkedin.com/company/ucsc-genomics-institute)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
