# Marqius — drop-in replacement for wkhtmltopdf in 14 libraries

**wkhtmltopdf is archived. Keep your code working.**

Your application still needs to send invoices, statements and reports every day. Marqius by **Simple AI LLC** is a maintained, Rust-based HTML-to-PDF converter for applications that start the `wkhtmltopdf` executable. Keep your HTML templates, PDF calls and wrapper library; configure the Marqius binary and check your output before switching production.

[Find your library](https://github.com/marqius-wkhtmltopdf/marqius-wkhtmltopdf-examples#pick-your-library) · [See a real PDF comparison](https://marqius.com/download/launch-2026-11-20/marqius-wkhtmltopdf-same-html-comparison.pdf) · [Try 30 days, no card](https://marqius.com/wkhtmltopdf-buy/)

[![Marqius: keep your code, upgrade your PDFs](https://raw.githubusercontent.com/marqius-wkhtmltopdf/marqius-wkhtmltopdf-examples/codex/initial-examples/assets/cover.webp)](https://marqius.com/wkhtmltopdf/)

## Start with the code you already have

[![Examples CI](https://github.com/marqius-wkhtmltopdf/marqius-wkhtmltopdf-examples/actions/workflows/render-examples.yml/badge.svg)](https://github.com/marqius-wkhtmltopdf/marqius-wkhtmltopdf-examples/actions/workflows/render-examples.yml)

The [public examples repository](https://github.com/marqius-wkhtmltopdf/marqius-wkhtmltopdf-examples) includes **14 runnable PDF integrations**: python-pdfkit, django-wkhtmltopdf, KnpLabs Snappy, laravel-snappy, phpwkhtmltopdf, KnpSnappyBundle, CakePdf, wicked_pdf, PDFKit for Ruby, wkhtmltopdf for Node.js, go-wkhtmltopdf, java-wkhtmltopdf-wrapper, pdf_generator for Elixir, and Rotativa.AspNetCore.

Its integration CI checks that each example creates a PDF containing the expected invoice text. The README separately records dated upstream-suite results from the manual, including which suites test wrapper code without running the converter.

| Your stack | Switching guide |
| --- | --- |
| Python, Django, Flask, pdfkit and imgkit | [Python guide](https://marqius.com/wkhtmltopdf/python/) |
| PHP, Laravel, Snappy and laravel-snappy | [PHP and Laravel guide](https://marqius.com/wkhtmltopdf/laravel-php/) |
| Ruby, Rails, wicked_pdf and PDFKit | [Ruby and Rails guide](https://marqius.com/wkhtmltopdf/rails-ruby/) |
| .NET on Linux, Rotativa and Wkhtmltopdf.NetCore | [.NET guide](https://marqius.com/wkhtmltopdf/dotnet/) |
| Node.js and Go wrappers | [Node.js and Go guide](https://marqius.com/wkhtmltopdf/node-go/) |
| Docker images and CI runners | [Docker guide](https://marqius.com/wkhtmltopdf/docker/) |

## See the PDFs before you switch

The [same-HTML invoice comparison](https://marqius.com/download/launch-2026-11-20/marqius-wkhtmltopdf-same-html-comparison.pdf) contains a side-by-side overview, both original full pages, and the source and method. It uses wkhtmltopdf 0.12.6 (patched Qt) and Marqius 0.12.6 in the same Linux environment, with the same fonts and CLI flags, on **20 November 2026**. [Download the example pack](https://marqius.com/download/launch-2026-11-20/marqius-same-html-example.zip).

That is one document. Use your own invoices, reports or statements to check fonts, wrapping, tables, amounts, images, headers, footers and page breaks before production.

These integrations launch an executable. Marqius does not replace the `libwkhtmltox` shared library used by bindings such as DinkToPdf. Some option behavior differs, including custom table-of-contents XSL stylesheets; JavaScript-dependent pages may use installed Chrome or Chromium. The [developer manual](https://marqius.com/download/developer-manual.pdf) explains the boundaries.

## Install, evaluate and get help

- [Official downloads and installation](https://marqius.com/wkhtmltopdf/download/) — Linux x86-64, Linux ARM64 and Apple silicon Macs.
- [Developer manual](https://marqius.com/download/developer-manual.pdf) — integration settings, CLI behavior and measured compatibility results.
- [Docker Hub: marqius/wkhtmltopdf](https://hub.docker.com/r/marqius/wkhtmltopdf) · [Homebrew tap](https://github.com/marqius-wkhtmltopdf/homebrew-tap).
- [Security and untrusted HTML guidance](https://marqius.com/wkhtmltopdf/security/).
- [Watch the introduction](https://youtu.be/KFKbbDIYvXc) · [hello@marqius.com](mailto:hello@marqius.com).

**30-day trial. No card required.** This wkhtmltopdf edition is **$10 USD per Client per month** or **$500 USD per Client for a lifetime licence with upgrades**, plus applicable taxes. A Client is a legal entity under the [licence](https://marqius.com/wkhtmltopdf/licence-agreement/). [Trial and plans](https://marqius.com/wkhtmltopdf-buy/).

The upstream [wkhtmltopdf repository was archived on 2 January 2023](https://github.com/wkhtmltopdf/wkhtmltopdf); its [status page](https://wkhtmltopdf.org/status.html) explains the aging Qt/WebKit stack. Marqius is independent of that project. The converter is proprietary software from Simple AI LLC; the integration examples are MIT licensed. Other product names identify integrations and belong to their respective owners.
