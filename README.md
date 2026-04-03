# Xelquanta-lab
A portable single-file DuckDB-WASM data lab with tables, charts, transforms, and AI copilot.

## DuckDB Web Interface

A single-file web application that provides a browser-based interface for DuckDB, enabling SQL queries on uploaded data files without server-side processing.

Please feel free to test the demo here:

https://shonejj.github.io/Xelquanta-lab

## Features

- **File Upload Support**: Load CSV, Parquet, JSON, files directly in the browser
- **SQL Query Interface**: Execute SQL queries against loaded data 
- **Table Management**: View tables
- **AI Integration**: Optional Groq API integration for natural language to SQL conversion
- **Export Capabilities**: Export query results to CSV
- **Demo Data**: Built-in sample dataset for testing

## Usage

1. Open `index.html` in a modern web browser
2. Upload data files using the upload button
3. Write and execute SQL queries in the query editor or use option in the data area to transform the imported data easily
4. View results in the data grid below

## Requirements

- Modern web browser with WebAssembly support
- Internet connection for loading DuckDB WASM and extensions
- Optional: Groq API key for AI features

## Technical Details

- Built with DuckDB WASM for client-side SQL processing
- Uses Monaco Editor for SQL editing
- No server required - runs entirely in the browser

## Privacy

All data processing happens locally in your browser. Files are not uploaded to any server.
