# VariantCalling

Description of each project:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Project 1. CRISPR

You work at the frontier of science. The biotech company you’re with is aiming to edit thousands of sites in mammalian genomes (we'll set aside the ethical considerations for now). The wet lab team is excited—they’ve run their CRISPR experiments on a mouse cell culture and sequenced the results!

Now, they need to determine if the experiment succeeded. They’ve asked you to quickly develop a pipeline to analyze the sequencing data and:

Identify the induced mutations from the CRISPR experiment.
Detect potential off-target effects.
The lab originally intended to edit the following sites, all located on chromosome 2:

36937210            36996899            85400441            85776687              85918029

86198668            86236802            86658391            87049235

HINT: Run a variant-calling pipeline on the genome and identify all changes. Compare the results against the provided list.

To achieve full credit (100%), submit the following deliverables:

A DataFrame showing the data corresponding to the intended mutations.
A DataFrame of off-target mutations.
A summary DataFrame displaying the number of mutations and genotypes per chromosome, considering only off-target changes.
A simple plot illustrating any aspect of the project (for example, data from points 1, 2, or 3 above).
