These three script files take as input standard Rosetta fragment files (both 9-mers and 3-mers) and alter them to abide by the SS-Rosetta method. New files are Rosetta-compatible ones.

File H1_9_mers amends a 9-mer file by reducing the number of fragments at specified positions to 1 instead of 25 (when there is a helix that lasts in nine successive positions).

File H5_3_mers amends a 3-mer file by reducing the number of fragments at specified positions to 5 instead of 200 (when there is a helix that lasts in three successive positions).

File E25_3_mers amends a 3-mer file by reducing the number of fragments at specified positions to 25 instead of 200 (when there is a beta strand that lasts in three successive positions).

These demo files target positions 1, 2, 3… 30, 60, 61, 63… 80 (as an example).

These three files amend the original file, therefor, DO make a copy before running it.

The name of the fragment files is the default one: 
- aat000_09_05.200_v1_3
- aat000_03_05.200_v1_3







