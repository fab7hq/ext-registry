# Contributing to the Fab7 Extension Registry

The registry contains reviewed metadata only. Extension source and release
artifacts remain owned by their publisher repositories.

## Propose a catalog change

1. Publish an immutable tagged source archive in the extension's own repository.
2. Compute and provide its SHA-256 digest.
3. Open the focused extension-submission issue before a pull request.
4. Update `catalog.yaml`, preserve canonical name sorting, and increment
   `catalog_version` whenever catalog bytes change.
5. Validate the catalog with the command documented in [README.md](README.md).

Keep each change to one catalog outcome. Catalog review establishes metadata
and source identity, not semantic correctness or execution authority.

By submitting a contribution, you agree that it is licensed under the
[Apache License 2.0](LICENSE).
