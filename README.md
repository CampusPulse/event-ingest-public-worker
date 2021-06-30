# vaccine-feed-ingest-public-worker

<!-- markdownlint-disable MD013 -->
| environment | repo ingest | private load |
|-|-|-|
| prod | [![production - repo - all stages / all sites](https://github.com/CAVaccineInventory/vaccine-feed-ingest-public-worker/actions/workflows/production-worker-repo.yml/badge.svg?branch=main)](https://github.com/CAVaccineInventory/vaccine-feed-ingest-public-worker/actions/workflows/production-worker-repo.yml) | [![production - private - load-to-vial](https://github.com/CAVaccineInventory/vaccine-feed-ingest-public-worker/actions/workflows/production-loader-private-gcs.yml/badge.svg?branch=main)](https://github.com/CAVaccineInventory/vaccine-feed-ingest-public-worker/actions/workflows/production-loader-private-gcs.yml) |
<!-- markdownlint-restore -->

[`vaccine-feed-ingest`](https://github.com/CAVaccineInventory/vaccine-feed-ingest) is an open-source repo which accepts contributions of ingestors from the public.
This repo, `vaccine-feed-ingest-public-worker`, periodically runs those ingestors via GitHub actions, and loads the results to the **v**accine **i**nformation **a**rchive & **l**ibrary, for further distribution on [vaccinatethestates.com](https://vaccinatethestates.com) and via data sharing partners.
Other systems may also run these ingestors with a different configuration than what is seen here.

Results for most ingestors are also directly available on GitHub in [`vaccine-feed-ingest-results`](https://github.com/CAVaccineInventory/vaccine-feed-ingest-results).
