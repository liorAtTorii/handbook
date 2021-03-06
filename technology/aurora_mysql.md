# Aurora MySQL
## Why SQL (or why not NO-SQL)?
We chose to work with a SQL storage for two main reasons:

* Proven technology. While not the latest hype, SQL is a safe bet. It is a proven technology than can handle high scale, and is known for data consistency.
* Relational data model - SQL works well when you can clearly model your data and there are strong relationships between the tables (as opposed to unstructured data). Torii data can clearly be modelled in terms of objects and relationships.

## Aurora

[Amazon Aurora (Aurora)](http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Aurora.Overview.html)  is a fully managed, MySQL- and PostgreSQL-compatible, relational database engine. It combines the speed and reliability of high-end commercial databases with the simplicity and cost-effectiveness of open-source databases.

Aurora benefits

* MySQL compatible
* Performance - Amazon Aurora provides five times the throughput of standard MySQL
* Storage Auto-Scaling (up to 64 TB)
* Scalabilty - easily scale up compute and memory resources with zero downtime
* Replication - Easily create up to 15 read replicas. Replication is performed in milliseconds
* Backups - Automated backups, stored in Amazon S3
* Point-in-Time Recovery - Fast recovery of the data by creating a new Aurora DB cluster from the backup data that Aurora retains, or from a DB cluster snapshot that you saved on S3
* High Availability - Amazon Aurora automatically maintains six copies of your data across three Availability Zones (AZs), and will automatically attempt to recover your database in a healthy AZ with no data loss.
* Patching—Staying Up-to-Date - Aurora will automatically update your database with the latest patches
