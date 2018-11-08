<!DOCTYPE html>
<html>
<body>

<h1 style="font-family:calibri;"><center>Provisional Cell Ontology</center></h1>

<p style="font-family:calibri;"><b style="font-size:150%;">Motivation:</b><br/>Research community is identifying novel cell types at a rapid pace using single cell RNA sequencing (scRNAseq). While there has been a focus on data generation, less attention has been paid to how the knowledge derived these data will be used by the research community.</p>
<p style="font-family:calibri;">Since the datasets produced by different research groups, labs, and organizations are likely in a proprietary format, this hinders the capability of aligning and sharing these datasets.</p>
<p style="font-family:calibri;">Translating the scientific studies and discoveries into biological knowledge that is Findable, Accessible, Interoperable and Reproducible (FAIR) has a crucial impact on the broader research community.</p>

<p style="font-family:calibri;"><b style="font-size:150%;">Approach:</b><br/>Provisional Cell Ontology (pCL) has been developed, where the data being gathered from experimental work is represented in a standard semantic format that can be captured, retrieved, exchanged, disseminated and managed using standard approaches and tools.</p> 
<p style="font-family:calibri;">Cell type definitions in the pCL are being constructed by combining selected elements of experimental evidence that support the unique cell type identity, including tissue specimen source and anatomic location represented by terms from Uberon, necessary and sufficient marker genes derived from machine learning analysis, and parent cell classes in the reference Cell Ontology (CL).  Using this strategy, we have defined 91 pCL classes from the adult human cerebral cortex middle temporal gyrus and 47 pCL classes from human fetal brain and will be expanding pCL to include classes from the adult human lung and pancreas and the developing heart.</p>
<p style="font-family:calibri;">The proposed framework is centered around CL. In addition to pCL ontology, it includes standard ontologies like UBERON, FMA, Hugo, BTO, GO, etc.  Depending on the search use case, these ontologies are used only as/if needed in a subset. The framework links the user-defined pCL ontology to other standard ontologies and supports semantic interoperability of information. In such a case, we can retrieve and trace information from any ontology, starting from the pCL ontology.</p>

<p style="font-family:calibri;"><b style="font-size:150%;">Status:</b><br/>The initial release is version 1.0 </p> 

</body>
</html>
