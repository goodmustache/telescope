# Telescope

Telescope is an OSS utility for managing Pathfinder 2e / Starfinder 2e characters.

## Single Commit

Since GIT stores each commit (AKA files changed) in full, storing each change to the static website will cause the GIT repo for this project to become _extremely_ bloated.
In order to avoid excess bloat to this repository, the initial commit is always rewritten so that only a singe "version" of the static website is stored.
If a past version is necessary to be deployed, simply roll back to the target version, regenerate the static files, and then rewrite `HEAD` on the `static-site` branch.
