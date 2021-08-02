# MuCIGREF: Multiple Computer-interpretable Guideline Representation and Execution Framework 


# MuCIGREF Ontology

MuCIGREF (Multiple Computer-Interpretable Guideline Representation and Execution Framework) Ontology is a generic ontology to represent knowledge elements of Clinical Practice Guidelines and their interrelations, and to create the multimorbidity related associations between them. 

MuCIGREF ontology, namely, Multiple Computer-interpretable Guideline (CIG) Representation Language (MuCRL) has two versions:
  - Ontology Web Language (OWL) format: .owl
  - Eclipse Modeling Framework (EMF) format: mucigref_ontology.emf

Both are available here. 

# MuCIGREF Knowledge Execution Engine
MuCIGREF's execution engine, namely, MuCEE able to concurrently implement multiple CIGs in real-time and infer required information from knowledge base. MuCEE has three modules as:
  - CIG acquisition
  - Multiple CIG merging
  - CIG verification

MuCEE is written using Epsilon Object Language (EOL). A part of CIG acquisition codes is shared as mucigref_model_acquisition.eol for illustration.

MuCIGREF's verification mechanism can be used to discover inconsistencies, errors or missing information in CIGs and in personal care plans. A part of verificstion codes are also shared under the file mucigref_sample_validation.evl for illustration, which are written using Epsilon Validation Language (EVL). 

If you would like to reuse any part of the codes, please cite it as follows:

**Ozyigit, EB (2020). MuCIGREF: Multiple Computer-interpretable Guideline Representation and Execution Framework For Managing Multimorbidity Care. PhD Thesis, University of Warwick.**

For further information, please get in touch via **edaozyigit.com/contact**
