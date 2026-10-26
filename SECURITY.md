# Reporting a security concern

Please use [private vulnerability reporting](https://github.com/francismontalbo/mammography-model-selection/security/advisories/new) for exposed credentials, accidental disclosure of personal data or unsafe code. Include the affected release and file, a short explanation and sanitized steps to reproduce the issue. Please do not send patient records, access tokens or restricted images.

For scientific questions or corrections, use [public issues](https://github.com/francismontalbo/mammography-model-selection/issues). Avoid posting security details there while a concern is being investigated.

## Using the research files

Check downloads against `ALL_ASSET_CHECKSUMS.sha256` and follow [REPRODUCTION.md](REPRODUCTION.md). Use a separate environment. Historical training controllers are for inspection and should not be run unchanged. Never load checkpoints from an untrusted source.

The published packages preserve the study's recorded environment. They are not a maintained clinical application. Dependency alerts in this repository do not establish that code inside release archives is free of vulnerabilities.

Security corrections should identify the affected version and describe any replacement files. Keep the original scientific evidence traceable rather than silently changing results.
