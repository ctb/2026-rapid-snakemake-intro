# 2026-rapid-snakemake-intro

A (very) rapid introduction to Snakemake

See [the hackmd slides](https://hackmd.io/sMw-VJANQK-qPlepiMs-vw?view#/) for information.

Examples are preloaded in the `ex*` subdirectories.

## Installing snakemake

On UC Davis HPCs, you may need to run: `module load conda`.

Then:
```
conda create -n rapid-snakemake -c conda-forge -c bioconda -y snakemake-minimal
```

and activate:
```
conda activate rapid-snakemake
```

## Grabbing this repository:

```
git clone https://github.com/ctb/2026-rapid-snakemake-intro.git
```

## Running the examples

For example,

```
cd ex1/
snakemake -j 1
```
