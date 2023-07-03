- Unstructured data:
    - Cloud Storage
- Relational databases:
    - Cloud SQL
    - Cloud Spanner
- NoSQL databases:
    - Firestore
    - Bigtable

- Unstructured data: information stored in a non-tabular form (Documents, Images, Audio files)
- Structured data: information stored in tables, rows and columns

- Types of structured daat:
    1. Transactional workload (online transaction processing systems - fast read/write/update) (only a portion of data is needed)
        - SQL? Local/regional scalability? -> Cloud SQL
        - SQL? Global scalability? -> Cloud Spanner
        - NoSQL? Firestore
    2. Analytical workload (entire dataset needs to be read)
        - SQL? -> BigQuery
        - NoSQL? -> Cloud BigTable
