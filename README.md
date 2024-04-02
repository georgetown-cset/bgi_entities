# BGI Entities

This repository contains a list of BGI-related entities CSET identified in preparing our report [China, Biotechnology and BGI: How China's Hybrid Economy Skews Competition](https://cset.georgetown.edu/article/UPDATE-ME/).

This [table](https://github.com/georgetown-cset/bgi_entities/blob/0eaea73ff6207f3fc5058f93b9fc4abbe81bf127/BGI_Entity_List.csv) summarizes all the entities (corporations, institutions, branches, and financial organizations, etc) that we were able to identify having a relation to BGI and MGI.  This list is based our review and analysis of
- BGI Genomics’ annual and semi-annual reports (年半年度报告 and 年年度报告) from 2019 through 2022.
- The 2022 Prospectus of MGI Tech (深圳华大智造科技股份有限公司), a major affiliate of BGI Genomics which went public on the Shanghai stock exchange on September 9th 2022 (SHA: 688114).   
- Corporate press releases, searching the Refinitiv database of corporate entities, and Baidu searches (the primary Chinese search engine). 
All together, we identified 445 corporations, research institutions, branches, and banks related to the BGI corporate family. 

## Column Names

### Entity Name (original)
This column contains the name of the entity as shown in the original source document(s).  This name appears in its original form and language.  These often appear in Chinese, although many of the entities are identified with English names in the original source documents.

### Entity Name (Etcetera translation)
This column contains the name of the entity translated from Chinese into English by a professional translation service.

### Entity Name (Google translation) 
This column contains the name of the entity translated from Chinese into English using Google’s translation tool.

### City/County
This column contains the city or county where the entity is located.

### Region
This column contains the region where the entity is located.

### Country
This column contains the country where the entity is located.

### Affiliation
This column identifies whether the source documents indicate the entity is affiliated with BGI, MGI, or it has some other affiliation.  Possible values are:
- “BGI & MGI” means the entity is affiliated with both BGI and MGI
- “BGI” means the entity is affiliated with BGI
- “MGI” means the entity is affiliated with BGI
- “Other” means the entity has a more complex or indeterminate relationship to MGI or BGI
- “BGI holding company” means this entity is the holding company that is the parent of BGI
- “BGI itself” means this entity is the BGI company itself
- “MGI holding company” means this entity is the holding company that is the parent of MGI
- “MGI itself” means this entity is the MGI company itself

### Nature of Affiliation
We grouped these various entities into the following categories according to the nature of their affiliation with BGI and MGI:
- **Primary companies**:  One of the four main, “controlling” companies in this network:
  * Shenzhen BGI Technology Co., Ltd.  (深圳华大基因科技有限公司), the parent holding company of BGI Genomics, referred to in the report as “BGI Group”.
  * BGI Genomics Co., Ltd.  (深圳华大基因股份有限公司), referred to in this report as “BGI Genomics”.
  * Shenzhen Huada Intelligent Manufacturing Holdings Co., Ltd. (深圳华大智造控股有限公司), the parent holding company of MGI Tech.
  * MGI Tech Co., Ltd. (深圳华大智造科技股份有限公司), referred to in the report as MGI Tech (note that MGI Tech changed its name from 深圳华大智造科技有限公司).
- **Subsidiary** (of BGI or MGI): An entity with more than 50% equity owned (directly or indirectly) by one of BGI Genomics or MGI Tech. These include entities such as:
  * Complete Genomics
  * Wuhan Huada Zhizao Bioengineering Co., Ltd. (“Wuhan Biology”)
  * Kunshan MGI Yunying Medical Technology Co., Ltd. (“Kunshan Yunying”)
- **Affiliate** (of BGI and/or MGI): An entity owned in part by BGI Genomics and/or MGI Tech. These include entities such as:
  * Wuhan Guao Gene Technology Co., Ltd. (“Guao Gene”)
  * Suzhou Synbio Biotechnology Co., Ltd. (“Suzhou Synbio”)
  * Kunshan MGI Yunying Medical Technology Co., Ltd. (“Kunshan Yunying”)
- **Associate** (of BGI and/or MGI): An entity controlled by one of BGI’s or MGI’s senior executives.  These include entitites such as:
  * Shenzhen BGI Technology Innovation Center Co., Ltd.
  * BGI Luoyang Agricultural Innovation Center
  * CITIC Industrial Investment Fund Management Co., Ltd.
- **Branch** (of MGI): One of the eight regional branches of MGI.
- **Other**: An entity with some other relationship to either MGI or BGI.  This includes the following kinds of organizations:
  * Exchanges in which BGI or MGI related companies are traded including:
    + Shanghai Greenwoods Jingqi Investment Center (Limited Partnership)
  * Banks and investment firms with major holdings in BGI or MGI such as:
    + Bank of China Co., Ltd.&mdash;China Merchants State Certificate Biomedical Index Hualing Securities Investment Fund
  * Companies identified in prospectuses but lacking a clear explanation of relationships. Below are some examples:
    + Beijing Rongzhi Lian Technology Co., Ltd.
    + Shaanxi Hua Darre Technology Co., Ltd.
    + Shenzhen Huada Clinical Examination Center
