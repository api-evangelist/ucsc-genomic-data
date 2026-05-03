# UCSC Genomic Data

The UCSC Genome Browser is a widely-used bioinformatics tool providing access to genomic data, sequence information, and annotation tracks for hundreds of organisms. The REST API provides programmatic access to genome assemblies, DNA sequences, annotation tracks, and track hubs. No authentication is required; rate limiting of one request per second is recommended.

**URL:** [https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml)

**Human URL:** [https://genome.ucsc.edu/goldenPath/help/api.html](https://genome.ucsc.edu/goldenPath/help/api.html)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Genomics, Bioinformatics, DNA, Biology, Research, Open Science

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-03

## APIs

### UCSC Genome Browser REST API
REST API for genome assembly discovery, DNA sequence retrieval, annotation track data, and track hub management. No authentication required.

**Base URL:** `https://api.genome.ucsc.edu`

#### Tags
Genomics, Bioinformatics, DNA Sequences, Annotation Tracks, Genome Assemblies

#### Properties
- [Documentation](https://genome.ucsc.edu/goldenPath/help/api.html)
- [OpenAPI](openapi/ucsc-genomic-data-openapi.yml)
- [Example](examples/ucsc-get-dna-sequence-example.json)
- [Example](examples/ucsc-list-tracks-example.json)
- [JSONSchema](json-schema/ucsc-genomic-data-sequence-schema.json)
- [JSONSchema](json-schema/ucsc-genomic-data-track-schema.json)

## Artifacts

### OpenAPI Specifications
| File | Description |
|------|-------------|
| [openapi/ucsc-genomic-data-openapi.yml](openapi/ucsc-genomic-data-openapi.yml) | UCSC Genome Browser REST API |

### Naftiko Capabilities
| File | Description |
|------|-------------|
| [capabilities/genomic-research.yaml](capabilities/genomic-research.yaml) | Genomic research workflow — sequence retrieval, track queries, genome discovery (8 tools) |

**Shared definitions:** `capabilities/shared/genome-browser.yaml`

### Rules
- [rules/ucsc-genomic-data-rules.yml](rules/ucsc-genomic-data-rules.yml)

### JSON Schema
- [json-schema/ucsc-genomic-data-sequence-schema.json](json-schema/ucsc-genomic-data-sequence-schema.json)
- [json-schema/ucsc-genomic-data-track-schema.json](json-schema/ucsc-genomic-data-track-schema.json)

### JSON Structure
- [json-structure/ucsc-genomic-data-structure.json](json-structure/ucsc-genomic-data-structure.json)

### JSON-LD
- [json-ld/ucsc-genomic-data-context.jsonld](json-ld/ucsc-genomic-data-context.jsonld)

### Examples
- [examples/ucsc-get-dna-sequence-example.json](examples/ucsc-get-dna-sequence-example.json)
- [examples/ucsc-list-tracks-example.json](examples/ucsc-list-tracks-example.json)

### Vocabulary
- [vocabulary/ucsc-genomic-data-vocabulary.yml](vocabulary/ucsc-genomic-data-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
