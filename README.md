# Co-ordinate-Extractor-
Extracts the genomic co-ordinates for computational operations using multi CPU cores for large-scale data .

Engine: Polars (Rust-based).

Method: Vectorized Regex extraction using .str.extract().

Performance: Automatically scales to use all logical CPU cores for O(n) time complexity relative to the number of rows.
