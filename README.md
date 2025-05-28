# Chip_seq
The following operations were taken on the data:
- Generated simulated paired-end ChIP-Seq data with stronger enrichment signals.
- Executed the **MACS3** peak caller on this simulated data from within an R script, attempting default model building.
- Loaded the resulting `.narrowPeak` file into R using `rtracklayer` (if peaks were found).
- Briefly inspected the `GRanges` object containing the peaks and visualized some basic properties (histograms).
- Visualized the raw read coverage for treatment and control alongside the called peaks in a specific genomic region using `Gviz`.
