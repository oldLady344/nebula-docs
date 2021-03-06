# Welcome to the Official Nebula Graph Documentation

**Nebula Graph** is a distributed, scalable, and lightning-fast graph database.

It is the optimal solution in the world capable of hosting graphs with dozens of billions of vertices (nodes) and trillions of edges with millisecond latency.

## Preface

* [About This Manual](0.about-this-manual.md)
* [Manual Change Log](CHANGELOG.md)

## Overview (for Beginners)

* [Introduction](1.overview/0.introduction.md)
* Concepts
  * [Data Model](1.overview/1.concepts/1.data-model.md)
  * [Query Language Overview](1.overview/1.concepts/2.nGQL-overview.md)
* Quick Start and Useful Links
  * [Get Started](1.overview/2.quick-start/1.get-started.md)
  * [FAQ](1.overview/2.quick-start/2.FAQ.md)
  * [Build Source Code](3.build-develop-and-administration/1.build/1.build-source-code.md)
  * [Import .csv File](3.build-develop-and-administration/5.storage-service-administration/data-import/import-csv-file.md)
  <!-- * [Ingest .sst File](3.build-develop-and-administration/5.storage-service-administration/data-import/download-and-ingest-sst-file.md) -->
  * [Nebula Graph Clients](1.overview/2.quick-start/3.supported-clients.md)

* Design and Architecture
  * [Design Overview](1.overview/3.design-and-architecture/1.design-and-architecture.md)
  * [Storage Architecture](1.overview/3.design-and-architecture/2.storage-design.md)
  * [Query Engine](1.overview/3.design-and-architecture/3.query-engine.md)

## Query Language (for All Users)

* Data Types
  * [Data Types](2.query-language/1.data-types/data-types.md)
  * [Type Conversion](2.query-language/1.data-types/type-conversion.md)
* Functions and Operators
  * [Bitwise Operators](2.query-language/2.functions-and-operators/bitwise-operators.md)
  * [Built-In Functions](2.query-language/2.functions-and-operators/built-in-functions.md)
  * [Comparison Functions And Operators](2.query-language/2.functions-and-operators/comparison-functions-and-operators.md)
  * [Group By Function](2.query-language/2.functions-and-operators/group-by-function.md)
  * [Limit Syntax](2.query-language/2.functions-and-operators/limit-syntax.md)
  * [Logical Operators](2.query-language/2.functions-and-operators/logical-operators.md)
  * [Order By Function](2.query-language/2.functions-and-operators/order-by-function.md)
  * [Set Operations](2.query-language/2.functions-and-operators/set-operations.md)
  * [String Comparison Functions and Operators](2.query-language/2.functions-and-operators/string-comparison-functions-and-operators.md)
  * [uuid Function](2.query-language/2.functions-and-operators/uuid.md)
* Language Structure
  * Literal Values
    * [Boolean Literals](2.query-language/3.language-structure/literal-values/boolean-literals.md)
    * [Numeric Literals](2.query-language/3.language-structure/literal-values/numeric-literals.md)
    * [String Literals](2.query-language/3.language-structure/literal-values/string-literals.md)
  * [Comment Syntax](2.query-language/3.language-structure/comment-syntax.md)
  * [Identifier Case Sensitivity](2.query-language/3.language-structure/identifier-case-sensitivity.md)
  * [Keywords and Reserved Words](2.query-language/3.language-structure/keywords-and-reserved-words.md)
  * [Pipe Syntax](2.query-language/3.language-structure/pipe-syntax.md)
  * [Property Reference](2.query-language/3.language-structure/property-reference.md)
  * [Schema Object Names](2.query-language/3.language-structure/schema-object-names.md)
  * [Statement Composition](2.query-language/3.language-structure/statement-composition.md)
  * [User-Defined Variables](2.query-language/3.language-structure/user-defined-variables.md)
* Statement Syntax
  * Data Definition Statements
    * [Alter Edge Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/alter-edge-syntax.md)
    * [Alter Tag Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/alter-tag-syntax.md)
    * [Create Space Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/create-space-syntax.md)
    * [Create Edge Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/create-edge-syntax.md)
    * [Create Tag Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/create-tag-syntax.md)
    * [Drop Edge Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/drop-edge-syntax.md)
    * [Drop Space Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/drop-space-syntax.md)
    * [Drop Tag Syntax](2.query-language/4.statement-syntax/1.data-definition-statements/drop-tag-syntax.md)
    * [Index](2.query-language/4.statement-syntax/1.data-definition-statements/index.md)
    * [TTL (time-to-live)](2.query-language/4.statement-syntax/1.data-definition-statements/TTL.md)
  * Data Query and Manipulation Statements
    * [Delete Edge Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/delete-edge-syntax.md)
    * [Delete Vertex Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/delete-vertex-syntax.md)
    * [Fetch Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/fetch-syntax.md)
    * [Go Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/go-syntax.md)
    * [Insert Edge Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/insert-edge-syntax.md)
    * [Insert Vertex Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/insert-vertex-syntax.md)
    * [Lookup Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/lookup-syntax.md)
    * [Return Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/return-syntax.md)
    * [Update Edge Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/update-edge-syntax.md)
    * [Update Vertex Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/update-edge-syntax.md)
    * [Upsert Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/upsert-syntax.md)
    * [Where Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/where-syntax.md)
    * [Yield Syntax](2.query-language/4.statement-syntax/2.data-query-and-manipulation-statements/yield-syntax.md)

  * Utility Statements
    * Show Statements
      * [Show Charset Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-charset-syntax.md)
      * [Show Collation Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-collation-syntax.md)
      * [Show Configs Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-configs-syntax.md)
      * [Show Create Spaces Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-create-space-syntax.md)
      * [Show Create Tag/Edge Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-create-tag-edge-syntax.md)
      * [Show Hosts Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-hosts-syntax.md)
      * [Show Indexes Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-indexes-syntax.md)
      * [Show Parts Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-parts-syntax.md)
      * [Show Roles Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-roles-syntax.md)
      * [Show Snapshots Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-snapshots-syntax.md)
      * [Show Spaces Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-spaces-syntax.md)
      * [Show Tag/Edge Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-tags-edges-syntax.md)
      * [Show Users Syntax](2.query-language/4.statement-syntax/3.utility-statements/show-statements/show-users-syntax.md)
    * [Describe Syntax](2.query-language/4.statement-syntax/3.utility-statements/describe-syntax.md)
    * [Use Syntax](2.query-language/4.statement-syntax/3.utility-statements/use-syntax.md)

  * Graph Algorithms
    * [Find Path Syntax](2.query-language/4.statement-syntax/4.graph-algorithms/find-path-syntax.md)

## Build Develop and Administration (for Developers and DBA)

* Build
  * [Build Source Code](3.build-develop-and-administration/1.build/1.build-source-code.md)
  * [Build By Docker](3.build-develop-and-administration/1.build/2.build-by-docker.md)
* Install
  * [rpm Installation](3.build-develop-and-administration/2.install/1.install-with-rpm-deb.md)
  * [Start and Stop Services](3.build-develop-and-administration/2.install/2.start-stop-service.md)
  * [Deploying Cluster](3.build-develop-and-administration/2.install/4.cluster-deploy.md)
* Configuration
  * [System Requirement](3.build-develop-and-administration/3.configurations/0.system-requirement.md)
  * [Config Persistency and Priority](3.build-develop-and-administration/3.configurations/1.config-persistency-and-priority.md)
  * [CONFIG Syntax](3.build-develop-and-administration/3.configurations/2.configs-syntax.md)
  * [Metad Configuration](3.build-develop-and-administration/3.configurations/3.meta-config.md)
  * [Graphd Configuration](3.build-develop-and-administration/3.configurations/4.graph-config.md)
  * [Storaged Configuration](3.build-develop-and-administration/3.configurations/5.storage-config.md)
  * [Console Configuration](3.build-develop-and-administration/3.configurations/6.console-config.md)
  * [Kernel Configuration](3.build-develop-and-administration/3.configurations/7.kernel-config.md)
  * [Single Node Log](3.build-develop-and-administration/3.configurations/8.single-node-log.md)
* Account Management Statement
  * [Alter User Syntax](3.build-develop-and-administration/4.account-management-statements/alter-user-syntax.md)
  * [Authentication](3.build-develop-and-administration/4.account-management-statements/authentication.md)
  * [Built-in Roles](3.build-develop-and-administration/4.account-management-statements/built-in-roles.md)
  * [Change Password](3.build-develop-and-administration/4.account-management-statements/change-password.md)
  * [Create User](3.build-develop-and-administration/4.account-management-statements/create-user-syntax.md)
  * [Drop User](3.build-develop-and-administration/4.account-management-statements/drop-user-syntax.md)
  * [Grant Role](3.build-develop-and-administration/4.account-management-statements/grant-role-syntax.md)
  * [LDAP](3.build-develop-and-administration/4.account-management-statements/LDAP.md)
  * [Revoke](3.build-develop-and-administration/4.account-management-statements/revoke-syntax.md)
* Batch Data Management
  * Data Import
    <!-- * [Download And Ingest .sst File](3.build-develop-and-administration/5.storage-service-administration/data-import/download-and-ingest-sst-file.md) -->
    * [Import .csv File](3.build-develop-and-administration/5.storage-service-administration/data-import/import-csv-file.md)
    * [Spark Writer](3.build-develop-and-administration/5.storage-service-administration/data-import/spark-writer.md)
  * Data Export
    * [Dump Tool](3.build-develop-and-administration/5.storage-service-administration/data-export/dump-tool.md)
  * [Storage Balance](3.build-develop-and-administration/5.storage-service-administration/storage-balance.md)
  * [Cluster Snapshot](3.build-develop-and-administration/5.storage-service-administration/cluster-snapshot.md)
  * [Long Time-Consuming Task Management](3.build-develop-and-administration/5.storage-service-administration/job-manager.md)
  * [Compact](3.build-develop-and-administration/5.storage-service-administration/compact.md)
* Monitoring and Statistics
  <!-- * [Connect Prometheus](3.build-develop-and-administration/7.monitor/0.connect-prometheus.md) -->
  * [Metrics](3.build-develop-and-administration/7.monitor/1.metrics-exposer.md)
  * [Meta Metrics](3.build-develop-and-administration/7.monitor/2.meta-metrics.md)
  * [Storage Metrics](3.build-develop-and-administration/7.monitor/3.storage-metrics.md)
  * [Graph Metrics](3.build-develop-and-administration/7.monitor/4.graph-metrics.md)
* Development and API
  <!-- * [Key Value API](3.build-develop-and-administration/6.develop-and-interface/kv-interfaces.md) -->
  * [Nebula Graph Clients](1.overview/2.quick-start/3.supported-clients.md)

## Contributions (for Contributors)

* [Contribute to Documentation](4.contributions/contribute-to-documentation.md)
* [Cpp Coding Style](4.contributions/cpp-coding-style.md)
* [Developer Documentation Style Guide](4.contributions/developer-documentation-style-guide.md)
* [How to Contribute](4.contributions/how-to-contribute.md)

## Appendix

* [Gremlin V.S. nGQL](5.appendix/gremlin-ngql.md)
* [Cypher V.S. nGQL](5.appendix/cypher-ngql.md)
* [SQL V.S. nGQL](5.appendix/sql-ngql.md)
<!-- * [Upgrading Nebula Graph](5.appendix/upgrade-guide.md)-->

## Misc

### Video

* [YouTube](https://www.youtube.com/channel/UC73V8q795eSEMxDX4Pvdwmw/)
* [bilibili](https://space.bilibili.com/472621355)
