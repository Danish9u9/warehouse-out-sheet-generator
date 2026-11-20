# Warehouse Out-Sheet Generator

Browser-based tool that parses courier shipping label PDFs using PDF.js, deduplicates orders, verifies item quantities, and generates an auto-fitting single-page A4 warehouse pick-list PDF (jsPDF) and audit report[cite: 31].

**Live Demo:** [https://danish9u9.github.io/warehouse-out-sheet-generator/](https://danish9u9.github.io/warehouse-out-sheet-generator/)

## Key Features

- **Client-Side PDF Parsing (`PDF.js`):** Extracts order IDs, item SKUs, and quantities directly in the browser with zero server uploads[cite: 31].
- **Automatic Deduplication & Verification:** Flags duplicate shipping labels and cross-checks total item quantities to prevent dispatch errors[cite: 31].
- **Auto-Fitting Single-Page A4 Pick-List (`jsPDF`):** Dynamically scales table layout and typography so the entire warehouse pick-list fits cleanly onto a single A4 page for printing[cite: 31].
- **Audit Report Generation:** Produces a structured summary alongside the pick-list for end-of-day dispatch reconciliation[cite: 31].

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Libraries:** PDF.js, jsPDF[cite: 31]
- **Hosting:** GitHub Pages

## Usage

Open the [live web app](https://danish9u9.github.io/warehouse-out-sheet-generator/) (or open `index.html` locally in any modern browser)[cite: 31], upload one or more courier shipping label PDFs, and download the generated pick-list PDF.
