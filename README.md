# CxMigrate

This tool provides a more granular approach to data migration from legacy Checkmarx SAST environments to the new CheckmarxOne platform. 

After configuring CxMigrate to connect to a legacy CxSAST and a CheckmarxOne environment, the tool provides you with an interface to select individual projects, teams, users, custom queries, and scan-results to be migrated to CheckmarxOne. CxMigrate has a configurable policy allowing you to define how various items are migrated - for example to control access to items, to control the organization of projects under CheckmarxOne Groups and Applications, as well as a variety of other settings. Items can be migrated and renamed, custom queries can be edited in the CxMigrate user interface to resolve compilation issues, and scans can be migrated including running a new scan in CheckmarxOne using the source code from the previous scan in legacy CxSAST.

This is the public repo for releases of CxMigrate - the source code is in a private repository.

Please raise issues here in Github for any errors, failures, or feature requests.
