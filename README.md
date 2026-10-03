# mssql-recovery-tool
Read-only MSSQL recovery utility to repair corrupted MDF/NDF database files and damaged SQL Server backups, recover dropped tables and lost records.
# MSSQL Database Recovery Tool
A read-only forensic recovery tool for Microsoft SQL Server.

## Overview
This tool performs offline, read-only analysis on SQL Server raw database files and backup files.
It parses database page structures directly, extracts usable data from damaged MDF, NDF and corrupted backup files without writing any changes to your source evidence.

## Supported Versions
- SQL Server 2005 ~ SQL Server 2025

## Core Capabilities
- Recover data from corrupted MDF / NDF primary & secondary database files
- Repair and extract data from damaged SQL backup (.bak) files, including compressed backups
- Read and salvage data from broken database files when SQL Server cannot attach
- Preview recoverable tables and records before export
- **100% read-only scan**: source files will never be modified during analysis

## Use Cases
- Database file corruption
- Damaged / broken backup files
- SQL Server fails to attach MDF
- Data rescue from disk image copies

## Important Notice
This is an offline forensic analysis tool.
We do NOT write or modify the original database files during scanning.
Always work on copies or disk images for evidence safety.

## Contact
For technical feedback and feature requests, please open GitHub issues.
