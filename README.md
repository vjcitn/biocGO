# biocGO -- a pkgdown site describing relations between Gene Ontology and Bioconductor

This site will collect basic information on the use of GO in Bioconductor.

Use the "Get started" tab above to see the main vignette.

Briefly, Bioconductor provides Gene Ontology resources in several ways.

- First, [GO.db](https://bioconductor.org/packages/GO.db) is an annotation package
providing convenient maps between GO tags and terms in the molecular function,
biological process, and cellular component ontologies.  The fundamental
representation is in SQLite, and [AnnotationDbi](https://bioconductor.org/packages/AnnotationDbi)
defines the API for querying the ontology.

- Second, [org.Hs.eg.db](https://bioconductor.org/packages/org.Hs.eg.db) provides
mappings from human genes to gene ontology tags, as defined at NCBI.

- Third, the [GO (bioc 3.13)](https://bioconductor.org/packages/3.13/BiocViews.html#___GO) biocViews
entry lists packages that declare Gene Ontology as a key concept addressed by the package.

- Additionally, the OBO representation of terms and relationships between them
is ingested using the [ontologyIndex](https://cran.r-project.org/package=ontologyIndex)
API and serialized for users in the [ontoProc](https://bioconductor.org/packages/ontoProc)
Bioconductor package.


