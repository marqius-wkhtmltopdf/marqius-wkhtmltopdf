No change to how documents convert: 0.12.12 makes the same PDFs as 0.12.11, so upgrading is optional.

Every file below was built by this repository's release workflow on GitHub's own machines, with build provenance and a software bill of materials (SBOM). Check a file before you run it:

```
gh attestation verify marqius-wkhtmltopdf-linux-x86_64 -R marqiushq/marqius-wkhtmltopdf
```

Check a Docker image with:

```
gh attestation verify oci://marqius/wkhtmltopdf:0.12.12 -R marqiushq/marqius-wkhtmltopdf
```
