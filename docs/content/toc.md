---
layout: toc
---

## Getting Started
  * [Design](/docs/VERSION/design/index.html)
    * [What is Druid?](/docs/VERSION/design/index.html#what-is-druid)
    * [When should I use Druid](/docs/VERSION/design/index.html#when-to-use-druid)
    * [Architecture](/docs/VERSION/design/index.html#architecture)
    * [Datasources & Segments](/docs/VERSION/design/index.html#datasources-and-segments)
    * [Query processing](/docs/VERSION/design/index.html#query-processing)
    * [External dependencies](/docs/VERSION/design/index.html#external-dependencies)
    * [Ingestion overview](/docs/VERSION/ingestion/overview.html)
  * [Quickstart](/docs/VERSION/tutorials/index.html)
    * [Tutorial: Loading a file](/docs/VERSION/tutorials/tutorial-batch.html)
    * [Tutorial: Loading stream data from Kafka](/docs/VERSION/tutorials/tutorial-kafka.html)
    * [Tutorial: Loading a file using Hadoop](/docs/VERSION/tutorials/tutorial-batch-hadoop.html)
    * [Tutorial: Loading stream data using HTTP push](/docs/VERSION/tutorials/tutorial-tranquility.html)
    * [Tutorial: Querying data](/docs/VERSION/tutorials/tutorial-query.html)
  * [Further tutorials](/docs/VERSION/tutorials/advanced.html)
    * [Tutorial: Rollup](/docs/VERSION/tutorials/rollup.html)
    * [Tutorial: Configuring retention](/docs/VERSION/tutorials/tutorial-retention.html)
    * [Tutorial: Updating existing data](/docs/VERSION/tutorials/tutorial-update-data.html)
    * [Tutorial: Compacting segments](/docs/VERSION/tutorials/tutorial-compaction.html)
    * [Tutorial: Deleting data](/docs/VERSION/tutorials/tutorial-delete-data.html)
    * [Tutorial: Writing your own ingestion specs](/docs/VERSION/tutorials/tutorial-ingestion-spec.html)
  * [Clustering](/docs/VERSION/tutorials/cluster.html)

## Data Ingestion
  * [Ingestion overview](/docs/VERSION/ingestion/overview.html)
  * [Data Formats](/docs/VERSION/ingestion/data-formats.html)
  * [Ingestion Spec](/docs/VERSION/ingestion/index.html)
  * [Schema Design](/docs/VERSION/ingestion/schema-design.html)
  * [Schema Changes](/docs/VERSION/ingestion/schema-changes.html)
  * [Batch File Ingestion](/docs/VERSION/ingestion/batch-ingestion.html)
    * [Native Batch Ingestion](docs/VERSION/ingestion/native_tasks.html)
    * [Hadoop Batch Ingestion](docs/VERSION/ingestion/hadoop.html)
  * [Stream Ingestion](/docs/VERSION/ingestion/stream-ingestion.html)
    * [Stream Push](/docs/VERSION/ingestion/stream-push.html)
    * [Stream Pull](/docs/VERSION/ingestion/stream-pull.html)
  * [Updating Existing Data](/docs/VERSION/ingestion/update-existing-data.html)
  * [Ingestion Tasks](/docs/VERSION/ingestion/tasks.html)
  * [Transform Specs](/docs/VERSION/ingestion/transform-spec.html)
  * [FAQ](/docs/VERSION/ingestion/faq.html)

## Querying
  * [Overview](/docs/VERSION/querying/querying.html)
  * [Timeseries](/docs/VERSION/querying/timeseriesquery.html)
  * [TopN](/docs/VERSION/querying/topnquery.html)
  * [GroupBy](/docs/VERSION/querying/groupbyquery.html)
  * [Time Boundary](/docs/VERSION/querying/timeboundaryquery.html)
  * [Segment Metadata](/docs/VERSION/querying/segmentmetadataquery.html)
  * [DataSource Metadata](/docs/VERSION/querying/datasourcemetadataquery.html)
  * [Search](/docs/VERSION/querying/searchquery.html)
  * [Select](/docs/VERSION/querying/select-query.html)
  * [Scan](/docs/VERSION/querying/scan-query.html)
  * Components
    * [Datasources](/docs/VERSION/querying/datasource.html)
    * [Filters](/docs/VERSION/querying/filters.html)
    * [Aggregations](/docs/VERSION/querying/aggregations.html)
    * [Post Aggregations](/docs/VERSION/querying/post-aggregations.html)
    * [Granularities](/docs/VERSION/querying/granularities.html)
    * [DimensionSpecs](/docs/VERSION/querying/dimensionspecs.html)
    * [Context](/docs/VERSION/querying/query-context.html)
  * [Multi-value dimensions](/docs/VERSION/querying/multi-value-dimensions.html)
  * [SQL](/docs/VERSION/querying/sql.html)
  * [Lookups](/docs/VERSION/querying/lookups.html)
  * [Joins](/docs/VERSION/querying/joins.html)
  * [Multitenancy](/docs/VERSION/querying/multitenancy.html)
  * [Caching](/docs/VERSION/querying/caching.html)
  * [Sorting Orders](/docs/VERSION/querying/sorting-orders.html)
  * [Virtual Columns](/docs/VERSION/querying/virtual-columns.html)

## Design
  * [Overview](/docs/VERSION/design/design.html)
  * Storage
    * [Segments](/docs/VERSION/design/segments.html)
  * Node Types
    * [Historical](/docs/VERSION/design/historical.html)
    * [Broker](/docs/VERSION/design/broker.html)
    * [Coordinator](/docs/VERSION/design/coordinator.html)
    * [Indexing Service](/docs/VERSION/design/indexing-service.html)
    * [Realtime](/docs/VERSION/design/realtime.html)
  * Dependencies
    * [Deep Storage](/docs/VERSION/dependencies/deep-storage.html)
    * [Metadata Storage](/docs/VERSION/dependencies/metadata-storage.html)
    * [ZooKeeper](/docs/VERSION/dependencies/zookeeper.html)

## Operations
  * [API Reference](/docs/VERSION/operations/api-reference.html)
    * [Coordinator](/docs/VERSION/operations/api-reference.html#coordinator)
    * [Overlord](/docs/VERSION/operations/api-reference.html#overlord)
    * [MiddleManager](/docs/VERSION/operations/api-reference.html#middlemanager)
    * [Peon](/docs/VERSION/operations/api-reference.html#peon)
    * [Broker](/docs/VERSION/operations/api-reference.html#broker)
    * [Historical](/docs/VERSION/operations/api-reference.html#historical)
  * [Good Practices](/docs/VERSION/operations/recommendations.html)
  * [Including Extensions](/docs/VERSION/operations/including-extensions.html)
  * [Data Retention](/docs/VERSION/operations/rule-configuration.html)
  * [Metrics and Monitoring](/docs/VERSION/operations/metrics.html)
  * [Alerts](/docs/VERSION/operations/alerts.html)
  * [Updating the Cluster](/docs/VERSION/operations/rolling-updates.html)
  * [Different Hadoop Versions](/docs/VERSION/operations/other-hadoop.html)
  * [Performance FAQ](/docs/VERSION/operations/performance-faq.html)
  * [Dump Segment Tool](/docs/VERSION/operations/dump-segment.html)
  * [Insert Segment Tool](/docs/VERSION/operations/insert-segment-to-db.html)
  * [Pull Dependencies Tool](/docs/VERSION/operations/pull-deps.html)
  * [Recommendations](/docs/VERSION/operations/recommendations.html)
  * [TLS Support](/docs/VERSION/operations/tls-support.html)
  * [Password Provider](/docs/VERSION/operations/password-provider.html)

## Configuration
  * [Configuration Reference](/docs/VERSION/configuration/index.html)
  * [Recommended Configuration File Organization](/docs/VERSION/configuration/index.html#recommended-configuration-file-organization)
  * [JVM Configuration Best Practices](/docs/VERSION/configuration/index.html#jvm-configuration-best-practices)
  * [Common Configuration](/docs/VERSION/configuration/index.html#common-configurations)
  * [Coordinator](/docs/VERSION/configuration/index.html#coordinator)
  * [Overlord](/docs/VERSION/configuration/index.html#overlord)
  * [MiddleManager & Peons](/docs/VERSION/configuration/index.html#middle-manager-and-peons)
  * [Broker](/docs/VERSION/configuration/index.html#broker)
  * [Historical](/docs/VERSION/configuration/index.html#historical)
  * [Caching](/docs/VERSION/configuration/index.html#cache-configuration)
  * [General Query Configuration](/docs/VERSION/configuration/index.html#general-query-configuration)
  * [Configuring Logging](/docs/VERSION/configuration/logging.html)
  
## Development
  * [Overview](/docs/VERSION/development/overview.html)
  * [Libraries](/docs/VERSION/development/libraries.html)
  * [Extensions](/docs/VERSION/development/extensions.html)
  * [JavaScript](/docs/VERSION/development/javascript.html)
  * [Build From Source](/docs/VERSION/development/build.html)
  * [Versioning](/docs/VERSION/development/versioning.html)
  * [Integration](/docs/VERSION/development/integrating-druid-with-other-technologies.html)
  * Experimental Features
    * [Overview](/docs/VERSION/development/experimental.html)
    * [Approximate Histograms and Quantiles](/docs/VERSION/development/extensions-core/approximate-histograms.html)
    * [Datasketches](/docs/VERSION/development/extensions-core/datasketches-extension.html)
    * [Geographic Queries](/docs/VERSION/development/geo.html)
    * [Router](/docs/VERSION/development/router.html)
    * [Kafka Indexing Service](/docs/VERSION/development/extensions-core/kafka-ingestion.html)


## Misc
  * [Druid Expressions Language](/docs/VERSION/misc/math-expr.html)
  * [Papers & Talks](/docs/VERSION/misc/papers-and-talks.html)
  * [Thanks](/thanks.html)
