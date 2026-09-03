# Scholarly Summary Report  
## Wellcome MS.3203 – Five Treatises upon Magic  
**Symbol Repository & Research Protocol Package**  
Date: 2026-09-03  
Protocol: research-protocol-infrastructure  

---

### 1. Manuscript Identification
- **Shelfmark**: Wellcome Collection MS.3203 (Accession 63884)
- **Title**: Five Treatises upon Magic
- **Production**: English, mid-19th century. Principal transcription by Henry Dawson Lea (1843); later ownership and annotation by Frederick Hockley (note 1869).
- **Content type**: Practical grimoire compiling Solomonic, Goetic and Theurgic material, with extensive hand-drawn seals and hierarchical spirit lists.
- **Physical / Digital status**: Digitized by Wellcome Collection; Public Domain Mark. Persistent URL: https://wellcomecollection.org/works/ec44wsyf

### 2. Scope of the Present Deep-Dive
Triple visual and structural survey focused on pages 90–150 (with special attention to 96–120 and extension to 150).  

Key visual findings:
- Page 96 contains four major composite plates (Anophezeton triangle, multi-ring “Maria” circle, vessel/alembic, additional circular seal).
- Pages 97–100 present the classic 72 Goetic spirit seals in tabular form.
- Pages 103 onward develop the Theurgia Goetia under the four emperors (Carnesiel, Caspiel, Amenadiel, Demoriel) and their subordinate dukes, generating hundreds of unique geometric sigils.
- Pages 121–150 continue the same Theurgic series without introducing new major full-page plates of the p.96 type.

No figurative (anthropomorphic or zoomorphic) drawings beyond the geometric and sigil repertoire were identified in the surveyed range.

### 3. Actors and Historical Context
**Henry Dawson Lea** appears as a private transcriber operating within the mid-Victorian English occult manuscript culture. His activity is best understood as part of a non-institutional network of collectors and copyists who preserved ceremonial magic texts that had limited circulation in university or medical libraries.

**Frederick Hockley** (1809–1885) was a more prominent figure: scryer, antiquarian, and manuscript collector whose library later fed institutional holdings, including the Wellcome. His annotations (1869) and ownership place MS.3203 within the continuum that links earlier Solomonic traditions to the source materials later used by the Hermetic Order of the Golden Dawn and related late-nineteenth-century occult societies. Financial independence allowed him to sustain a substantial private collection; the surviving record does not indicate commercial publication of this particular manuscript in his lifetime.

The broader cohort reflects a pattern of elite, private transmission of magical literature in nineteenth-century Britain — parallel to, yet distinct from, the contemporaneous medical and scientific collecting represented by the Wellcome’s other early acquisitions.

### 4. Network Analysis Pass (Spirit Hierarchies)
A seed hierarchical edge-list was generated (see `analysis/spirit_hierarchy_edges.csv`):

- Top-level: Solomon → Goetia / Theurgia  
- Goetia → 72 named spirits (Bael … Andromalius)  
- Theurgia → four emperors (Carnesiel, Caspiel, Amenadiel, Demoriel) → subordinate dukes and spirits  

This structure is suitable for import into Gephi (ForceAtlas2) or similar tools for visualisation of command hierarchies and modularity. The Theurgia corpus (pp. 111–150+) constitutes the denser subordinate network. Full named-entity extraction of every individual seal remains a residual task; the present edge-list provides the architectural backbone for subsequent quantitative work.

### 5. Licensing and Reuse
All source images and the underlying text of MS.3203 are under the **Public Domain Mark** (Wellcome Collection).  
This research inventory, protocol packaging, and derived catalogues are released to facilitate scholarly reuse. Attribution to the Wellcome Collection and to the Lea–Hockley transmission chain is requested as good practice.

### 6. Deliverables Produced
- Standardised symbol repository and inventory (schema-compliant)
- Google Drive project folder: https://drive.google.com/drive/folders/1NOlYKsnbrYxklSigPgNJzvnNMhTRBNyA
- GitHub repository: https://github.com/tuiringaariki22/ms3203-five-treatises-symbol-repository
- Page renders 121–150 (local artifacts)
- Seed hierarchy edge-list for network analysis
- This scholarly summary report

### 7. Residual Work & Recommended Pathways
1. Individual seal-level cataloguing and optional vectorisation of the Theurgia series.
2. Full Gephi / ForceAtlas2 visualisation of the hierarchy with modularity colouring by emperor.
3. Expanded literature review of Hockley’s manuscripts and their reception in Golden Dawn studies.
4. Cross-comparison with other Wellcome and British Library grimoires sharing the same textual tradition.
5. Integration into larger digital-humanities or claims-oriented research programmes as required.

---

*Prepared under the research-protocol-infrastructure skill. All stages (Discovery → Extraction → Analysis → Publication) applied.*
