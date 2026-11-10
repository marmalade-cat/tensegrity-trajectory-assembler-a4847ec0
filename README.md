Tensegrity Trajectory Assembler — prototype

A minimal browser prototype that loads two CSVs (commanded and measured per-module angles with timestamps), aligns streams, fills missing values, and exports standardized replay CSV and JSON. Use it to test alignment and reconstruction strategies before applying to real supplementary datasets.

Usage: open index.html in a browser, load CSVs, adjust alignment tolerance, and export.

This is a small demo only; no network or file system access beyond user file inputs.