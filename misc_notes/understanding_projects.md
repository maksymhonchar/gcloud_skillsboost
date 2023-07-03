- Projects are the basis for utilizing Cloud services

- GCloud resource hierarchy:
    1. Resources
        - virtual machines, cloud storage buckets, tables in bigquery, ...
    2. Projects
        - Projects are separate entities under the Organization node
        - Projects hold resources, each of which belongs to just x1 Projects
        - Projects can have different owners and users
        - Projects are billed separately
    3. Folders
        - or subfolders :)
        - folders allow you to group resources on a per-department basis
        - organization node is needed
    4. Organization node
        - stands at the top level
        - encompasses all the projects, folders, and resources in your organization

- Each GCloud project has x3 identifying attributes:
    1. project ID
    2. project Name
    3. project Number
