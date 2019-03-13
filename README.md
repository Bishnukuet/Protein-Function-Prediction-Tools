# Protein Function Annotation Tools

Thanks to recent developments in genomic sequencing technologies, the number of protein sequences in public databases is growing enormously.
In order to exploit more fully this huge quantity of data, protein sequences need to be annotated with functional properties such as Enzyme Commission (EC) numbers and Gene Ontology terms. 
The UniProt Knowledgebase (UniProtKB) is currently the largest and most comprehensive resource for protein sequence and annotation data. According to the March 2018 release of UniProtKB, some 556,000 sequences are manually curated but over 111 million sequences lack functional annotations. 
The ability to automatically annotate protein sequences in UniProtKB/TrEMBL, the non-reviewed UniProt sequence repository, would represent a major step towards bridging the gap between annotated and unannotated protein sequences.

Here, I ensemble a curated list of resources regarding the research in protein function annotation. 

# The repository for protein data:
- **Uniprot Knowledge Base**
  - [[SwissProt]](https://www.uniprot.org/uniprot/?query=reviewed:yes)
  - [[TrEMBL]](https://www.uniprot.org/uniprot/?query=reviewed:no)
- **Protein Data Bank PDB**
  - [[PDB]](https://www.rcsb.org/)
  - [[wwwPDB]](http://www.wwpdb.org/)
- **Protein Domain Data Base**
  - [[InterPro]](https://www.ebi.ac.uk/interpro/)
  - [[pfam]](https://pfam.xfam.org/)
  - [[CATH]](http://www.cathdb.info/)
  
# Function Annotation Tools: Gene Ontology (GO) terms Prediction:
- **Sequence Similarity Based**
   - **Blast2GO**
    - [[Blast2Go]] (https://www.blast2go.com/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/16081474)
  - **DeepGO**
    - [[DeepGO]](http://deepgo.bio2vec.net/deepgo/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5860606/)
  - **PANNZER**
    - [[PANNZER]](http://ekhidna2.biocenter.helsinki.fi/sanspanz/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/25653249)
  - **Argot2.5**
    - [[Argot2.5]](http://www.medcomp.medicina.unipd.it/Argot2-5/form.php)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/22536960)
  - **INGA**
    - [[INGA]](http://protein.bio.unipd.it/inga)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/26019177)
  - **CATH FunFHMMer**
    - [[FunFHMMer]](http://www.cathdb.info/search/by_funfhmmer)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/25964299)
  - **PANDA**
    - [[Panda]](http://protein.bio.unipd.it/panada/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/24265686)
  - **PFP-ESG**
    - [[PFP-ESG]](http://kiharalab.org/software.php)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/28451967)

# Function Annotation Tools: Enzyme Commission Number (EC) Prediction:
  - **GrAPFI 2019**
    - [[GrAPFI[](https://gitlab.inria.fr/bsarker/GrAPFI)
    - [[Paper]](https://hal.inria.fr/hal-01920595)
  - **ECPred 2018**
    - [[ECPred]](http://cansyl.metu.edu.tr/ECPred.html)
    - [[Paper]](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2368-y)
  - **DEEPre 2018**
    - [[DEEPre]](http://www.cbrc.kaust.edu.sa/DEEPre/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/29069344)
  - **COFACTOR 2017**
    - [[COFACTOR]](https://zhanglab.ccmb.med.umich.edu/COFACTOR/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5793808/)
  - **SVMProt 2016**
    - [[SVMProt]](http://bidd2.nus.edu.sg/cgi-bin/svmprot/svmprot.cgi)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/27525735)
  - **EC-BLast 2014**
    - [[EC-Blast]](http://www.ebi.ac.uk/thornton-srv/software/rbl/)
    - [[Paper]](https://www.nature.com/articles/nmeth.2803)

  - **EzyPred 2007**
    - [[EzyPred]](http://www.csbio.sjtu.edu.cn/bioinf/EzyPred/)
    - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/17931599)

# Interesting Papers
- [[Predicting human protein function with multi-task deep neural networks]](https://www.ncbi.nlm.nih.gov/pubmed/29889900)
- [[Using PPI network autocorrelation in hierarchical multi-label classification trees for gene function prediction]](https://www.ncbi.nlm.nih.gov/pubmed/24070402)
- [[Protein function prediction using text-based features extracted from the biomedical literature: the CAFA challenge]](https://www.ncbi.nlm.nih.gov/pubmed/23514326)
- [[MS-kNN: protein function prediction by integrating multiple data sources]](https://www.ncbi.nlm.nih.gov/pubmed/23514608)
- [[A regression-based K nearest neighbor algorithm for gene function prediction from heterogeneous data]](https://www.ncbi.nlm.nih.gov/pubmed/16723004)
- [[Predicting gene function using similarity learning]](https://www.ncbi.nlm.nih.gov/pubmed/24266903)
- [[Gene Ontology annotation of the rice blast fungus, Magnaporthe oryzae]](https://www.ncbi.nlm.nih.gov/pubmed/19278556)
- [[Prediction of protein function from protein sequence and structure]](https://www.ncbi.nlm.nih.gov/pubmed/15029827)
- [[Predicting protein function from sequence and structural data]](https://www.ncbi.nlm.nih.gov/pubmed/15963890)
- [[Automatic annotation of protein function]](https://www.ncbi.nlm.nih.gov/pubmed/15922590)
- [[Automatic annotation of protein function based on family identification]](https://www.ncbi.nlm.nih.gov/pubmed/14579359)
- [[Annotating proteins by mining protein interaction networks]](https://www.ncbi.nlm.nih.gov/pubmed/16873481)
- [[ProFAT: a web-based tool for the functional annotation of protein sequences]](https://www.ncbi.nlm.nih.gov/pubmed/17059594)
- [[An efficient method for protein function annotation based on multilayer protein networks]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5039885/)

# Interesting Papers of EC Annotation

- [[Accurate prediction of protein enzymatic class by N-to-1 Neural Networks]](https://www.ncbi.nlm.nih.gov/pubmed/23368876)
- [[Efficiency analysis of {KNN} and minimum distance-based classifiers in enzyme family prediction]](https://www.ncbi.nlm.nih.gov/pubmed/19853514)
- [[ECS: an automatic enzyme classifier based on functional domain composition]](https://www.ncbi.nlm.nih.gov/pubmed/17500036)
- [[Predicting enzyme subclass by functional domain composition and pseudo amino acid composition]](https://www.ncbi.nlm.nih.gov/pubmed/15952744)
- [[Accurate prediction of enzyme subfamily class using an adaptive fuzzy k-nearest neighbor method]](https://www.ncbi.nlm.nih.gov/pubmed/17140725)
- [[EFICAz2.5: application of a high-precision enzyme function predictor to 396 proteomes]](https://www.ncbi.nlm.nih.gov/pubmed/22923291)
 
  
  
  
