ansible-templates-macros
=========

Contains files with all macros  & parameters by resources

Requirements
------------

None.

Directory structure
--------------

One folder by cloud provider containing 2 folders:

- macros
  - this folder contains one files by resources. This file (.j2) contains code to create json templates.
- params
  - this folder contains one file  by resources. This file (.yml) contains code defining parameters needed by that resources.

Folders 
- ../azure/macros
- ../azure/params
- ../aws/macros
- ../aws/params

File nomenclature
------------

File name represent category and resource type name with suffix 

- \<category>\-\<resourcetype>\-params.yml
- \<category>\-\<resourcetype>\-macros.j2

Example:

- compute-virtualmachine-params.yml
- compute-virtualmachine-macros.j2

Useful Links
----------------
https://docs.microsoft.com/en-US/azure/templates/

Author Information
------------------
Alan Pinard
Pascal S. Clermont