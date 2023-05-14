# Project Apollo
Apollo is a platform for managing SQL queries. Representatively, it includes query metadata management, query versioning, and query serving.

![image](https://github.com/Linho1150/apollo/assets/56428918/e212c8dc-c7b2-4039-a951-c8f57656c34e)

- Detail
  - Peach
    - Use to serve queries. It is also used to synchronize the system.
  - Cherry
    - Keep frequently used queries in cache to speed up.
  - Banana
    - Archive Query and related information. Metadata stored as a file in Github is imported into DB and managed as RAW DATA. Sync DB and Github according to the configuration. Reduce IO to import queries through Github.
  - Apple
    - Archive the metadata of the query to a file.
- Items to check
    - How often is the query called?
    - What should We do with github versioning structure?
    - Can We support Replica?
    - Which Configuration Should We Use?
