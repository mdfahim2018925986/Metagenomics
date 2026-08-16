Raw paired-end FASTQ
        │
        ▼
1. Quality Control
   ├── FastQC
   ├── fastp
   └── MultiQC
        │
        ▼
2. Host-read Removal
        │
        ▼
3. Taxonomic Profiling
   ├── Kraken2 → read classification
   ├── Bracken → abundance estimation
   └── MetaPhlAn → marker-gene taxonomic profiling
        │
        ▼
4. Functional Profiling
   └── HUMAnN
       ├── ChocoPhlAn + Bowtie2
       ├── UniRef90 + DIAMOND
       └── Utility Mapping
        │
        ▼
5. Downstream Analysis
   ├── Community composition
   ├── Alpha / beta diversity
   ├── Differential abundance
   ├── Functional pathways
   └── Visualization
        │
        ▼
6. Optional Advanced Analysis
   ├── Metagenome assembly
   ├── Gene prediction / annotation
   ├── AMR genes
   ├── Virulence factors
   ├── Mobile genetic elements
   ├── Plasmids
   └── Metagenome-assembled genomes (MAGs)
