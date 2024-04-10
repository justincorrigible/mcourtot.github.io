---
title: Research
nav:
  order: 1
  tooltip: Research themes
---

# {% include icon.html icon="fa-solid fa-laptop-medical" %}Research

Fundamentally, all of my research focuses on enabling more sophisticated biomedical data integration and knowledge representation, specifically applied to the health domain.

## Fundational themes
1. Designing knowledge representation for biomedical data to address key clinical use cases.  I have over 15 years of experience in the development of data standards. I led and contributed to the development of several ontological resources, including for systems biology, vaccine adverse events, biomedical experiments, antimicrobial resistance, and information artifacts. Over 200,000 datasets worldwide implement the Data Use Ontology I designed. The ICGC-ARGO data model I develop underpins several funded projects, including the European-Canadian Cancer Network and the Marathon of Hope Cancer Centres Network.

2. Technical expertise supporting consortia of ontology developers I actively contribute to the OBO Foundry, a collaborative consortium of more than 150 biomedical ontologies adhering to shared best practices. I co-developed and implemented multiple tools that are used across the consortium, such as the Minimal Information to Represent an External Ontology Term (MIREOT) which for the first time allowed partial reuse of ontologies, increasing semantic consistency and interoperability.

3. At-scale automated annotation and classification of biomedical data. My PhD research demonstrated that an ontology-based system relying on existing clinical guidelines could successfully and quickly classify reports of adverse events compared to manual classification. I led the Gene Ontology (GO) editorial office and annotation teams. GO is the most widely used ontology in biomedical research; I used it to identify new hypotheses for new biomedical research for example with metagenomics and fungal bioremediation of radioactive sites. 

4. Big data genomics platforms design and deployment  At OICR, my team of 25 develops the Overture software suite, which powers our big data platforms. It has managed ~3 million genomes (2.5 petabytes of data) accessed by over 300,000 researchers worldwide. Overture supports many active large-scale cancer genomics projects including ICGC and ICGC-ARGO (collecting molecular and clinical data for over 100k patients worldwide), VirusSeq (Canadian Covid portal with over 500k SARS-CoV-2 sequences), and the upcoming pan-Canadian Genome Library. Beyond the global north, it drives the African Pathogen Data Sharing and Archive Platform to upload and share pathogen sequences and associated metadata across continental Africa.

## Expanding themes
1. Deliver TRUE data While achieving Findable, Accessible, Interoperable and Reusable (FAIR) data has been a fantastic driver towards making data more accessible and shareable, it now needs to go further, towards what I call TRUE (Tracked, Reasonable, Understandable and Ethical) data. Data needs to be Tracked to establish attribution; this is fundamental not only to assert provenance of our knowledge but also for equity and encourage open data sharing. Data must be Reasonable: unless we can computationally process the large amount of data generated, using standard tools and pipelines, it will remain vastly underused. Large-language models (LLMs) provide fantastic opportunities to extract information, but unless data is Understandable, we risk ‘hallucinations’ and falling short of providing explainable AI, which can amplify detrimental bias. Finally, data use needs to be Ethical: it should be secure and follow regulatory requirements.

2. Computational cohorts Not only is accessing human individual-level data records time and effort-consuming, but it can result in disappointment when it does not even contain the information of interest. For example, researchers can search for cancer datasets, but what if they need recurring cancer cases specifically? I initiated work to enable computational, aggregated representation of cohort data, based on the Phenopacket standard I developed. This would enable producing high-level cohort summary statistics, but also running small algorithms on the aggregated data such as “has_cancer and occurence_date >1”, giving confidence to the researcher that they will obtain data relevant to their work. High-level data rendering will increase discovery and provide a first step towards deeper integration, supporting a tiered approach and iterative, fast improvements to the data model, allowing for agile adjustments as needed.

3. Streamline data access Much work is done on improving data quality, but unless it can be efficiently accessed, the best data in the world will remain unused. I have built several standards to streamline data access (GA4GH DUO, Passport, and Machine-Readable Consent Guidance). Those would be nicely complemented by ways to standardize patient enrollment and data access requests. 

4. Leverage emerging technologies
The recent explosion of LLMs for health research has generated many opportunities and challenges which are both relevant to this research program and would advance my own research in knowledge representation and curation. In collaboration with clinicians, I have started small projects based on LLM-based data extraction to retrieve information about clinical trials from reference databases and generate summaries which are then loaded into a data portal for ease of access. I want to explore image generation to provide data visualization - for example infographics on drug efficiency for clinical trials. I am currently expanding this project with academic collaborators to use the same methods to extract clinical trials eligibility criteria from natural language protocols. 

