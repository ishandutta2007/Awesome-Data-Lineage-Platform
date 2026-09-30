# Awesome-Data-Lineage-Platform

## Top Data Lineage Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Column-Level Lineage, Impact Analysis, Pipeline Tracing, Open Standards & End-to-End Data Flow Visibility*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Lineage**. These systems map how data moves from sources through transformations to reports, models, and applications—enabling impact analysis, debugging, and governance.



**Examples** include Manta, Collibra, Alation, Microsoft Purview, Atlan, Octopai, OvalEdge, Informatica EDC, DataGalaxy, CastorDoc, Monte Carlo, OpenLineage, Secoda, Acceldata, and DataHub (the category leaders).



**Open-source emphasis**: Data lineage has a strong open foundation. **OpenLineage**, **Marquez**, **DataHub**, **OpenMetadata**, and **Apache Atlas** provide standards and production-ready lineage platforms. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Manta](https://www.getmanta.com/)**  

  Deep code-level and automated data lineage platform specialized in complex ETL and legacy transformation environments.



- **[Collibra](https://www.collibra.com/)**  

  Enterprise data governance platform with robust lineage, impact analysis, and stewardship workflows.



- **[Alation](https://www.alation.com/)**  

  Data intelligence platform combining catalog, behavioral insights, and column-level lineage for analytics teams.



- **[Microsoft Purview](https://azure.microsoft.com/products/purview/)**  

  Microsoft’s data governance and lineage service tightly integrated with Azure, Microsoft 365, and hybrid estates.



- **[Atlan](https://atlan.com/)**  

  Active metadata platform with strong column-level lineage for modern data stacks (dbt, Snowflake, Databricks, etc.).



- **[Octopai](https://www.octopai.com/)**  

  Automated data lineage and discovery platform focused on BI and analytics environments.



- **[OvalEdge](https://www.ovaledge.com/)**  

  Data catalog and lineage platform with broad connectors and governance features.



- **[Informatica Enterprise Data Catalog / EDC](https://www.informatica.com/)**  

  Enterprise metadata and lineage capabilities within Informatica’s data management cloud.



- **[DataGalaxy](https://www.datagalaxy.com/)**  

  Collaborative data knowledge and lineage platform for business and technical stakeholders.



- **[CastorDoc](https://www.castordoc.com/)**  

  Data documentation and catalog tool with lineage and collaboration features for analytics teams.



- **[Monte Carlo](https://www.montecarlodata.com/)**  

  Data observability platform that includes lineage context for incident investigation and impact analysis.



- **[OpenLineage (ecosystem / commercial support)](https://openlineage.io/)**  

  Open standard with commercial tooling and integrations built around lineage event collection.



- **[Secoda](https://www.secoda.co/)**  

  AI-assisted data catalog and knowledge platform with lineage and search across assets.



- **[Acceldata](https://www.acceldata.io/)**  

  Data observability and reliability platform with lineage and pipeline monitoring capabilities.



- **[DataHub (Managed / Acryl)](https://datahubproject.io/)**  

  Commercial and managed offerings around the open-source DataHub metadata and lineage platform.



## Open-Source GitHub Projects

- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  

  Open standard for lineage metadata collection—instrument jobs (Spark, Airflow, dbt, Flink, etc.) to emit consistent lineage events.



- **[Marquez](https://github.com/MarquezProject/marquez)**  

  Open-source metadata service and reference implementation of the OpenLineage API for collecting and visualizing lineage.



- **[DataHub](https://github.com/datahub-project/datahub)**  

  Open-source metadata platform with strong column-level lineage, impact analysis, and a graph-based model.



- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  

  Open-source data catalog and governance platform with built-in lineage, connectors, and column-level support.



- **[Apache Atlas](https://github.com/apache/atlas)**  

  Open-source metadata and governance framework with lineage and classification capabilities (Hadoop-era roots).



- **[dbt lineage / documentation](https://github.com/dbt-labs/dbt-core)**  

  Built-in model and column lineage for dbt projects—widely used as a foundation for modern stack lineage.



- **[Egeria](https://github.com/odpi/egeria)**  

  Open metadata and governance project for federated metadata exchange across tools and platforms.



- **[SQL parsers and column-lineage extractors](https://github.com/)**  

  Community libraries that parse SQL/ETL code to produce column-level lineage graphs.



- **[Documentation and OpenLineage / DataHub playbooks](https://openlineage.io/docs/)**  

  Guides for instrumenting pipelines, running Marquez, and operating open lineage platforms.



- **[Self-hosted lineage stacks](https://github.com/)**  

  Patterns combining OpenLineage producers → Marquez or DataHub/OpenMetadata for end-to-end open lineage.



### Additional Strong Open-Source Options

- Emitting lineage with **OpenLineage** from Airflow, Spark, dbt, and other jobs.

- Storing and visualizing with **Marquez**, **DataHub**, or **OpenMetadata**.

- Using **dbt** native lineage for transformation-layer visibility.

- Accepting that deep legacy ETL code parsing, enterprise governance packaging, and fully managed multi-tool coverage still favor commercial platforms (Manta, Collibra, Atlan, Alation, Purview, Informatica, etc.).

- Focusing open-source efforts on standards-based collection and ownership of lineage metadata.



**Frameworks for building custom systems**: Instrument jobs with OpenLineage → collect in Marquez or DataHub/OpenMetadata → use impact analysis before changes → enrich with catalog metadata. Suitable for modern data teams. Complex hybrid and legacy estates often add commercial lineage scanners.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Lineage metadata can reveal sensitive system topology. Secure access and accurate instrumentation are required. This list is not operational advice.



---

**Made for data engineers, governance teams, and open metadata advocates.**

Let's keep data flows visible, impact-aware, and as open as practical.
