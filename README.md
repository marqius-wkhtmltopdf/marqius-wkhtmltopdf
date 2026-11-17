# Marqius: a maintained drop-in wkhtmltopdf replacement

[![Marqius — great documents, ready for print](https://marqius.com/images/marqius-social.jpg)](https://marqius.com/wkhtmltopdf/)

**Keep your application. Replace the PDF converter.**

Marqius by **Simple AI LLC** is a wkhtmltopdf-compatible HTML-to-PDF command-line program for generating invoices, reports, statements and other documents. It is designed for teams whose applications call the wkhtmltopdf executable.

Keep your templates and wrapper library, configure the Marqius executable, and compare the PDFs on your own documents before switching production.

[Explore Marqius](https://marqius.com/wkhtmltopdf/) · [Download and install](https://marqius.com/wkhtmltopdf/download/) · [Trial and licence plans](https://marqius.com/wkhtmltopdf-buy/) · [Contact](https://marqius.com/contact/)

## HTML-to-PDF workflows

| Your stack | Migration guide |
| --- | --- |
| Python, Django, Flask, pdfkit and imgkit | [Python guide](https://marqius.com/wkhtmltopdf/python/) |
| PHP, Laravel, Snappy and laravel-snappy | [PHP and Laravel guide](https://marqius.com/wkhtmltopdf/laravel-php/) |
| Ruby, Rails, wicked_pdf and PDFKit | [Ruby and Rails guide](https://marqius.com/wkhtmltopdf/rails-ruby/) |
| .NET on Linux, Rotativa and Wkhtmltopdf.NetCore | [.NET guide](https://marqius.com/wkhtmltopdf/dotnet/) |
| Node.js and Go wrappers | [Node.js and Go guide](https://marqius.com/wkhtmltopdf/node-go/) |
| Docker images and CI runners | [Docker guide](https://marqius.com/wkhtmltopdf/docker/) |

These guides cover integrations that launch an executable. Marqius does not replace the libwkhtmltox shared library used by integrations such as DinkToPdf.

## Start with one real document

After following the installation guide, render a PDF and compare it with your existing output:

```sh
marqius wkhtmltopdf --page-size A4 invoice.html invoice.pdf
marqius compare old.pdf invoice.pdf
```

Check fonts, images, headers, footers and page breaks before changing a production workflow. PDF output is not guaranteed to be identical.

Current direct downloads support **Linux x86-64**, **Linux ARM64** and **Apple silicon Macs**. The official installer verifies SHA-256 checksums and preserves an existing wkhtmltopdf installation unless you explicitly choose takeover.

## Downloads, documentation and repositories

- [Official download and installation guide](https://marqius.com/wkhtmltopdf/download/)
- [wkhtmltopdf switching manual (PDF)](https://marqius.com/download/replace-wkhtmltopdf.pdf)
- [Security and untrusted HTML guidance](https://marqius.com/wkhtmltopdf/security/)
- [Docker Hub: marqius/wkhtmltopdf](https://hub.docker.com/r/marqius/wkhtmltopdf) — `0.11.0` and `latest` support Linux AMD64 and ARM64.
- [Homebrew tap](https://github.com/marqius-wkhtmltopdf/homebrew-tap) — distribution setup is in progress; no installable cask or formula is published yet.

Marqius is proprietary software from Simple AI LLC. These repositories provide product documentation and distribution resources, not the engine source. See the [licence plans](https://marqius.com/wkhtmltopdf-buy/) for product terms.

Marqius is independent of the wkhtmltopdf project. Other product names identify migration paths and belong to their respective owners.
