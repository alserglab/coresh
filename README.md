This repository demonstrates the core algorithm behind CORESH search engine for querying public gene expression datasets based on a user-provided gene signature (https://alserglab.wustl.edu/coresh/). 

CORESH ranks the datasets based on the level of coregulation of user-provided genes using a score inspired by Principal Component Analysis, which can be applied to any gene expression matrix. Currently, CORESH operates on a compendium of more than 40,000 mouse and 40,000 human gene expression datasets from the GEO database, including datasets from both microarray and RNA-seq profiling.

Please refer to the vignette at https://rpubs.com/asergushichev/coresh-local.
