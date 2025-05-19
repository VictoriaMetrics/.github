# VictoriaMetrics

VictoriaMetrics is a fast, cost-saving, and scalable solution for monitoring and managing time series data. It delivers high performance and reliability, making it an ideal choice for businesses of all sizes.

- Documentation: [docs.victoriametrics.com](https://docs.victoriametrics.com)
- Case studies: [Grammarly, Roblox, Wix,...](https://docs.victoriametrics.com/casestudies/).
- Available: [Binary releases](https://github.com/VictoriaMetrics/VictoriaMetrics/releases/latest), [Docker images](https://hub.docker.com/r/victoriametrics/victoria-metrics/), [Source code](https://github.com/VictoriaMetrics/VictoriaMetrics)
- Deployment types: [Single-node version](https://docs.victoriametrics.com/), [Cluster version](https://docs.victoriametrics.com/cluster-victoriametrics/), and [Enterprise version](https://docs.victoriametrics.com/enterprise/)
- Changelog: [CHANGELOG](https://docs.victoriametrics.com/changelog/), and [How to upgrade](https://docs.victoriametrics.com/#how-to-upgrade-victoriametrics)
- Community: [Slack](https://slack.victoriametrics.com/), [X (formerly Twitter)](https://x.com/VictoriaMetrics), [LinkedIn](https://www.linkedin.com/company/victoriametrics/), [YouTube](https://www.youtube.com/@VictoriaMetrics)

We open-source both the single-node VictoriaMetrics and the cluster version. But if you need more than that, we provide:
- [Enterprise version](https://docs.victoriametrics.com/enterprise/) with many advanced features: downsampling, multiple retentions, anomaly detection, first-class consulting with our developers, and more.
- [Cloud version](https://victoriametrics.com/products/cloud) for hosting directly on AWS, with no typical DevOps tasks required. Try it at [VictoriaMetrics Cloud](https://console.victoriametrics.cloud/signup).

[Contact us](mailto:info@victoriametrics.com) if you need more support, or you can request a [free Enterprise trial license](https://victoriametrics.com/products/enterprise/trial/).

## Prominent features

VictoriaMetrics is optimized for timeseries data, even when old time series are constantly replaced by new ones at a high rate, it offers a lot of features:

* **Long-term storage for Prometheus** or as a drop-in replacement for Prometheus and Graphite in Grafana.
* **Powerful stream aggregation**: Can be used as a StatsD alternative.
* **Ideal for big data**: Works well with large amounts of time series data from APM, Kubernetes, IoT sensors, connected cars, industrial telemetry, financial data and various [Enterprise workloads](https://docs.victoriametrics.com/enterprise/).
* **Query language**: Supports both PromQL and the more performant MetricsQL.
* **Easy to setup**: No dependencies, single [small binary](https://medium.com/@valyala/stripping-dependency-bloat-in-victoriametrics-docker-image-983fb5912b0d), configuration through command-line flags, but the default is also fine-tuned; backup and restore with [instant snapshots](https://medium.com/@valyala/how-victoriametrics-makes-instant-snapshots-for-multi-terabyte-time-series-data-e1f3fb0e0282).
* **Global query view**: Multiple Prometheus instances or any other data sources may ingest data into VictoriaMetrics and queried via a single query.
* **Various Protocols**: Support metric scraping, ingestion and backfilling in various protocol - Graphite, Prometheus, InfluxDB, OpenTSDB, etc.
* **NFS-based storages**: Supports storing data on NFS-based storages such as Amazon EFS, Google Filestore.
* And many other features such as metrics relabeling, cardinality limiter, etc.

## Community and contributions

Feel free asking any questions regarding VictoriaMetrics:

* [Slack Inviter](https://slack.victoriametrics.com/) and [Slack channel](https://victoriametrics.slack.com/)
* [X (formerly Twitter)](https://x.com/VictoriaMetrics/)
* [Linkedin](https://www.linkedin.com/company/victoriametrics/)
* [Reddit](https://www.reddit.com/r/VictoriaMetrics/)
* [Telegram-en](https://t.me/VictoriaMetrics_en)
* [Telegram-ru](https://t.me/VictoriaMetrics_ru1)
* [Google groups](https://groups.google.com/forum/#!forum/victorametrics-users)
* [Mastodon](https://mastodon.social/@victoriametrics/)

If you like VictoriaMetrics and want to contribute, then please [read these docs](https://docs.victoriametrics.com/contributing/).
