# Security Policy

## Reporting a Vulnerability

For any abuse reports or security concerns, please open an issue in this repository.

We take all reports seriously and will respond within 48 hours.

## Scope

This tool cleans the shader cache and edits local configuration files. It does not:

- Inject DLLs into game processes
- Modify game memory
- Alter game installation or save files
- Access network resources
- Collect telemetry

Every configuration change writes a timestamped backup first, so any modification can be reverted in one click. If you believe a release behaves differently, open an issue with the version number and the steps that produced it.