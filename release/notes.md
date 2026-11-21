**ERPNext 15 and 16 supported.**

- Header and footer scripts, such as the one that writes "Page 1 of 3", run even with `--disable-javascript`, as they do in wkhtmltopdf.
- A document that ends with a page break no longer gets an empty last page.
- Form fields print as they do in wkhtmltopdf.
- When a page or a picture answers with an error, such as a website refusing the request, the message names the address and the status, in wkhtmltopdf's words.
- Without a licence, each page now reads "Prepared by Marqius, Purchase Licence", linking to the plans.
- Free Community licence keys, for personal, teaching and open-source use, are accepted.

Every file below was built by this repository's release workflow on GitHub's own machines, with build provenance and a software bill of materials (SBOM). Check a file before you run it:

```
gh attestation verify marqius-wkhtmltopdf-linux-x86_64 -R marqiushq/marqius-wkhtmltopdf
```

Check a Docker image with:

```
gh attestation verify oci://marqius/wkhtmltopdf:0.12.13 -R marqiushq/marqius-wkhtmltopdf
```
