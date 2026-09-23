# RomRaider2 Releases

Official public downloads for RomRaider2 ECU Studio.

The active development repository is private. This public repository is intentionally
limited to release downloads, checksums, release notes, and the exact corresponding
source required for each distributed GPL build.

Use the Releases section to download builds for supported platforms.
Release packages are prerelease/testing builds unless explicitly marked stable.

For every published build:
- compiled platform packages include SHA-256 checksum sidecars;
- exact corresponding source is attached as one or more release assets;
- each source archive and source manifest has a SHA-256 checksum sidecar;
- the browsable repository and release-tag tree contain only this README.

Normal future releases should build all packages from one immutable release tag and
therefore use one Corresponding_Source.zip. If qualified replacement packages were
built from different revisions, as happened for 1.1.12 RC1, the release includes
separate corresponding-source archives plus a manifest mapping each binary to its
source commit.

The source attachments expose released source only. They do not expose newer
unreleased development work or private task/audit state.
