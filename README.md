# Shyamkrishna Sreeramasetty

Data engineering portfolio focused on reliable pipelines, data quality,
dimensional modeling, metadata, observability, and reproducible delivery.

## Flagship projects

### [PlantGuard Lab](https://github.com/sshyam67/plantguard-lab)

A reproducible computer-vision research system that tests MobileNetV3 plant-
disease classification across 18 controlled image degradations. It combines
leakage-aware data preparation, image-quality checks, contextual metadata,
SQLite audit history, a Flask interface, documented ethics, tests, and CI.

### [CDC Lakehouse Pipeline](https://github.com/sshyam67/cdc-lakehouse-pipeline)

An ordered change-data-capture workflow across bronze, silver, and gold layers.
It demonstrates append-only event storage, idempotent replay, upserts, deletes,
current-state modeling, deterministic aggregates, tests, and CI.

### [Data Contract Guardian](https://github.com/sshyam67/data-contract-guardian)

A dependency-free contract enforcement CLI for CSV data. It validates types,
required fields, nullability, uniqueness, and numeric bounds, then detects
breaking schema changes before deployment.

### [Pipeline Observability Platform](https://github.com/sshyam67/pipeline-observability-platform)

An operational monitoring pipeline that ingests run events, stores history,
evaluates freshness, duration, volume, and success SLAs, emits machine-readable
alerts, and publishes an HTML status view.

### [Data Quality Monitor](https://github.com/sshyam67/Data-Quality-Monitor)

A configuration-driven validation pipeline with row quarantine, trusted-record
loading, source lineage, JSON quality reports, SQLite audit tables, tests, and
GitHub Actions.

## Engineering evidence

| Capability | Repository evidence |
|---|---|
| ML robustness, traceability, and responsible AI | [PlantGuard Lab](https://github.com/sshyam67/plantguard-lab) |
| CDC and medallion architecture | [CDC Lakehouse Pipeline](https://github.com/sshyam67/cdc-lakehouse-pipeline) |
| Data contracts and schema evolution | [Data Contract Guardian](https://github.com/sshyam67/data-contract-guardian) |
| Data quality and quarantine | [Data Quality Monitor](https://github.com/sshyam67/Data-Quality-Monitor) |
| Pipeline SLAs and observability | [Pipeline Observability Platform](https://github.com/sshyam67/pipeline-observability-platform) |
| Dimensional modeling and SQL analytics | [Sales Data Analysis](https://github.com/sshyam67/sales-data-analysis-project) |
| Metadata profiling and documentation | [Metadata Dictionary Support](https://github.com/sshyam67/metadata-dictionary-support) |

## Additional projects

- [Sales Data Analysis](https://github.com/sshyam67/sales-data-analysis-project) -
  a 9,994-row raw-to-dimensional SQLite analytics pipeline.
- [Global Ethical Supply Chain Tracker](https://github.com/sshyam67/Global-Ethical-Supply-Chain-Tracker) -
  auditable supplier-risk scoring with configurable weights and run lineage.
- [Metadata Dictionary Support](https://github.com/sshyam67/metadata-dictionary-support) -
  automated JSON and Markdown data dictionaries from CSV schemas.
- [Amazon Sales Dashboard](https://github.com/sshyam67/Amazon-Dashboard-Sales) -
  a dimensional sales mart with SQL KPIs and generated HTML reporting.
- [House Price Prediction](https://github.com/sshyam67/House-Price-Prediction) -
  a reproducible preprocessing, training, evaluation, and artifact pipeline.
- [Echo Emotional Memory App](https://github.com/sshyam67/Echo-Emotional-Memory-App) -
  a privacy-first event store with batch ingestion, lineage, quality reporting,
  schema evolution, and portable export.
- [Story-to-Movie Studio](https://github.com/sshyam67/story-to-movie-studio) -
  a resumable AI-media orchestration project with scene manifests, provider
  adapters, subtitles, continuity metadata, and FFmpeg assembly.

## Technical focus

- Python and SQL
- CSV/JSONL ingestion and validation
- SQLite warehouse and dimensional models
- CDC, idempotency, lineage, quarantine, and schema evolution
- Data contracts, metadata profiling, and pipeline SLAs
- Unit testing, GitHub Actions, configuration-driven design, and documentation
- ML evaluation, input-quality monitoring, auditability, and responsible AI

## Current direction

I am extending these foundations toward Airflow or Dagster orchestration,
Spark, dbt, cloud object storage, and production warehouse platforms. Every
featured repository is designed to run locally, explain its architecture, pass
automated tests, and state its limitations honestly.

## Contact

- GitHub: [@sshyam67](https://github.com/sshyam67)
- Email: sshyamkrishna67@gmail.com
