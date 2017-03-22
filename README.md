ansible-templates-macros
=========

Contains files with all macros  & parameters by ressources

Requirements
------------

None.

Directory structure
--------------

One folder by cloud provider containing 2 folders:

- macros
  - this folder contains one files by resources. This file (.yml) contains code to create json templates.
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
- \<category>\-\<resourcetype>\-macros.yml

Example:

- compute-virtualmachine-params.yml
- compute-virtualmachine-macros.yml

Author Information
------------------
Alan Pinard
Pascal S. Clermont