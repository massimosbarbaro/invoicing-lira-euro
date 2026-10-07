# Fatture: invoicing program for the lira-euro changeover

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23186711.svg)](https://doi.org/10.5281/zenodo.23186711)

*Programma di fatturazione per il passaggio dalla lira all'euro*

2000–2003 · version 2000 Euro  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Fatture (“SE Fatture 2000 Euro”) is a small invoicing program for a professional practice. It manages customers and products, issues invoices with discounts, payment terms, delivery-note and order references and VAT, shows amounts in both lire and euro during the changeover period, and produces statistics by customer, product and month.

I designed and programmed this application in 2000–2003. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Customer and product registries with search windows.
- Invoices with discount, payment terms (direct remittance, bank transfer 30/60/90/120 days end of month), delivery note and customer order reference.
- Lira/euro double display and VAT computation in the printed invoice.
- Statistics by customer, by product and by month.
- Compact and repair of the database from the program.

## Data

Microsoft Access (Jet 4) database. Tables: `Cliente`, `Prodotto`, `Fattura`, `FatturaDettagli`, `CC`, `Parametri`, `UltimaFattura`, `UltimaRisposta`, `UltimoProdotto`.

## Technology

DAO / Jet 4, Crystal Reports 4.6 (OCX), DBGrid, Masked Edit, Common Controls.

## Repository contents

| Path | Content |
|---|---|
| `bin/Fatture.exe` | The compiled program (2003 build). |
| `bin/FattureRidotto.mdb` | Empty copy of the program database (structure only). |

## What is not included

The source code of this program has not survived; the repository publishes the compiled program as it was distributed, together with an **empty** copy of its database (every table emptied and the file compacted). The customer registry, invoices and report layouts are not included because they contain personal and business data.

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23186711](https://doi.org/10.5281/zenodo.23186711).

> Sbarbaro, Massimo. 2003. *Fatture: invoicing program for the lira-euro changeover*. Software (2000–2003), version 2000 Euro. Zenodo. https://doi.org/10.5281/zenodo.23186711.

## License

Released under the [MIT License](LICENSE). © 2000 Massimo Sbarbaro.
