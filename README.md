# Java-Learning




QuestDB is an open-source time-series database for high throughput ingestion and fast SQL queries with operational simplicity.

QuestDB is well-suited for financial market data, IoT sensor data, application metrics, real-time dashboards, and fast analytics.

QuestDB implements ANSI SQL with native time-series SQL extensions. These SQL extensions make it simple to filter and downsample data, or correlate data from multiple sources using relational and time-series joins. We achieve high performance by adopting a column-oriented storage model, parallelized vector execution, SIMD instructions, and low-latency techniques. The entire codebase is built from the ground up in Java and C++, with no dependencies and zero garbage collection.

QuestDB supports schema-agnostic streaming ingestion using the InfluxDB line protocol and a REST API for bulk imports and exports. The QuestDB SQL Web Console is an interactive SQL editor facilitating CSV import. Finally, QuestDB also includes the Postgres Wire Protocol for programmatic queries and interoperability with various tools such as Grafana.
