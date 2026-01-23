# Current Applications of CRISPR/Cas Technology in Gene Therapy – Towards More Precise and Computationally Guided Genome Editing

## Introduction

CRISPR/Cas technology has become one of the most significant biotechnological innovations of the past decade. Originally discovered as an adaptive immune defense mechanism in bacteria and archaea, it has been repurposed into a powerful and relatively easy-to-program genome editing tool that is now widely used in basic research and increasingly explored in therapeutic applications. From the perspective of gene therapy, CRISPR/Cas systems have enabled strategies that were previously unattainable with earlier genome editing technologies.

At the same time, the rapid adoption of CRISPR has highlighted important biological, technical, and ethical limitations. Key challenges include editing precision, off-target effects, and efficient and safe delivery of genome editing components. In recent years, it has become evident that effective and safe CRISPR-based gene therapy cannot rely solely on experimental optimization, but instead requires genome-level understanding and computationally guided design. This article reviews current applications of CRISPR/Cas technology in gene therapy and emphasizes the growing importance of precision, biological context, and bioinformatics in 2025.

## Biological Basis of the CRISPR/Cas System

The CRISPR/Cas system functions as an adaptive immune defense in bacteria and archaea, protecting cells from invading genetic elements such as viruses and plasmids. The system relies on CRISPR arrays that store short sequence fragments derived from previous infections and Cas proteins that act as nucleases (Amitai & Sorek, 2016). Upon reinfection, guide RNAs derived from CRISPR loci direct Cas proteins to complementary target sequences, leading to sequence-specific cleavage.

In genome editing applications, this natural mechanism is simplified by using synthetic single guide RNA (sgRNA) molecules that direct the Cas9 nuclease to a chosen genomic locus. Cas9 recognizes its target based on complementarity and the presence of a protospacer adjacent motif (PAM), inducing a double-strand break in DNA. This RNA-guided targeting mechanism is the key reason CRISPR/Cas9 has largely replaced earlier genome editing platforms such as zinc finger nucleases and TALENs (Sander & Joung, 2014).

## Genome Editing Beyond Double-Strand Breaks

Classical CRISPR/Cas9 genome editing relies on double-strand breaks that are repaired by cellular mechanisms such as non-homologous end joining (NHEJ) or homology-directed repair (HDR). These pathways enable gene disruption, deletion, or precise correction, and have been extensively explored in gene therapy research. However, double-strand breaks carry inherent risks, including imprecise repair outcomes and genomic instability.

As a result, recent development has shifted toward more refined editing strategies. Modified Cas9 variants, including nickase Cas9 and catalytically inactive dCas9, enable single-strand cutting, transcriptional regulation, and epigenetic modulation without permanent DNA cleavage. In addition, newer approaches such as base editing and prime editing allow precise nucleotide-level changes without generating double-strand breaks, making them particularly attractive for therapeutic applications (Anzalone et al., 2019).

## Therapeutic Applications of CRISPR-Based Gene Editing

CRISPR/Cas technology has been explored in a wide range of disease contexts, although biological feasibility varies significantly between disease classes. Viral infections were among the first therapeutic targets, particularly retroviruses. HIV is a retrovirus whose life cycle includes reverse transcription and stable integration into the host genome. This proviral state makes infection persistent and difficult to eradicate, but also provides a theoretical opportunity to directly target the integrated viral genome using CRISPR-based approaches (Lu Xiao-Jie et al., 2015). While experimental studies have demonstrated suppression of viral replication, high mutation rates and viral diversity remain major obstacles.

Monogenic inherited disorders currently represent the most realistic clinical targets for CRISPR-based gene therapy. Diseases caused by mutations in a single gene, such as β-thalassemia or Duchenne muscular dystrophy, allow relatively straightforward targeting of a defined genomic locus. In these cases, CRISPR has been successfully applied both in ex vivo edited stem cells and in vivo strategies, offering promising therapeutic outcomes (Xie et al., 2014).

In contrast, cancer and other polygenic diseases pose far greater challenges. Cancer genomes are highly heterogeneous and often contain numerous driver and passenger mutations, complicating single-target editing approaches. Although CRISPR systems can theoretically be multiplexed to target several loci simultaneously, effective and safe therapeutic implementation requires deep genomic characterization and careful target selection.

## Off-Target Effects and the Need for Precision

One of the central limitations of CRISPR/Cas technology is the potential for off-target activity. Cas9 does not require perfect sequence complementarity, which can result in unintended cleavage at genomic sites containing partial homology and a compatible PAM motif. Such off-target events may have significant biological consequences and represent a major concern in therapeutic settings (Sternberg & Doudna, 2015).

Multiple strategies have been developed to reduce off-target risk, including guide RNA optimization, engineered Cas9 variants with enhanced specificity, and improved delivery methods. Nevertheless, it has become clear that experimental optimization alone is insufficient, and that genome-wide computational analysis is essential for predicting and minimizing off-target effects prior to laboratory validation.

## Bioinformatics in CRISPR Design and Risk Assessment

Bioinformatics has become a central component of modern CRISPR-based gene therapy research. Genome-scale sequence data enable systematic screening of candidate target sites and identification of potential off-target regions using in silico methods. Computational analyses support guide RNA design, target prioritization, and overall therapeutic strategy selection before experimental implementation.

This shift reflects a broader transformation in gene therapy, where biological insight, genomics, and data analysis are increasingly integrated. CRISPR is no longer solely a wet-lab technique, but part of a comprehensive workflow that combines computational prediction with experimental validation.

## Epigenetic Editing and Reversible Modulation

Epigenetic editing using dCas9-based systems provides an alternative to permanent genome modification. By coupling dCas9 to transcriptional activators, repressors, or chromatin-modifying enzymes, gene expression can be modulated without altering DNA sequence (Portela & Esteller, 2010). Such approaches are particularly attractive therapeutically, as they are potentially reversible and may reduce long-term risks associated with permanent genomic changes.

## Ethical and Regulatory Considerations

The application of CRISPR/Cas technology in gene therapy raises significant ethical and regulatory concerns, particularly with respect to germline editing. While somatic gene therapy approaches are advancing toward clinical use, germline modification remains heavily restricted or prohibited in many countries. The pace of technological development continues to challenge existing regulatory frameworks.

## Conclusions and Outlook

CRISPR/Cas technology has fundamentally transformed gene therapy research and opened new possibilities for treating genetic diseases. By 2025, the primary focus has shifted from editing efficiency toward precision, biological context, and computationally informed design. The future of gene therapy increasingly lies at the intersection of molecular biology and bioinformatics, where genome-scale data analysis supports the development of safer and more targeted therapeutic strategies.

## References

Amitai, G. & Sorek, R. (2016). CRISPR–Cas adaptation: insights into the mechanism of action. *Nature Reviews Microbiology*, 14, 67–76.  
Anzalone, A. V. et al. (2019). Search-and-replace genome editing without double-strand breaks or donor DNA. *Nature*, 576, 149–157.  
Lu Xiao-Jie, X. et al. (2015). CRISPR-Cas9: a new and promising player in gene therapy. *Journal of Medical Genetics*, 52, 289–296.  
Portela, A. & Esteller, M. (2010). Epigenetic modifications and human disease. *Nature Biotechnology*, 28, 1057–1068.  
Sander, J. D. & Joung, J. K. (2014). CRISPR-Cas systems for editing, regulating and targeting genomes. *Nature Biotechnology*, 32, 347–355.  
Sternberg, S. H. & Doudna, J. A. (2015). Expanding the biologist’s toolkit with CRISPR–Cas9. *Science*, 346, 1258096.  
