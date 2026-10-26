# Graph Report - EmmaF  (2026-10-26)

## Corpus Check
- 2 files · ~54,415 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 293 nodes · 891 edges · 15 communities
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 33 edges (avg confidence: 0.81)
- Token cost: 118,493 input · 0 output

## Community Hubs (Navigation)
- Détection & supervision CyFun
- Cadres ReCyF / CyFun / ANSSI
- Veille & tests de vulnérabilités
- Identification des risques & incidents
- Référentiels nationaux
- Pays baltes & Danemark
- Identités & accès
- Gouvernance & crise
- Administration & cloisonnement
- Journalisation & sondes IDS
- Spécificités de supervision avancée
- Architecture & réseau
- MCO / MCS & correctifs
- SIEM, corrélation & CVD
- Pilotage & Hongrie

## God Nodes (most connected - your core abstractions)
1. `ReCyF (référentiel cyber français NIS2)` - 74 edges
2. `CyberFundamentals (CyFun) 2023` - 63 edges
3. `Estonia` - 39 edges
4. `CSF function 3 - Detect` - 33 edges
5. `Hungary` - 29 edges
6. `S1 Supervision et traitement des événements` - 29 edges
7. `Verdict: Commune, niveau de détail différent` - 25 edges
8. `Detection (Détection)` - 24 edges
9. `Lithuania` - 23 edges
10. `Denmark` - 22 edges

## Surprising Connections (you probably didn't know these)
- `MD-27: Réaliser des scans ou tests de vulnérabilités périodiques` --conceptually_related_to--> `Essential entities [EE] applicability`  [INFERRED]
  graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md → graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md  _Bridges community 13 → community 2_
- `MD-34: Rendre le trafic chiffré visible des outils de supervision (déchiffrement TLS/SSH)` --conceptually_related_to--> `Essential entities [EE] applicability`  [INFERRED]
  graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md → graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md  _Bridges community 13 → community 10_
- `MD-05: Protéger les journaux contre l'accès, la modification et la suppression non autorisés` --semantically_similar_to--> `MD-35: Garantir la non-répudiation des actions journalisées`  [INFERRED] [semantically similar]
  graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md → graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md  _Bridges community 9 → community 13_
- `ReCyF (référentiel cyber français NIS2)` --semantically_similar_to--> `CyberFundamentals (CyFun) 2023`  [INFERRED] [semantically similar]
  graphify-out/converted/Convergences_ReCyF_CyFun_par_obligation_d2005a48.md → graphify-out/converted/Convergences_ReCyF_CyFun_par_obligation_d2005a48.md  _Bridges community 6 → community 1_
- `Verdict: Exigence commune` --references--> `Mapping ANSSI ReCyF-CyFun`  [INFERRED]
  graphify-out/converted/Convergences_ReCyF_CyFun_par_obligation_d2005a48.md → graphify-out/converted/Convergences_ReCyF_CyFun_par_obligation_d2005a48.md  _Bridges community 1 → community 11_

## Hyperedges (group relationships)
- **Log lifecycle: define, timestamp, retain, protect, centralise, review** — graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_02, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_03, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_04, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_05, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_06, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_07 [INFERRED 0.85]
- **Vulnerability cycle: watch, process, scan, remediate** — graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_25, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_26, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_27, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_28 [INFERRED 0.85]
- **Detection toolchain: SIEM, IDS/IPS, correlation, automated alerting** — graphify_out_converted_nis2_monitoring_detection_6ea462f0_concept_siem, graphify_out_converted_nis2_monitoring_detection_6ea462f0_concept_ids_ips, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_10, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_13, graphify_out_converted_nis2_monitoring_detection_6ea462f0_md_09 [INFERRED 0.75]
- **Chaîne supervision / journalisation / incidents** — graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_s1, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_s2, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_s3, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_b2, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_e1 [INFERRED 0.85]
- **Gestion des vulnérabilités et correctifs** — graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_m1, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_m2, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_m3, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_m4, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_m5 [EXTRACTED 1.00]
- **Chantier administration dédiée ReCyF** — graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_d1, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_d2, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_d3, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_d4, graphify_out_converted_convergences_recyf_cyfun_par_obligation_d2005a48_obl_d5 [EXTRACTED 1.00]

## Communities (15 total, 0 thin omitted)

### Community 0 - "Détection & supervision CyFun"
Cohesion: 0.06
Nodes (52): Catégorie: Continuité et sauvegardes, Catégorie: Détection et supervision, CSF function 3 - Detect, CSF function 4 - Respond, CyFun DE.AE-1.1, CyFun DE.AE-2.1, CyFun DE.AE-2.2, CyFun DE.AE-3.1 (+44 more)

### Community 1 - "Cadres ReCyF / CyFun / ANSSI"
Cohesion: 0.14
Nodes (22): ANSSI, Catégorie: Inventaire et cartographie, Catégorie: Sécurité physique, Catégorie: Tiers et fournisseurs, Catégorie: Transverse, CSF function 5 - Recover, CyberFundamentals (CyFun) 2023, Convergences ReCyF / CyFun par obligation (+14 more)

### Community 2 - "Veille & tests de vulnérabilités"
Cohesion: 0.16
Nodes (23): CERT-FR, CSIRT, CSIRT Italia, EDR / antivirus signatures, ISAC (sector information sharing centres), OWASP ASVS L2, Vulnerability scan / penetration test, SAST / DAST / SCA / bug bounty (+15 more)

### Community 3 - "Identification des risques & incidents"
Cohesion: 0.12
Nodes (20): Catégorie: Gestion des incidents, CSF function 1 - Identify, CSF function 2 - Protect, CyFun DE.DP-4.1, CyFun ID.RA-1.1, CyFun ID.RA-1.2, CyFun ID.RA-2.1, CyFun ID.RA-2.2 (+12 more)

### Community 4 - "Référentiels nationaux"
Cohesion: 0.16
Nodes (21): Belgian referential (NIST CSF-style PR/DE categories), irma.cert.ee monitoring tool, X-tee (Estonian data exchange layer), Croatian cybersecurity measures (Basic Cyber Hygiene etc.), Danish executive order 6(1) (REQ / REC), Estonian E-ITS-style module catalogue (DER/OPS/SYS/NET/APP/IND/INF/CON), Finnish recommendations referential, French referential (MONITORING / MCO_MCS) (+13 more)

### Community 5 - "Pays baltes & Danemark"
Cohesion: 0.20
Nodes (21): DLP (data leak prevention), Latvian Constitution Protection Bureau, NTP time synchronisation (STRATUM 2), Operational technology (OT) passive monitoring, Privileged accounts, UEBA (user and entity behaviour analytics), Denmark, Estonia (+13 more)

### Community 6 - "Identités & accès"
Cohesion: 0.17
Nodes (18): Catégorie: Identités et accès (IAM), Catégorie: Ressources humaines, CyFun RS.AN-5.1, Entité importante (EI), A1 Comptes individuels et désactivation, A2 Revue des comptes et des droits, A3 Droits d'accès et moindre privilège, A4 Authentification et MFA (+10 more)

### Community 7 - "Gouvernance & crise"
Cohesion: 0.17
Nodes (14): Catégorie: Audit et amélioration continue, Catégorie: Crise et exercices, Catégorie: Gouvernance, CyFun DE.DP-3.1, G1 Organisation de la sécurité et responsable, G2 Responsabilité et engagement du dirigeant, G3 PSSI et politiques thématiques, G4 Pilotage de la conformité (+6 more)

### Community 8 - "Administration & cloisonnement"
Cohesion: 0.23
Nodes (13): Catégorie: Administration des SI, Catégorie: Gestion des risques, Entité essentielle (EE), D1 Comptes d'administration dédiés, D2 Annuaire et cœur de confiance (Tier 0), D3 Réseau d'administration dédié, D4 Postes et liaisons d'administration dédiés, D5 Flux d'administration protégés (+5 more)

### Community 9 - "Journalisation & sondes IDS"
Cohesion: 0.30
Nodes (15): IDS/IPS network probes, Log retention period (3 months FR to 3 years EE), NIDS / HIDS, WIDS / WIPS wireless intrusion detection, Belgium, Croatia, Netherlands, Slovakia (+7 more)

### Community 10 - "Spécificités de supervision avancée"
Cohesion: 0.22
Nodes (14): TLS-RPT mail encryption reporting, TLS/SSH traffic decryption for monitoring, MD-33: Détecter les anomalies de comportement des utilisateurs et entités (UEBA), MD-34: Rendre le trafic chiffré visible des outils de supervision (déchiffrement TLS/SSH), MD-36: Se protéger contre les attaques par déni de service, MD-38: Définir des niveaux de service attendus pour détecter tôt les incidents significatifs, MD-41: Remonter au gouvernement les non-conformités non corrigées des administrations publiques, MD-42: Décliner la supervision par type de composant (serveurs, pare-feu, DNS, NAC, téléphonie, archives…) (+6 more)

### Community 11 - "Architecture & réseau"
Cohesion: 0.18
Nodes (13): Catégorie: Architecture et réseau, Catégorie: Postes et équipements, CyFun DE.CM-1.1, CyFun DE.CM-4.1, C2 DMIA / PRD et PCA / PRA, N1 Cloisonnement des SI, N3 Passerelles entrantes et sortantes, N5 Pare-feu et revue des règles (+5 more)

### Community 12 - "MCO / MCS & correctifs"
Cohesion: 0.18
Nodes (11): Catégorie: Maintien en condition de sécurité, CyFun DE.CM-3.3, CyFun DE.CM-7.2, CyFun DE.CM-8.1, CyFun DE.CM-8.2, CyFun PR.MA-1.1, B1 Développement sécurisé et gestion des changements, M1 Procédure MCO / MCS (+3 more)

### Community 13 - "SIEM, corrélation & CVD"
Cohesion: 0.31
Nodes (9): Coordinated Vulnerability Disclosure (CVD), Non-repudiation of logged actions, SIEM (central log collection), Finland, Essential entities [EE] applicability, MD-06: Centraliser la collecte des journaux (serveur central, SIEM), MD-13: Corréler des sources multiples (journaux, vulnérabilités, performance, accès physiques), MD-29: Ouvrir un canal de réception des signalements de vulnérabilités (+1 more)

### Community 14 - "Pilotage & Hongrie"
Cohesion: 0.39
Nodes (8): Hungary, MD-14: Détecter les connexions, services et équipements non autorisés, MD-17: Contrôler l'intégrité des logiciels, micrologiciels et informations, MD-19: Vérifier régulièrement le bon fonctionnement des fonctions de sécurité et des outils de détection, MD-21: Formaliser une politique ou des procédures de journalisation et de détection, MD-23: Améliorer en continu la couverture de détection selon l'évolution des menaces, MD-37: Mesurer la performance de la sécurité par des indicateurs suivis, Governance (Pilotage)

## Ambiguous Edges - Review These
- `NIS2 Monitoring & Detection (13-country analysis)` → `MD-36: Se protéger contre les attaques par déni de service`  [AMBIGUOUS]
  graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md · relation: conceptually_related_to
- `NIS2 Monitoring & Detection (13-country analysis)` → `MD-41: Remonter au gouvernement les non-conformités non corrigées des administrations publiques`  [AMBIGUOUS]
  graphify-out/converted/NIS2_Monitoring_Detection_6ea462f0.md · relation: conceptually_related_to

## Knowledge Gaps
- **17 isolated node(s):** `NIS2 Directive`, `NTP time synchronisation (STRATUM 2)`, `Log retention period (3 months FR to 3 years EE)`, `EDR / antivirus signatures`, `DLP (data leak prevention)` (+12 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 22 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `CyberFundamentals (CyFun) 2023` connect `Cadres ReCyF / CyFun / ANSSI` to `Détection & supervision CyFun`, `Identification des risques & incidents`, `Identités & accès`, `Gouvernance & crise`, `Administration & cloisonnement`, `Architecture & réseau`, `MCO / MCS & correctifs`?**
  _High betweenness centrality (0.147) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `ReCyF (référentiel cyber français NIS2)` (e.g. with `CyberFundamentals (CyFun) 2023` and `Directive NIS2`) actually correct?**
  _`ReCyF (référentiel cyber français NIS2)` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `NIS2 Directive`, `NTP time synchronisation (STRATUM 2)`, `Log retention period (3 months FR to 3 years EE)` to the rest of the system?**
  _17 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Détection & supervision CyFun` be split into smaller, more focused modules?**
  _Cohesion score 0.06127946127946128 - nodes in this community are weakly interconnected._
- **Why does `ReCyF (référentiel cyber français NIS2)` connect `Identités & accès` to `Détection & supervision CyFun`, `Cadres ReCyF / CyFun / ANSSI`, `Identification des risques & incidents`, `Gouvernance & crise`, `Administration & cloisonnement`, `Architecture & réseau`, `MCO / MCS & correctifs`?**
  _High betweenness centrality (0.129) - this node is a cross-community bridge._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `NIS2 Monitoring & Detection (13-country analysis)` and `MD-36: Se protéger contre les attaques par déni de service`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `NIS2 Monitoring & Detection (13-country analysis)` and `MD-41: Remonter au gouvernement les non-conformités non corrigées des administrations publiques`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._