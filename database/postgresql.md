https://www.postgresql.org/

https://www.pgadmin.org/

https://github.com/dhamaniasad/awesome-postgres

https://pgmodeler.io/

https://news.ycombinator.com/item?id=25910277

https://www.slony.info/

# SQL

https://postgres.cz/wiki/PostgreSQL_SQL_Tricks_III

https://news.ycombinator.com/item?id=23516947

https://hashrocket.com/blog/posts/custom-aggregates-in-postgresql

https://www.narrator.ai/blog/postgres-missing-datediff-function/
> https://lobste.rs/s/mxhevf/postgresql_s_missing_datediff_function
> select justify_interval('2021-06-04'::timestamp with time zone - '2020-04-06 23:53:45');

https://www.cybertec-postgresql.com/en/postgresql-limit-vs-fetch-first-rows-with-ties/
> https://news.ycombinator.com/item?id=27845360

https://notes.eatonphil.com/exploring-plpgsql.html

## JSON
https://blog.crunchydata.com/blog/generating-json-directly-from-postgres
> https://news.ycombinator.com/item?id=27848085

http://coussej.github.io/2016/01/14/Replacing-EAV-with-JSONB-in-PostgreSQL/

https://blog.crunchydata.com/blog/better-json-in-postgres-with-postgresql-14
> https://news.ycombinator.com/item?id=27358977

## Types
https://blog.jonudell.net/2021/07/27/working-with-postgres-types/
> https://news.ycombinator.com/item?id=28095264

https://github.com/vramework/postgres-typed
> https://news.ycombinator.com/item?id=28326117

# Performance
https://explain.depesz.com/
> https://news.ycombinator.com/item?id=28771875

https://scalegrid.io/blog/introduction-to-auto-explain-postgres/

https://about.gitlab.com/blog/2021/09/29/why-we-spent-the-last-month-eliminating-postgresql-subtransactions/
> https://news.ycombinator.com/item?id=28730225
 
https://www.migops.com/blog/2021/04/09/pgbackrest-the-best-postgres-backup-tool-with-a-very-active-community/#Conclusion

https://github.com/ankane/pgvector vector similarity search
> https://news.ycombinator.com/item?id=26903105

http://eradman.com/ephemeralpg/

https://elephant-shed.io/

https://www.cybertec-postgresql.com/en/postgresql-detecting-slow-queries-quickly/

https://github.com/plv8/plv8

https://github.com/agroal/pgagroal High-performance protocol-native connection pool
> https://news.ycombinator.com/item?id=29303627

## Index
http://leopard.in.ua/2015/04/13/postgresql-indexes/

https://www.i-programmer.info/news/84-database/14855-a-deep-dive-into-postgresql-indexes.html

https://blog.crunchydata.com/blog/postgres-indexes-for-newbies
> https://news.ycombinator.com/item?id=30001964

## Analysis
https://blog.crunchydata.com/blog/get-started-with-explain-analyze

https://github.com/marklit/datafluent_pg

https://www.percona.com/blog/improve-postgresql-query-performance-insights-with-pg_stat_monitor/

https://brandur.org/idempotency-keys

https://www.pgmustard.com/

### Debug
https://iamsafts.com/posts/postgres-gin-performance/
> https://news.ycombinator.com/item?id=27152507

https://www.cybertec-postgresql.com/en/how-to-interpret-postgresql-explain-analyze-output/

https://dev.to/jbranchaud/beware-the-missing-foreign-key-index-a-postgres-performance-gotcha-3d5i

# Admin
https://supabase.io/blog/2021/07/01/roles-postgres-hooks
> https://news.ycombinator.com/item?id=27712800

# Extensions
https://age.apache.org/# Graph

https://supabase.com/blog/2021/12/03/pg-graphql
> https://news.ycombinator.com/item?id=29430720
> https://www.getmotoradmin.com/supabase
> > https://news.ycombinator.com/item?id=30100077
> > > https://directus.io/

https://github.com/solidsnack/GraphpostgresQL

https://github.com/arkhipov/temporal_tables Table that records the period of time when a row is valid.

https://github.com/nearform/temporal_tables
> https://news.ycombinator.com/item?id=26748096

https://depth-first.com/articles/2021/09/07/a-rust-postgresql-extension-for-cas-numbers/

https://postgrest.org/en/v9.0/releases/v9.0.0.html
> https://news.ycombinator.com/item?id=29389576
> https://github.com/PostgREST/postgrest 

# Security
https://goteleport.com/blog/securing-postgres-postgresql/
> https://news.ycombinator.com/item?id=26674756

https://www.cisecurity.org/benchmark/postgresql/
  
# Operations

https://heap.io/blog/how-postgres-audit-tables-saved-us-from-taking-down-production

https://www.highgo.ca/2021/01/27/avoiding-identifying-and-dealing-with-postgresql-database-corruption-part-1/

https://www.mutuallyhuman.com/blog/how-a-read-query-can-write-to-disk-a-postgresql-story/ work_mem
> https://news.ycombinator.com/item?id=29056405
> > https://wiki.postgresql.org/wiki/Tuning_Your_PostgreSQL_Server

https://incident.io/blog/one-two-skip-a-few Postgres sequences can skip 32 unexpectedly
> https://news.ycombinator.com/item?id=27843084

## Audit
https://supabase.com/blog/2022/03/08/audit
> https://news.ycombinator.com/item?id=30615470
> https://www.reddit.com/r/programming/comments/tpj6zk/postgres_auditing_in_150_lines_of_sql/

## Backup
https://abishekmuthian.com/backup-postgresql-to-cloud/

## OOM
https://info.crunchydata.com/blog/deep-postgresql-thoughts-the-linux-assassin

# Migration
https://github.com/sastraxi/pgsh

https://github.com/djrobstep/migra
> https://news.ycombinator.com/item?id=16673526
> https://news.ycombinator.com/item?id=30464882

https://blog.discourse.org/2021/04/standing-on-the-shoulders-of-a-giant-elephant/

https://www.paulox.net/2021/05/28/upgrading-postgresql-from-version-12-to-13-on-ubuntu-21-04-focal-fossa/

https://engineering.theblueground.com/blog/zero-downtime-postgres-migration-done-right/

https://fabianlindfors.se/blog/schema-migrations-in-postgres/
> https://news.ycombinator.com/item?id=27531934
> > https://dba.stackexchange.com/questions/195104/postgres-group-by-id-works-on-table-directly-but-not-on-identical-view

https://www.migops.com/blog/2021/08/27/announcing-pg_dbms_job-in-postgresql-for-oracle-dbms_job-compatibility/

https://news.ycombinator.com/item?id=28707577
> https://vericred.com/how-we-migrated-a-1tb-database-from-heroku-to-aws-aurora-with-almost-no-downtime/

https://babelfishpg.org/
> https://github.com/babelfish-for-postgresql SQL server compatibility layer by AWS

https://fabianlindfors.se/blog/schema-migrations-in-postgres-using-reshape/
> https://news.ycombinator.com/item?id=29825520

https://github.com/fabianlindfors/reshape

https://github.com/bikeshedder/tusker

https://retool.com/blog/how-we-upgraded-postgresql-database/
> https://news.ycombinator.com/item?id=31084147

# HA
https://dzone.com/articles/managing-high-availability-in-postgresql-part-i

https://github.com/zalando/patroni

https://fly.io/blog/globally-distributed-postgres/
> https://news.ycombinator.com/item?id=27690950

https://www.notion.so/blog/sharding-postgres-at-notion
> https://news.ycombinator.com/item?id=28776786

https://tapoueh.org/blog/2021/12/postgres-ha-roles-are-dynamic

# Generator
https://github.com/vramework/schemats Postgres to TypeScript Interfaces and Enums
> https://news.ycombinator.com/item?id=27570058

# Extensions
https://github.com/jie123108/imgsmlr-server

# Search
https://about.sourcegraph.com/blog/postgres-text-search-balancing-query-time-and-relevancy/
> https://news.ycombinator.com/item?id=28873779

# Queue
https://spin.atomicobject.com/2021/02/04/redis-postgresql/
> https://news.ycombinator.com/item?id=27482243

# Realtime
https://github.com/supabase/realtime Listen to your to PostgreSQL database in realtime via WebSockets (Erlang/Elixir)
> https://news.ycombinator.com/item?id=26968449

# Proxy

## NoSQL
https://www.mangodb.io/
> https://news.ycombinator.com/item?id=29071623

# Container
https://www.kubegres.io/
> https://www.reddit.com/r/PostgreSQL/comments/mqrsbn/kubegres_is_a_kubernetes_operator_for_postgresql/

https://www.postgresql.org/about/news/kubegres-is-available-as-open-source-2197/
> https://news.ycombinator.com/item?id=28758162
 
## K8S
https://stackgres.io/
> https://news.ycombinator.com/item?id=28865432

https://blog.crunchydata.com/blog/postgresql-14-on-kubernetes
> https://news.ycombinator.com/item?id=28767637

https://stackgres.io/blog/easily-running-babelfish-for-postgresql-on-kubernetes/

# News
https://pganalyze.com/blog/how-postgres-chooses-index
> https://news.ycombinator.com/item?id=31115492

https://splitmind.dev/posts/generate-creds-postgres-vault-with-golang/
> https://news.ycombinator.com/item?id=31072936

https://bytebase.com/blog/database-migration-sqlite-to-postgresql
> https://news.ycombinator.com/item?id=31038614

https://postgrespro.com/blog/pgsql/5968022 Locks in PostgreSQL: 4. Locks in memory

https://github.com/postgres-ai/database-lab-engine/releases/tag/v3.1.0

https://www.highgo.ca/2021/07/23/the-amazing-buffer-tag-in-postgresql/

https://blog.crunchydata.com/blog/announcing-postgres-container-apps-easy-deploy-postgres-apps
> https://news.ycombinator.com/item?id=30867644

https://github.com/vitabaks/postgresql_cluster

https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=7103ebb7aae8ab8076b7e85f335ceb8fe799097c

https://github.com/gurjeet/pg_plan_guarantee
> https://news.ycombinator.com/item?id=30825069

https://github.com/porsager/postgres js
> https://news.ycombinator.com/item?id=30794332

https://eggerapps.at/postico/ A Modern PostgreSQL Client for the Mac
> https://news.ycombinator.com/item?id=30798274

https://www.tangramvision.com/blog/hands-on-with-postgresql-authorization-part-2-row-level-security
> https://news.ycombinator.com/item?id=30700899

https://arctype.com/blog/postgresql-hooks/

https://news.ycombinator.com/item?id=30629430 A word used only by Postgres developers

https://github.com/ossc-db/pg_hint_plan
> https://news.ycombinator.com/item?id=30614154

https://www.shayon.dev/post/2022/47/pg-osc-zero-downtime-schema-changes-in-postgresql/
> https://news.ycombinator.com/item?id=30579847

https://www.yagiz.co/postgresql-index-performance/

https://gist.github.com/jcoleman/1e6ad1bf8de454c166da94b67537758b Schema Change Guide
> https://news.ycombinator.com/item?id=30458580

https://www.shayon.dev/post/2022/47/pg-osc-zero-downtime-schema-changes-in-postgresql/

https://alexklibisz.com/2022/02/18/optimizing-postgres-trigram-search.html
> https://news.ycombinator.com/item?id=30433269

https://www.youtube.com/watch?v=j7UPVU5UCV4 Intro to Postgres Planner - Hacking Melanie Plageman

https://github.com/shayonj/pg-online-schema-change

https://blog.yugabyte.com/postgresql-timestamps-timezones/
> https://news.ycombinator.com/item?id=30318751

https://www.citusdata.com/blog/2018/02/22/seven-tips-for-dealing-with-postgres-locks/
> https://news.ycombinator.com/item?id=30316653

https://github.com/levkk/pgcat Show HN: PgCat, Postgres pooler with sharding, load balancing and failover
> https://news.ycombinator.com/item?id=30267539

https://datastation.multiprocess.io/blog/2022-02-08-the-world-of-postgresql-wire-compatibility.html
> https://news.ycombinator.com/item?id=30284538

https://ketansingh.me/posts/how-postgres-stores-rows/
> https://news.ycombinator.com/item?id=30279986

https://wiki.postgresql.org/wiki/Don%27t_Do_This
> https://news.ycombinator.com/item?id=30298736

https://ardentperf.com/2022/02/10/a-hairy-postgresql-incident/
> https://news.ycombinator.com/item?id=30296490

https://www.depesz.com/2022/02/06/waiting-for-postgresql-15-add-unique-null-treatment-option/

https://www.splitgraph.com/blog/postgresql-fdw-aggregation-pushdown-multicorn-part-1

https://www.evanjones.ca/postgres-large-json-performance.html

https://rclayton.silvrback.com/distributed-locking-with-postgres-advisory-locks

https://github.com/postgres-ai/database-lab-engine
> https://news.ycombinator.com/item?id=30068669

https://github.com/jorzel/postgres-full-text-search

https://www.dolthub.com/blog/2022-01-26-creating-a-postgres-foreign-data-wrapper/
> https://news.ycombinator.com/item?id=30089884

https://www.interdb.jp/pg/index.html The Internals of PostgreSQL
> https://news.ycombinator.com/item?id=30086374

https://spacelift.io/blog/tricking-postgres-into-using-query-plan
> https://news.ycombinator.com/item?id=29981737

https://postgres.ai/blog/20220114-progress-bar-for-postgres-queries-lets-dive-deeper

https://rhaas.blogspot.com/2022/01/who-contributed-to-postgresql.html
> https://news.ycombinator.com/item?id=29910327

https://www.adyen.com/blog/updating-a-50-terabyte-postgresql-database
> https://news.ycombinator.com/item?id=29923303
> > https://www.slony.info/

https://blog.crunchydata.com/blog/five-tips-for-a-healthier-postgres-database-in-the-new-year
> https://news.ycombinator.com/item?id=29858083

https://heap.io/blog/optimizing-postgres-queries-at-scale
> https://news.ycombinator.com/item?id=29715872

https://blog.crunchydata.com/blog/randomly-sampling-data-using-sql-and-postgresql

https://jezenthomas.com/fast-counting-with-postgresql-and-haskell/

https://pawelurbanek.com/postgresql-fix-performance

https://vadosware.io/post/everything-ive-seen-on-optimizing-postgres-on-zfs-on-linux/
> https://news.ycombinator.com/item?id=29647645

https://github.com/supabase/supabase
> https://supabase.com/blog/2021/11/30/supabase-studio

https://github.com/eulerto/wal2json

https://schemaverse.com/
> https://news.ycombinator.com/item?id=29375911

https://www.postgresql.org/about/news/pgpool-ii-426-419-4016-3721-and-3628-released-2357/

https://eradman.com/posts/ephemeral-databases.html
> https://news.ycombinator.com/item?id=29248299

https://www.migops.com/blog/2021/11/15/postgresql-15-will-include-some-more-regexp-functions/

https://github.com/yandex/odyssey Advanced multi-threaded PostgreSQL connection pooler and request router
> https://news.ycombinator.com/item?id=29201000

https://www.postgresql.fastware.com/blog/what-is-the-new-lz4-toast-compression-in-postgresql-14
> https://news.ycombinator.com/item?id=29147656

https://hakibenita.com/postgresql-unknown-features
> https://news.ycombinator.com/item?id=29163319

https://www.enterprisedb.com/products/biganimal-cloud-postgresql

https://github.com/postgrespro/jsquery
> https://news.ycombinator.com/item?id=29069777

https://notes.eatonphil.com/exploring-plpgsql-forth-like.html

https://stackgres.io/blog/stackgres-1-0-0-open-source-postgres-aas-with-120-extensions/

https://blog.timescale.com/blog/function-pipelines-building-functional-programming-into-postgresql-using-custom-operators/
> https://news.ycombinator.com/item?id=28919205

https://www.migops.com/blog/2021/10/14/stored-procedure-out-parameters-in-postgresql-14/
> https://news.ycombinator.com/item?id=28878918

https://heap.io/blog/the-million-indexes-incident

https://www.postgresql.org/about/news/postgresql-14-released-2318/
> https://news.ycombinator.com/item?id=28705699

https://pgloader.io/ LISP
> https://news.ycombinator.com/item?id=28659076

https://blog.crunchydata.com/blog/postgres-14-its-the-little-things

https://www.depesz.com/2021/09/10/waiting-for-postgresql-15-revoke-public-create-from-public-schema-now-owned-by-pg_database_owner/
> https://news.ycombinator.com/item?id=28537870

[Postgres: Boundless `text` and Back Again](https://brandur.org/text) 
> https://news.ycombinator.com/item?id=28484312

https://www.cybertec-postgresql.com/en/index-bloat-reduced-in-postgresql-v14/
> https://news.ycombinator.com/item?id=28486623

https://postgres.ai/blog/20210831-postgresql-subtransactions-considered-harmful
> https://news.ycombinator.com/item?id=28374333

https://blog.timescale.com/blog/how-postgresql-aggregation-works-and-how-it-inspired-our-hyperfunctions-design-2/
> https://news.ycombinator.com/item?id=28075774

https://drewdevault.com/2021/08/05/In-praise-of-Postgres.html
> https://news.ycombinator.com/item?id=28075204

https://www.channable.com/tech/dbcritic-constructively-criticizing-your-postgres-schema
> https://news.ycombinator.com/item?id=27760073

https://www.postgresql.org/about/news/postgresql-14-beta-1-released-2213/
> https://news.ycombinator.com/item?id=27220725

https://www.postgresql.org/about/news/postgresql-133-127-1112-1017-and-9622-released-2210/

https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=1e55e7d1755cefbb44982fbacc7da461fa8684e6
> https://news.ycombinator.com/item?id=26756568

https://rbranson.medium.com/10-things-i-hate-about-postgresql-20dbab8c2791
> https://news.ycombinator.com/item?id=26709019

https://www.postgresql.org/about/news/1960/ PostgreSQL 11.5, 10.10, 9.6.15, 9.5.19, 9.4.24, and 12 Beta 3 Released! Sec Fixes

https://archive.fosdem.org/2019/schedule/event/postgresql_fsync/
> https://news.ycombinator.com/item?id=19119991
> https://news.ycombinator.com/item?id=30131165