
> برای خواندن این صفحه به زبان فارسی، [README.fa.md](./README.fa.md) را ببینید.

## 🧭 Ontology of Iranian Tribes

During a series of scholarly meetings held at the **National Library and Archives of Iran**, a comprehensive list of Iranian tribes was compiled. Participants included **Dr. Torkashvand**, **Narges Ghadimi**, and **Rezagholi**, in collaboration with **Dr. Gholamreza Amirkhani**, **Ata Ahmadi**, and **Fariborz Khosravi**.

Following the initial compilation, the accuracy of the data was reviewed in collaboration with provincial authorities. Each province's list was submitted to the respective governor’s office for validation and correction. Once finalized, the idea of transforming this data into a formal ontology was proposed, approved by the **Research Council**, and implemented using **Protégé**, the open-source ontology editor developed at Stanford University. The continued collaboration and expertise of Dr. Torkashvand were instrumental throughout the process.

The **Ontology of Iranian Tribes** represents a large-scale and relatively comprehensive knowledge base of tribal structures in Iran. It includes thousands of classes for tribes, clans, lineages, households, associated regions, and related concepts—along with hundreds of individual instances.

### 📊 Ontology Statistics

- **Total RDF Triples**: 18,177  
- **Classes**: 4,648  
- **Object Properties**: 7  
- **Datatype Properties**: 6  
- **Individuals**: 601  

The tribal hierarchy is modeled in the following structure:  
**Tribe → Clan → Lineage → Family Branch → Offspring → Household**

---

### 🏷️ Example Classes

Examples of classes included in the ontology:

- `Tribe_Shakkak`  
- `Tribe_Arab_Haji_Agha_Soltani`  
- `Goklan`  
- `Clan_Darkhvar`, `Clan_ValadBeigi`, `Clan_HaghNazarkhani`, `Clan_Saeedi`, `Clan_Amir`  
- `Lineage_BahmanBiglu`, `Lineage_Bamasheh`, `Lineage_Malaler`  
- `Family_Zalaei`  
- `Offspring_MohammadKazem`, `Offspring_Faraj`, `Offspring_MollaKhosridi`

---

### 🔗 Object Properties

Seven object properties define key relationships:

- `is_a` – hierarchy (e.g., a clan is part of a tribe)  
- `has_dialect` / `tribe_dialect` – linguistic relationships  
- `reside_in` / `habitat` – geographical distribution  
- `produce` / `produced_in` – economic or production-related links  

---

### 🔢 Datatype Properties

Six datatype properties capture descriptive or bibliographic attributes:

- `Population`  
- `Number`  
- `Book`  
- `Article`  
- `Document`  
- `Thesis`  

---

### 👤 Individuals

About 600 individuals are represented, including:

- `Information_Tribe_Bakhtiari`  
- `Information_Chente`  
- `Definition`  
- System-related identifiers  

---

### 🧩 Conclusion

The **Ontology of Iranian Tribes** provides a structured and richly detailed knowledge base capturing tribal, linguistic, geographical, demographic, and bibliographic dimensions of Iranian society. It offers an important resource for researchers in **anthropology**, **ethnography**, **linguistics**, **Middle Eastern studies**, and **digital humanities**.

**Author**: Fariborz Khosravi  
**Contact**: [khosravi.fariborz@gmail.com](mailto:khosravi.fariborz@gmail.com)






## 📜 License

This ontology is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).  
Author: Fariborz Khosravi – [khosravi.fariborz@gmail.com](mailto:khosravi.fariborz@gmail.com)  
See [LICENSE](./LICENSE) for full details.



# iranian-tribes-ontology
an open ontology of Iranian tribes, clans, and lineages for research, preservation, and reuse.
