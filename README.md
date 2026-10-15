# Unix for Biology

A free, self-paced, introductory course the Unix command line for high-throughput biological data analysis and bioinformatics. Contained entirely in a single standalone HTML page with an embedded interactive biological shell emulator, real-world genomics examples (FASTA, FASTQ, BED, GFF, VCF), self-check quizzes, and curated references.

## Contents

| # | Module | Core Biological Focus |
|---|--------|------------------------|
| 1 | The Biologist's Shell & File Navigation | Inspecting large FASTQ/FASTA files with `head`, `tail`, `less -S`, and `zcat` |
| 2 | Pattern Searching in Sequences with Grep | Counting reads, pulling headers, filtering out comments (`grep -v '^#'`) |
| 3 | Working with Tabular Genomic Data: Cut, Sort & Uniq | Manipulating BED/SAM coordinates, natural sorting (`sort -V`), read frequencies |
| 4 | Stream Editing and Sequence Cleaning with Sed | Converting UCSC/Ensembl chromosome names (`chr1` vs `1`), DNA/RNA conversions |
| 5 | Genomic Table Crunching with Awk | Filtering features by interval size (`$3 - $2`), calculating coverage and GC content |
| 6 | Pipes, Redirection & Assembling Bio-Pipelines | Directing aligner output without intermediate disk writes, logging stderr |
| 7 | Bash Scripting & Batch Automation for High-Throughput Data | Iterating over multi-sample sequencing libraries (`for fq in *_R1.fastq.gz`) |
| 8 | HPC Clusters, Bio-Environments & Production Reproducibility | SLURM job submission, Bioconda environment management, Snakemake/Nextflow |

Each module provides learning objectives, time estimates, executable commands ready to test directly in the browser sandbox, equivalent Python and R scripts, filterable reference materials, and concept validation quizzes.

## Usage

1. Download `index.html`.
2. Open it in any modern web browser.
3. No build step, Python server, node package manager, or tool installation is required.

To host the course on the web, place `index.html` in the root of any static web host or GitHub Pages repository.

### Browser Sandbox & Privacy
The built-in interactive sandbox simulates biological pipeline processing using client-side JavaScript. All data entered and course progress tracking remain entirely within your browser's local storage (`localStorage`). No files or analytical operations leave your device.

## Contributing

Suggestions for new biological command patterns, edge-case scenarios with genomics file formats, additional practice exercises, and updated resources are welcomed via issues or pull requests.

## Acknowledgments

- Foundational Curriculum & Bio-Pipelines: [Software Carpentry: The Unix Shell](https://swcarpentry.github.io/shell-novice/), [Stephen Turner's Bioinformatics One-Liners](https://github.com/stephenturner/oneliners), [Data Science at the Command Line](https://datascienceatthecommandline.com/2e/) (Jeroen Janssens)
- Textbooks & References: *Bioinformatics Data Skills* by Vince Buffalo (O'Reilly Media), *The AWK Programming Language* by Alfred V. Aho, Brian W. Kernighan, and Peter J. Weinberger, *Advanced Bash-Scripting Guide* by Mendel Cooper
- Tool Documentation & Standards: [GNU Coreutils & Grep Manuals](https://www.gnu.org/software/coreutils/), [UCSC Genome Browser File Format Guidelines](https://genome.ucsc.edu/FAQ/FAQformat.html), [Bioawk](https://github.com/lh3/bioawk) (Heng Li), [Bioconda](https://bioconda.github.io/), [SLURM Workload Manager](https://slurm.schedmd.com/)
- Educational Communities & Channels: [Biostars](https://www.biostars.org/), [Rosalind Bioinformatics](https://rosalind.info/), [The Carpentries](https://carpentries.org/), [OMGenomics](https://www.youtube.com/@OMGenomics), [Bioinformatics Coach](https://www.youtube.com/@BioinformaticsCoach)
- Coding assistance: Gemini (Google)

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
