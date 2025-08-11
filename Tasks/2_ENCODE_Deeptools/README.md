# ENCODE Deeptools Plots

## Task Description
We want you to generate a [Deeptools Heatmap Plot](https://deeptools.readthedocs.io/en/develop/content/example_gallery.html#dnase-accessibility-at-enhancers-in-murine-es-cells) from some ENCODE ChIP-Seq data.

Something similar to this:

![Example Heatmap](https://training.galaxyproject.org/training-material/topics/epigenetics/images/cut_and_run/peak_coverage_heatmap.png)

The ENCODE samples we'd like to use are all Histone ChIP datasets from Human HEK293 cells.  The accession codes for the samples to use are:

* Input Control - ENCSR000EVA
* H3K4me3 - ENCSR000DTU
* H3K27Ac - ENCSR000FCH

Where an ENCODE study has more than one sequence dataset in it, you can just pick one of the ones available to use.

The plot should profile the read abundance around gene transcript start sites +/- 10kb.  We want a single plot showing Input, H3K4me3 and H3K27Ac, preferably in that order.

## Relevant details
You can use any human genome assembly version or annotation set. It's up to you (or the LLM).

You can either start from the raw sequence data and work all of the way through the process, or get the aligned data from ENCODE and use that to start.

## Data provided
No data is provided for this task.  You should be able to download the data you need from the [ENCODE web site](https://www.encodeproject.org) based on the accession codes above.