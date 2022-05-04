# Hashtag Demultiplex Pipeline

## Files

- **main.df:** Contains Nextflow script, which calls the processes
- **nextflow.config:** Default parameters for the pipeline
- **HTODemux.R:** HTODemux algorithm 
- **HTODemux-visualisation.R:** HTODemux graphs
- **multi-seq.R:** HTODemux algorithm 

### HTODemux 
#### Input

- UMI Matrix.rds File
- Hashtag counts matrix  .rds File. (*)
- Parameters for HTODemux

### MULTI-seq
#### Input
- S4 Seurat object.rds File
- Path to save graphs
