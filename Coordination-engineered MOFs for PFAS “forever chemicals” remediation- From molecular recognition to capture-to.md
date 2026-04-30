# Page 1

Coordination Chemistry Reviews 559 (2026) 217818
Contents lists available at ScienceDirect
Coordination Chemistry Reviews
journal homepage: www.elsevier.com/locate/ccr
Coordination-engineered MOFs for PFAS “forever chemicals” remediation:
From molecular recognition to capture-to-destruction architectures
Fouzia Mashkoora,1, Mohd Shoeba,1, Rushda Mashkoorb, Abul Kalamc, Changyoon Jeonga,*
aSchool of Mechanical Engineering, Yeungnam University, Gyeongsan, Gyeongbuk 38541, Republic of Korea
bDepartment of Chemical Engineering, ZHCET College, Aligarh Muslim University, Aligarh 202002, India
cDepartment of Chemistry, College of Science, King Khalid University P.O. Box 9004, Abha 61413, Saudi Arabia
A R T I C L E I N F O A B S T R A C T
Keywords: Per- and polyfluoroalkyl substances (PFAS) “Forever Chemicals” pose a persistent threat to water resources
PFAS because of the exceptional stability of C–F bonds, the structural diversity of PFAS classes, and increasingly
MOFs stringent drinking-water targets in the low ng/L range. Conventional technologies dominated by activated car-
Coordination chemistry
bons and ion-exchange resins often struggle with selectivity, regeneration, and the efficient removal of short-
Selectivity
chain, neutral, and zwitterionic PFAS. Metal-organic frameworks (MOFs) provide a distinctive remediation
Defects
Defluorination platform because metal-node coordination environments, linker chemistry, defect landscapes, and pore micro-
environments can be engineered with molecular precision. This review develops a coordination-chemistry
framework that connects PFAS molecular descriptors (headgroup identity, hydration, chain length, and pre-
cursor structures) to MOF design variables (Lewis acidity and coordinative unsaturation at nodes, linker elec-
tronics, pore topology, and fluorophilicity) to rationalize binding and selectivity beyond empirical capacity
metrics. PFAS uptake is organized into four interacting modes: outer-sphere electrostatic association, inner-
sphere node-headgroup coordination, anion exchange, and confinement-driven tail partitioning, clarifying
why paradigms derived from PFOS and PFOA can fail for short-chain and non-ionic PFAS. We compare key MOF
families while emphasizing competition from inorganic anions and natural organic matter, defect-mediated
capacity-durability trade-offs, and the distinction between structural robustness and coordination robustness
in realistic waters. Capture-to-destruction strategies using MOF-derived materials and hybrid photo- and elec-
trochemical systems are assessed with attention to coordination-enabled activation requirements and rigorous
transformation-product accounting. Finally, we outline translation priorities, including standardized testing,
regeneration and life-cycle durability, and integration into continuous-flow architectures.
1. Introduction chemical and thermal stability, low surface energy, and strong repel-
lency, enabling widespread use in aqueous film-forming foams, surface
Per- and polyfluoroalkyl substances (PFAS) “A Forever Chemicals” coatings, textiles, food-contact materials, and electronics manufacturing
rank among the most challenging contaminant classes in environmental [4–7]. Structurally, PFAS consist of fully or partially fluorinated alkyl
chemistry because of their exceptional persistence, global distribution, chains terminated by polar headgroups such as carboxylates, sulfonates,
and well-documented links to adverse health outcomes [1]. As drinking- or phosphonates; their resistance to thermal, chemical, and biological
water guideline values continue to tighten toward the low ng/L range, degradation is fundamentally rooted in the strength of C–F bonds and
effective PFAS treatment increasingly demands not only high capacity the shielding effect of dense fluorination [8]. PFAS contamination is
but also molecular selectivity and sustained performance in chemically now documented across surface waters, groundwater, drinking-water
complex water matrices at ultra-trace concentrations [2,3]. PFAS orig- supplies, soils, and biota, spanning ng/L background levels to mg/L
inated from industrial fluorochemistry and expanded rapidly after the concentrations at industrial hot spots [9–12]. Many PFAS exhibit long
mid-20th century because densely fluorinated backbones impart biological half-lives, extending to years for PFOS and PFOA in human
* Corresponding author.
E-mail address: yoonni22@yu.ac.kr(C. Jeong).
1 Authors have equal contribution.
https://doi.org/10.1016/j.ccr.2026.217818
Received 30 January 2026; Accepted 5 March 2026
Available online 13 March 2026
0010-8545/© 2026 Elsevier B.V. All rights are reserved, including those for text and data mining, AI training, and similar technologies.

# Page 2

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
serum, and epidemiological and toxicological studies associate chronic Metal-organic frameworks (MOFs) provide a fundamentally different
exposure with a range of adverse outcomes [11,12]. The consequences approach. The 2025 Nobel Prize in Chemistry recognizing MOF devel-
of delayed control are exemplified by the Veneto (Italy) contamination opment highlights the maturity and chemical significance of reticular
case, where long-term releases from the Miteni facility impacted chemistry as a platform for designing porous materials with precisely
drinking-water sources across multiple provinces and necessitated tunable function [31,32]. Built from metal ions or clusters bridged by
emergency treatment measures and long-term health surveillance multitopic organic linkers, MOFs offer crystalline architectures with
(Fig. 1) [13–15]. To contextualize the chemical challenges discussed exceptional control over pore size, topology, and chemical functionality,
below, Figs. 2a-c summarizes PFAS subclasses and structural diversity, enabling high internal surface areas, large pore volumes, and well-
Fig. 2d-e outlines major exposure pathways and regulatory milestones, defined binding environments [33,34]. This modular coordination
and Table 1 compiles representative physicochemical and biological chemistry has enabled broad applications in separation, catalysis,
properties of widely studied PFAS. sensing, and water purification, and increasingly in the capture and
From a coordination-chemistry perspective, PFAS are intrinsically transformation of persistent aqueous pollutants [35]. For PFAS reme-
difficult molecular targets because their removal involves a coupled diation, MOFs offer an unusually rich and programmable design space.
headgroup-tail recognition problem. Anionic PFAS headgroups Their modular architectures allow largely independent tuning of metal-
(carboxylate, sulfonate, phosphonate) behave as hard oxygen-donor node identity, linker electronics, pore size and shape, surface charge,
bases, yet they are stabilized by tightly bound hydration shells in hydrophobicity or fluorophilicity, and defect density [29]. This
water, particularly for short-chain PFAS, which increases the energetic orthogonal control enables targeted optimization of PFAS uptake and, in
cost of desolvation and binding [28]. At the same time, the per- selected systems, catalytic activation. Interconnected pore networks can
fluorinated tail is weakly polarizable and hydrophobic, and it packs promote rapid mass transport and preconcentration at ultra-trace levels,
differently from hydrocarbon chains; as a result, confinement effects, while well-defined coordination sites within confined pores support
fluorophilic interactions, and tail-driven partitioning can dominate specific interactions with PFAS headgroups through coordination,
selectivity even when headgroup coordination is thermodynamically electrostatics, hydrogen bonding, and ion exchange. In parallel, tail-
favorable [29]. These coupled effects complicate molecular recognition driven effects, including hydrophobic or fluorophilic packing and
under realistic conditions, where effective treatment must discriminate short-range contacts such as π-CF and F … F interactions, can further
among diverse PFAS while competing with abundant inorganic anions modulate selectivity and chain-length dependence [28]. Importantly,
and natural organic matter at ultra-trace concentrations [30]. These MOFs can also be integrated with photocatalytic, electrochemical, or
chemical constraints explain the predictable limitations of established redox-active components, or converted into MOF-derived materials,
treatment technologies. Activated carbons rely largely on nonspecific enabling closer coupling between capture and in situ transformation.
hydrophobic interactions and pore filling, which favor long-chain PFAS Beyond surface area considerations, PFAS-MOF interactions are funda-
but often perform poorly for short-chain, strongly hydrated, or ether- mentally governed by coordination chemistry. PFAS headgroups act as
containing species, particularly in natural waters where organic mat- hard oxygen-donor bases and preferentially interact with hard or
ter competes for adsorption sites [30]. Ion-exchange resins provide borderline Lewis-acidic nodes such as Zr(IV), Al(III), Fe(III), and many
electrostatic capture but frequently show limited selectivity among rare-earth centers [21,36–38]. The geometry, connectivity, and degree
competing anions, slow intraparticle transport, and secondary waste of coordinative unsaturation of the secondary building units dictate
burdens during regeneration. Membrane separations can be effective for binding strength, accessible site density, and resistance to displacement
PFAS rejection, but they concentrate contaminants into brines that still by water and competing anions. Simultaneously, fluorinated tails
require downstream destruction. Collectively, these outcomes reflect a interact with pore environments defined by linker polarity and fluo-
shared limitation: conventional platforms offer limited control over the rophilicity, influencing selective partitioning within MOF channels
coordination environment experienced by PFAS headgroups and little [21,36,38]. The coupling of headgroup-node coordination and tail-pore
ability to independently tune the microenvironment that accommodates interactions therefore renders PFAS remediation an intrinsically
fluorinated tails. Moreover, capture and destruction are typically treated coordination-controlled problem, positioning MOFs as uniquely capable
as disconnected steps rather than as a unified, chemistry-enabled pro- platforms for selective capture and catalytic transformation [21,36–38].
cess [2,28]. Although several reviews have addressed MOFs for water
Fig. 1. Protest against PFAS contamination in Italy, with activists displaying banners reading “STOP PFAS” and “PERICOLO PFAS” during a demonstration high-
lighting the health and environmental risks of “forever chemicals” [15].
2

# Page 3

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 2. (a) Chemical structures of PFAS. Reproduced with permission [16]. Copyright 2017, Elsevier. (b) Basic structural features of a PFAS. Reproduced with
permission [17]. Copyright 2022, Elsevier. (c) “Family tree” of PFASs, Reproduced with permission [18]. Copyright 2017, American Chemical Society. (d) Pathways
of direct human exposure of PFAS and its potential health effects, Reproduced with permission [19]. Copyright 2020, MDPI. (e) Chronological timeline of major
regulatory, policy, and guideline milestones governing PFAS from 2000 to 2024, Reproduced with permission [12]. Copyright 2024, Royal Society of Chemistry.
remediation and PFAS removal, important gaps remain. Much of the than retrospective performance comparison [21,36,37]. An overview of
existing literature emphasizes long-chain anionic PFAS, particularly the major MOF families investigated for PFAS adsorption, the corre-
PFOS and PFOA, and focuses on adsorption capacities and kinetic fitting sponding structural/chemical tunability and functionalization strate-
rather than on coordination environment, node speciation, and pore- gies, and the rapid growth of MOF-enabled PFAS research is summarized
level molecular recognition [21,36,37]. Short- and ultrashort-chain in Fig. 3a-c [21,29].
PFAS, neutral and zwitterionic species, competitive effects in realistic In this review, we develop a coordination-chemistry framework for
matrices, and process-relevant considerations such as shaping, dura- understanding and designing MOF-based systems for PFAS remediation.
bility, and capture-to-destruction strategies remain underdeveloped We first distill the structural diversity of PFAS and the resulting con-
[30,37]. Here, we adopt a coordination-chemistry-centered perspective straints on molecular recognition in aqueous environments. We then
that links PFAS molecular structure to MOF node, linker, and pore critically analyze PFAS adsorption across major MOF families by
design, enabling mechanistic interpretation and predictive design rather focusing on metal-node identity, linker electronics, defect chemistry,
3

# Page 4

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 2. (continued).
Table 1
Chemical names, generic structures, and selected physicochemical properties of PFASa [20–27].
Compound type Common name Acronym Structural type Formula log Kow pKa MW (g/ Half -life
mol)
Legacy long-chain Perfluorooctanoic acid PFOA Perfluoroalkyl C8HF15O2 – (cid:0) 0.20 414.07 2–4 years
PFCA carboxylic acid
Legacy long-chain Perfluorooctanesulfonic PFOS Perfluoroalkyl C8HF17O3S – (cid:0) 3.27 500.13 4–6 years
PFSA acid sulfonic acid
Long-chain PFSA Perfluorohexanesulfonic PFHxS Perfluoroalkyl C6HF13O3S – 0.14 400.11 5–8 years
(regulatory acid sulfonic acid
concern)
Long-chain PFCA Perfluoroheptanoic acid PFHpA Perfluoroalkyl C7HF13O2 – (cid:0) 0.19 364.06 62 days
(environmental carboxylic acid
marker)
Mid-chain PFCA Perfluorohexanoic acid PFHxA Perfluoroalkyl C6HF11O2 – (cid:0) 0.16 314.05 14–49 days
carboxylic acid
Short-chain PFCA Perfluorobutanoic acid PFBA Perfluoroalkyl C4HF7O2 – 0.40 214.04 72–81 h
replacement carboxylic acid
Short-chain PFSA Perfluorobutanesulfonic PFBS Perfluoroalkyl C4HF9O3S – 0.14 300.09 ~44 days
replacement acid sulfonic acid
Short-chain PFSA Perfluoropentanesulfonic PFPeS Perfluoroalkyl C5HF11O3S – 0.14 350.10 1 years
derivative acid sulfonic acid
Ether PFCA (GenX Hexafluoropropylene oxide HFPO- Polyfluoroalkyl CF3(CF2)2OCF(CF3)COOH 3.93 (cid:0) 0.20 330 –
technology) dimer acid DA ether carboxylic
acid
Ether PFCA 4,8-Dioxa-3H- ADONA Polyfluoroalkyl CF3OCF2CF2CF2OCHCF2COOH 4.81 (cid:0) 0.04 359 –
replacement perfluorononanoic acid ether carboxylic
acid
Ether PFSA Polyfluoroalkyl ether PFESAs Polyfluoroalkyl HCF2CF2OCF2CF(CF3) 5.22 – 464 ~15.3
replacement sulfonic acid ether sulfonic acid OCF2CF2SO3H years
Ether PFSA (short- Polyfluoroalkyl ether ether- Polyfluoroalkyl CF3O(CF2)5SO3H 4.85 – 416 ~15.3
chain analogue) hexane sulfonic acid PFHxS ether sulfonic acid years
Chlorinated ether Chlorinated polyfluoroalkyl Cl- Cl-substituted Cl(CF2CF2)nOCF2CF2SO3H (n 6.04–8.45 – 532.5–732.5 10.1–56.4
PFSA (F-53B- ether sulfonic acids PFESAs ether sulfonic =3–5) years
type) acids
Chlorinated PFCA Chlorine-substituted Cl-PFCAs Cl-substituted Cl(CF2)nCOOH (n =4–11) 2.90–7.12 (cid:0) 0.63 280.5–630.5 19–3 days
perfluorocarboxylic acids perfluoroalkyl to
carboxylic acids (cid:0) 0.28
and pore microenvironments, with particular attention to competitive materials, emphasizing how coordination environment and framework
effects in realistic water matrices and to species beyond PFOS and PFOA. design influence C–F bond activation. Finally, we identify key chal-
We next examine MOF-enabled pathways for PFAS transformation, lenges and opportunities for translation, including durability, regener-
including photo- and electro-driven processes and MOF-derived ation, operation at ng/L concentrations, and the integration of capture
4

# Page 5

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 3. Schemic illustration of various MOF structures employed for PFAS adsorption, Reproduced with permission [21]. Copyright 2025, American Chemical
Society. (b) General introduction of MOFs, Reproduced with permission [29]. Copyright 2024, Springer Nature. (c) The number of research articles and review
articles on MOFs for the treatment of PFAS based on a Scopus search.
and destruction within scalable treatment architectures. By framing 2. Structural foundations of MOFs relevant to PFAS remediation
PFAS remediation as a coordination-controlled problem rather than an
adsorption-capacity comparison, this review aims to provide transfer- MOFs are crystalline porous coordination networks constructed from
able design principles to guide the development of selective, robust, and metal ions or metal-oxo clusters linked by multitopic organic ligands.
functionally integrated MOF-based remediation platforms. Their modular architecture allows systematic control over pore size,
5

# Page 6

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
topology, and chemical functionality through variation of metal nodes particles with high surface accessibility. Electrochemical synthesis en-
and organic linkers. As a result, MOFs exhibit large internal surface ables in-situ generation of metal ions and can produce MOF films or
areas, ordered pore networks, and chemically well-defined adsorption coatings on conductive substrates, while mechanochemical routes allow
environments, which make them attractive materials for adsorption, rapid solvent-limited synthesis of various Zn-, Cu-, Zr-, and Al-based
catalysis, and environmental remediation [39]. The fundamental frameworks [66–69]. For practical water-treatment applications, scal-
structural feature of MOFs is the formation of secondary building units able production and material shaping are increasingly important.
(SBUs) in which metal ions or clusters coordinate with organic ligands to Continuous-flow synthesis improves control over reaction conditions
generate extended three-dimensional frameworks. The coordination and enables higher space-time yields, while spray-drying, extrusion, and
number, oxidation state, and geometry of the metal centers determine pelletization convert MOF powders into mechanically stable forms
the acidity, charge distribution, and accessibility of adsorption sites suitable for packed-bed or filtration systems [70–83]. In the context of
inside the pores. At the same time, linker length, rigidity, and func- PFAS remediation, synthesis conditions strongly influence defect den-
tionalization regulate pore aperture, surface polarity, and local chemical sity, pore accessibility, and exposure of Lewis-acidic metal sites, all of
environment. Through this reticular design strategy, a wide range of which affect PFAS adsorption performance.
MOF families with controllable pore architectures and coordination
environments have been developed, including IRMOFs, HKUST-type 3.1. Conventional (batch) solvothermal synthesis
frameworks, zeolitic imidazolate frameworks (ZIFs), MIL-type struc-
tures, and UiO-type Zr-based MOFs [40–50]. The evolution of coordi- Conventional solvothermal synthesis remains one of the most widely
nation frameworks and the reticular design principles underlying used approaches for preparing metal-organic frameworks. In this
modern MOF architectures are illustrated in Fig. 4a-b. method, metal salts and organic linkers react in polar solvents such as
For PFAS remediation, several MOF families have attracted partic- DMF, DEF, NMP, alcohols, or water within sealed vessels at elevated
ular attention because of their hydrolytic stability and accessible Lewis- temperatures, typically in the range of 80–250 ◦C. Under these condi-
acidic metal sites. UiO-type Zr(IV) frameworks, constructed from tions, elevated temperature and autogenous pressure promote linker
Zr6O4(OH)4 clusters, exhibit exceptional structural robustness in deprotonation, assembly of secondary building units (SBUs), and
aqueous environments together with strongly oxophilic metal centers. controlled crystal growth. Non-solvothermal routes employ similar co-
The μ 3-oxo and μ 3-hydroxo groups within these clusters create hard ordination chemistry but operate at reflux or lower temperatures under
Lewis-acidic sites capable of interacting strongly with PFAS headgroups ambient pressure, which can be advantageous for frameworks that
such as carboxylates and sulfonates through electrostatic attraction, crystallize readily in water or low-boiling solvents and for synthesis
hydrogen bonding, or inner-sphere coordination [36,51–54]. MIL-type protocols aimed at reducing solvent toxicity or energy consumption
Fe-based frameworks, including MIL-100 and MIL-101, contain trinu- [85–88]. In both regimes, nucleation and crystal growth are governed by
clear Fe3O clusters that provide multiple accessible coordination sites several key parameters, including precursor concentration, solvent co-
and large mesoporous cages. These structural characteristics facilitate ordination strength, ligand acidity, pH, and the presence of modulators
PFAS adsorption through Lewis acid-base interactions with PFAS such as monocarboxylic acids or mineral acids/bases [89,90]. Careful
headgroups while also allowing pore-confinement and hydrophobic in- adjustment of these variables allows control over crystal size,
teractions to stabilize fluorinated chains within the framework [55–57]. morphology, phase purity, and defect density. These principles underpin
Other MOF systems, such as Al-based frameworks and selected rare- the classical synthesis of many well-known MOFs, including HKUST-1,
earth MOFs, combine high charge density and oxophilic metal centers MOF-5, MIL-100/MIL-101, and UiO-type frameworks. In particular,
with diverse coordination geometries, enabling strong binding of the use of monocarboxylic acid modulators and controlled water content
anionic PFAS species in aqueous environments [58–62]. has proven effective for tuning particle size and introducing missing-
In addition to metal-node chemistry, the pore microenvironment of linker or missing-cluster defects in Zr-based frameworks, features that
MOFs plays a crucial role in PFAS affinity. Linker functionalization, can significantly influence adsorption and catalytic behavior
defect engineering, and mixed-metal nodes can modify pore polarity, [63,91–95].
hydrophobicity, and electrostatic potential. These structural modifica- Beyond framework discovery, solvothermal conditions can also be
tions influence both the coordination interactions between PFAS head- used to engineer hierarchical porosity and tailored morphologies. For
groups and metal centers and the accommodation of perfluorinated tails example, solvothermal synthesis has been used to generate bimetallic
within pore channels. Consequently, the balance between coordination MOFs with microsphere assemblies composed of nanosized crystallites,
chemistry, electrostatic attraction, and hydrophobic or fluorophilic in- structures that enhance mass transport and increase exposure of acces-
teractions determines PFAS adsorption behavior in MOF systems. These sible coordination sites [96]. Similar approaches have been applied to
structural characteristics form the basis for understanding PFAS binding zeolitic imidazolate frameworks (ZIFs), where alcohol- or water-rich
mechanisms and adsorption performance in MOF materials, which are solvothermal systems provide improved control over crystal growth
discussed in the following sections. while avoiding some of the limitations associated with high-boiling
organic solvents [97–99]. Despite its versatility, classical batch synthe-
3. Synthesis of MOFs sis presents several limitations, including relatively long reaction times,
high energy consumption, and the use of large volumes of high-boiling
MOFs are commonly synthesized through coordination reactions solvents that often require post-synthetic activation steps. These chal-
between metal salts and multitopic organic ligands under solvothermal lenges have motivated the development of alternative synthesis strate-
or hydrothermal conditions, typically at 80–250 ◦C. These conditions gies such as microwave-assisted, sonochemical, mechanochemical, and
allow controlled nucleation and crystal growth and have been widely continuous-flow approaches, which aim to preserve the underlying co-
used for preparing archetypal frameworks such as MOF-5, HKUST-1, ordination chemistry while improving mass transfer and reaction effi-
MIL-101, and UiO-type MOFs. Reaction parameters including solvent ciency [100,101]. Nevertheless, solvothermal synthesis remains an
composition, temperature, pH, precursor concentration, and modulators important platform for the discovery and optimization of MOF mate-
influence framework connectivity, crystal morphology, and defect rials. From the perspective of PFAS remediation, these synthesis condi-
density. The major synthesis routes and key parameters governing MOF tions provide a flexible means of tuning defect density, pore
formation are summarized in Fig. 5[63–65]. To reduce reaction time architecture, and accessibility of Lewis-acidic metal sites, all of which
and improve synthetic efficiency, several alternative approaches have influence PFAS adsorption behavior and stability in aqueous environ-
been developed. Microwave-assisted and sonochemical methods accel- ments. A representative solvothermal synthesis workflow for Cu-based
erate nucleation and crystallization, often producing nanoscale MOF MOFs is illustrated in Fig. 6a [102].
6

# Page 7

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 4. (a) Historical evolution of coordination chemistry leading to modern MOFs, Reproduced with permission [39]. Copyright 2018, American Chemical Society.
(b) Representative examples of reticular design in MOFs, showing the use of common metal-carboxylate secondary building units combined with different organic
linkers to generate diverse framework topologies and pore environments, Reproduced with permission [39]. Copyright 2018, American Chemical Society.
7

# Page 8

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 5. Various synthesis methods of MOF materials, Reproduced with permission [84]. Copyright 2022, Royal Society of Chemistry.
3.2. Microfluidic synthesis (“numbering-up”), and modular continuous-flow platforms are
improving productivity and enabling gram-scale production while
Microfluidic synthesis has emerged as an effective complement to maintaining precise control over nucleation and growth [108,109]. In
conventional solvothermal routes, particularly when rapid screening, PFAS-related applications, these platforms provide a useful route for
precise particle-size control, and tunable defect structures are required. screening coordination environments and defect structures under real-
In microfluidic reactors, reactants are confined to microliter- or istic water chemistries and for producing narrowly dispersed MOF
nanoliter-scale volumes that flow through narrow channels or form particles suitable for integration into membranes or packed-bed
droplets segmented by an immiscible carrier fluid. The high surface- adsorption systems. A representative continuous microfluidic synthesis
area-to-volume ratio, short diffusion distances, and efficient heat of HKUST-1 is illustrated in Fig. 6b [110].
transfer in these systems significantly accelerate nucleation and crystal
growth, often reducing MOF synthesis times from hours to minutes
3.3. Microwave-assisted synthesis
while improving particle-size uniformity [103,104].
Early work demonstrated that droplet-based microfluidic sol-
Microwave (MW) heating provides a rapid route for preparing MOFs
vothermal systems can continuously produce frameworks such as MOF-
by accelerating nucleation and crystal growth relative to conventional
5, IRMOF-3, HKUST-1, and UiO-66 with reaction kinetics substantially
solvothermal heating. In MW-assisted synthesis, electromagnetic radi-
faster than batch autoclave synthesis while maintaining phase purity
ation couples directly with polar solvents, metal ions, and linkers
and narrow size distributions [104]. In continuous nanoliter reactors,
through dipolar polarization and ionic conduction, resulting in rapid
parameters including residence time, flow-rate ratios between phases,
volumetric heating and steep temperature ramps. These conditions
and supersaturation levels provide additional control over crystal size,
enhance ion mobility and collision frequency, significantly shortening
morphology, and defect density. These capabilities enable the fabrica-
crystallization times from hours or days to minutes while often main-
tion of hierarchical structures and composite architectures, including
taining high yields and phase purity [111]. Early studies demonstrated
core-shell particles and MOF-polymer composites formed directly within
that classical frameworks such as MOF-5 and HKUST-1 can be synthe-
microchannels [104,105].
sized using microwave irradiation by adapting solvothermal reaction
Compared with single-phase microreactors, droplet or segmented-
mixtures to MW conditions. For example, MOF-5 crystallization can
flow systems offer advantages for MOF synthesis because each droplet
begin within approximately 15 min, with well-defined crystals obtained
functions as an isolated microreactor. This configuration minimizes
in less than 30 min under optimized conditions [112]. Similar behavior
channel fouling, enables high-throughput parallelization, and facilitates
has been reported for other Zn- and Cu-based frameworks, although
combinatorial screening of synthesis parameters such as metal-linker
excessive power or temperature can lead to smaller crystals or increased
ratios, temperature, and additive concentrations. Such capabilities are
defect formation, indicating the need for careful control of microwave
particularly useful for rapidly evaluating MIL-, UiO-, and ZIF-type
power, precursor concentration, and reaction temperature [113,114].
frameworks and related composites relevant to PFAS adsorption and
MW-assisted synthesis offers several advantages for MOF preparation,
degradation [21,36,106,107]. Although early microfluidic systems were
including drastically reduced reaction times, tunable particle sizes
considered low-throughput, advances in channel design, parallelization
ranging from microcrystals to nanoparticles, high product yields, and
8

# Page 9

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 6. Solvothermal synthesis method of CuMOF, Reproduced with permission [102]. Copyright 2019, American Chemical Society. (b) Microfluidic synthesis of
HKUST-1, Reprinted with permission [110]. Copyright 2018, Royal Society of Chemistry. (c) Microwave-assisted synthesis of Zr-based MOF, Reprinted with
permission [116]. Copyright 2021, Elsevier.
improved energy efficiency compared with conventional solvothermal bulk solvent. As a result, MOF formation can occur rapidly, often within
heating [113]. At the same time, limitations arise from variations in 10–60 min at ambient temperature, with high yields and reduced sol-
microwave field distribution and reactor design, which can complicate vent consumption [69,117]. Three main mechanochemical approaches
reproducibility and lead to localized heating if temperature and power are typically employed for MOF synthesis: neat grinding (NG), liquid-
are not carefully controlled [113,115]. Recent developments integrating assisted grinding (LAG), and ion- and liquid-assisted grinding (ILAG).
MW heating with continuous-flow reactors and greener solvent systems In NG, solid precursors are milled without added solvent, providing a
have improved the scalability of this method for MOF production highly solvent-efficient route but often limited by slow diffusion of metal
[63,78,113]. In the context of PFAS remediation, microwave-assisted ions and linkers. Early examples include solvent-free preparation of
synthesis provides an efficient route for producing nanocrystalline and microporous frameworks such as [Cu(INA)2] through ball milling of
defect-engineered MOFs with enhanced accessibility of metal coordi- copper acetate and isonicotinic acid, demonstrating the feasibility of
nation sites and improved adsorption performance. A representative rapid coordination network formation under solid-state conditions
microwave-assisted synthesis route for Zr-based MOFs is illustrated in [118–120].
Fig. 6c [116]. To enhance mass transport and crystallinity, LAG introduces small
amounts of liquid additives that facilitate linker deprotonation, inter-
mediate stabilization, and framework assembly. This strategy signifi-
3.4. Mechanochemical synthesis cantly broadens the accessible MOF library and has enabled rapid
synthesis of porous frameworks such as MOF-74 and UiO-66 analogues
Mechanochemical synthesis (MS) has emerged as an efficient and from metal oxides and organic linkers within minutes while dramati-
sustainable approach for preparing MOFs, driven by the broader effort cally reducing solvent consumption relative to solvothermal methods
to develop solvent-minimized and energy-efficient synthetic routes. In [121–125]. ILAG further extends this approach by introducing both
mechanochemistry, mechanical forces such as impact, shear, and liquid additives and small quantities of inorganic salts, which can pro-
compression activate solid reactants, generating defects and high- mote reagent dissolution, influence nucleation pathways, and direct
contact surfaces that promote coordination bond formation without
9

# Page 10

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
formation of particular framework topologies or defect structures [69] preparing MOFs, particularly when nanoscale control and rapid crys-
[122]. Mechanochemical synthesis has also progressed toward scalable tallization are required [130]. Ultrasound irradiation promotes homo-
production. Continuous processes such as twin-screw extrusion provide geneous nucleation and significantly shortens reaction times compared
controlled shear and residence time, enabling continuous synthesis of with conventional heating. This effect arises from acoustic cavitation,
frameworks including ZIF-8 and HKUST-1 with high space-time yields where formation and collapse of microbubbles generate localized high
and minimal solvent usage [126]. In parallel, in-situ characterization temperatures and pressures, together with rapid heating and cooling
methods such as synchrotron powder X-ray diffraction and Raman rates. These conditions enhance mixing, accelerate ligand deprotonation
spectroscopy have revealed complex amorphization–recrystallization and metal-ligand coordination, and often favor nucleation over crystal
pathways and metastable intermediates during mechanochemical MOF growth, producing smaller and more uniform MOF particles [131–133].
formation [127,128]. Mechanochemical routes offer several advantages Sonochemical protocols have been successfully applied to a range of
compared with conventional solvothermal synthesis, including reduced MOF systems. Early studies demonstrated rapid formation of frame-
solvent consumption, shorter reaction times, and compatibility with works such as MOF-177 and other Cu-based MOFs using ultrasound-
inexpensive metal oxide precursors and continuous processing tech- assisted synthesis, often with reduced reaction times and improved en-
nologies [67,121]. For PFAS remediation, these methods are particu- ergy efficiency compared with solvothermal methods [132,134]. Ul-
larly attractive for scalable production of MOF powders and MOF- trasound has also enabled control over framework features such as
polymer composites that can be shaped into pellets, beads, or mono- interpenetration and defect density; for example, tuning ultrasonic
lithic structures while preserving defect sites and pore accessibility power during synthesis of CuTATB frameworks allows modulation of
important for PFAS adsorption. A representative mechanochemical catenation and adsorption behavior [135]. Similarly, Zr-based por-
synthesis route is illustrated in Fig. 7a [129]. phyrinic MOFs such as MOF-525 and MOF-545 have been prepared
within minutes to hours with high phase purity and enhanced defect
concentrations relative to conventional routes [133,136]. More
3.5. Sonochemical synthesis
recently, sonochemical synthesis has been extended to diverse MOF
systems, including Fe-based frameworks and rare-earth BTC structures
Sonochemical synthesis has emerged as an efficient approach for
Fig. 7. (a) Mechanochemical synthesis method of cobalt-doped-ZIF-8, Reproduced with permission [129]. Copyright 2020, Elsevier. (b) Sonochemical synthesis of
ZIF-8, Reproduced with permission [140]. Copyright 2013, Elsevier. (c) Electrochemical synthesis of Zn3(BTC)2, Reprinted with permission [157]. Copyright 2014,
Royal Society of Chemistry.
10

# Page 11

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
prepared under greener aqueous conditions [137–139]. Integration of pre-defined inorganic “secondary building units” (SBUs) and organic
ultrasound with continuous-flow or two-phase reactors has further ligands into extended frameworks with predictable topologies, pore
improved productivity, enabling high space-time yields and uniform architectures, and functionalities [158]. This structural programma-
particle formation while minimizing fouling during scale-up [73]. For bility, together with record-high surface areas, large and accessible pore
PFAS remediation, sonochemical synthesis is particularly attractive volumes, and a rich palette of metal-ligand combinations, underpins the
because it provides rapid access to nanocrystalline and defect-rich MOFs broad utility of MOFs in gas storage and separation, catalysis, sensing,
with short diffusion pathways and high densities of accessible coordi- drug delivery, and environmental remediation [85,159,160]. Within
nation sites. These structural features can enhance adsorption kinetics this family, MOFs have emerged as particularly promising platforms for
and facilitate integration of MOF materials into coatings, membranes, or the removal and sensing of per- and polyfluoroalkyl substances (PFAS),
composite adsorbents for water-treatment applications. A representative because they couple high density of accessible binding sites with pre-
ultrasound-assisted MOF synthesis process is illustrated in Fig. 7b [140]. cisely engineered pore environments and metal-ligand coordination
spheres. Their effectiveness in PFAS remediation stems from several key
3.6. Electrochemical synthesis of MOFs features: (i) the ability to position hard or borderline Lewis-acidic metal
centers, basic or hydrogen-bonding organic functional groups, and
Electrochemical synthesis provides an alternative route for MOF charged linker moieties in well-defined coordination environments; (ii)
preparation in which metal ions are generated in situ through anodic tunable hydrophobic/hydrophilic balance and fluorophilic character
dissolution of a metallic electrode [141]. In this approach, the metal inside the pores; and (iii) the possibility to match pore size, shape, and
electrode serves as the precursor for the framework nodes, while organic connectivity with PFAS chain length, headgroup functionality, and ag-
linkers and supporting electrolyte are dissolved in the reaction medium. gregation state [21,36,42]. As a result, MOFs offer a rare combination of
This strategy enables MOF formation under relatively mild conditions, structural porosity, chemical stability, and selective host-guest in-
often near room temperature and atmospheric pressure, with reaction teractions that can be rationally tuned to target both long- and short-
times ranging from minutes to a few hours [142,143]. Because the metal chain PFAS, as well as emerging non-ionic and zwitterionic analogues.
supply rate is controlled electrochemically, parameters such as applied The fundamental coordination-chemistry principles that guide MOF
potential, current density, and waveform provide additional control design for PFAS interactions are summarized in Fig. 8a.
over nucleation and crystal growth beyond the variables available in
conventional solvothermal synthesis [144,145]. Early studies demon- 4.1. HSAB considerations, competing anions, and linker-controlled
strated the electrochemical formation of Cu-based frameworks such as acidity
HKUST-1, whose crystallographic features closely resemble those of
solvothermally prepared analogues [142,143]. One advantage of this From a structural viewpoint, MOFs have gained attention because
method is the ability to grow MOFs directly as coatings or thin films on they allow atomistic control over metal nodes, organic linkers, pore
conductive substrates. For example, controlled electrochemical deposi- structures, and framework topology. At the level of coordination
tion has enabled spatially resolved Cu3(BTC)2 films on patterned copper chemistry, PFAS headgroups can be regarded as hard, oxygen-donor
surfaces and thin MOF layers on meshes or hollow fibers [146–149]. bases [161,162]. Perfluoroalkyl carboxylates, sulfonates, and phospho-
Subsequent developments have extended this approach to other sys- nates all present deprotonated XO3 (cid:0) /XO4 2(cid:0) groups (X =C, S, P) with high
tems, including electrodeposited MIL-type frameworks and continuous charge density and low polarizability, which interact most strongly with
MOF membranes grown on conductive supports [147,150]. Electro- hard or borderline hard Lewis-acidic metal centers [36,161]. This simple
chemical growth of Zr-based membranes such as UiO-66-NH2 has also hard-soft acid-base (HSAB) picture rationalizes why many PFAS-
demonstrated promising structural uniformity and porosity for separa- selective MOFs are built from high-valent, oxophilic nodes such as Zr
tion applications [151–154]. Compared with purely solvothermal (IV), Hf(IV), Ti(IV), Al(III), Fe(III), and trivalent or tetravalent rare-earth
routes, electrochemical synthesis offers additional flexibility because cations, often assembled into μ 3-oxo/μ 3-hydroxo cluster SBUs
both chemical and electrical parameters influence framework forma- [30,163–165]. These nodes offer strongly Lewis-acidic M-OH2/M-OH
tion. Adjusting potential, current density, and electrolyte composition sites or open M sites that can coordinate PFAS headgroups through
can affect nucleation rates, crystal morphology, and oxidation states of inner-sphere M-O-C(O) or M-O-S(O)2 linkages, or through outer-sphere
metal centers. At the same time, careful control of cathodic reactions ion pairing within hydrogen-bonding networks [7]. However, HSAB
and solvent electrochemistry is required to avoid competing processes arguments alone are insufficient to predict PFAS selectivity in realistic
such as hydrogen evolution or solvent reduction [143]. Recent advances waters. PFAS selectivity in MOFs is also controlled by pore-level mo-
emphasize integrating electrochemical MOF synthesis with greener lecular recognition, not only HSAB matching at metal nodes [166].
solvents and continuous-flow platforms, highlighting its potential as an Cooperative interactions can include electrostatics/ion pairing, hydro-
energy-efficient and scalable production strategy [63,155,156]. For phobic association of the perfluoroalkyl tail with nonpolar pore walls,
PFAS remediation, electrochemically synthesized MOFs are particularly hydrogen bonding near polar groups, and fluorophilic F–F interactions,
attractive because thin films or membranes grown on conductive sup- which together can bias PFAS partitioning into the framework under
ports can combine adsorption with electrochemically driven degrada- competitive aqueous conditions [28,167,168]. In addition, linker fluo-
tion pathways. By tuning the electrochemical environment, redox-active rination can enhance affinity and stability and may introduce anion-
metal centers and defect sites can be engineered to enhance PFAS cap- π/quadrupole interactions that stabilize anionic PFAS near aromatic
ture and facilitate subsequent catalytic transformation. A representative pore surfaces, providing a recognition-based explanation for selectivity
electrochemical synthesis strategy based on anodic metal dissolution is trends that HSAB alone cannot capture [28]. The effective coordination
illustrated in Fig. 7c [157]. strength depends critically on hydration-shell stripping, node accessi-
bility (including defect-derived coordinative unsaturation), and
4. Structural and coordination chemistry fundamentals of MOFs competition from common oxyanions (like, carbonate/bicarbonate,
relevant to PFAS affinity sulfate, phosphate), which can invert apparent affinity trends inferred
from gas-phase or idealized models [169–171]. In practice, PFAS uptake
MOFs are crystalline porous coordination networks constructed from reflects the balance between inner-sphere binding thermodynamics and
metal nodes (ions or clusters) bridged by multitopic organic linkers, and the energetic penalty of desolvation and site access, particularly for
they have rapidly evolved into one of the most versatile classes of porous short-chain PFAS [172,173].
materials in chemistry and materials science. Their emergence has In realistic waters, however, PFAS anions compete with a spectrum
transformed reticular chemistry by enabling the modular assembly of of other hard inorganic anions, including HCO3
(cid:0)
/CO3
2(cid:0)
, SO4
2(cid:0)
, NO3
(cid:0)
, Cl
(cid:0)
11

# Page 12

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 8. Coordination-chemistry principles and structural design levers that govern PFAS affinity and reactivity in MOFs. (a) General chemistry concepts (HSAB
principles, periodic trends, electronegativity, and reaction kinetics) that guide rational MOF design for PFAS interactions, Reproduced with permission [35].
Copyright 2022, American Chemical Society. (b) Linker/ligand functionalization introduces tailored interaction motifs and tunes the local chemical microenvi-
ronment around PFAS, Reproduced with permission [222]. Copyright 2022, Elsevier. (c) Metal-node selection and framework topology (e.g., MIL-101 and MIL-53
analogues) enable control of pore architecture and coordinatively unsaturated metal sites, Reproduced with permission [207]. Copyright 2021, Elsevier. (d) Defect
engineering reshapes local coordination environments and pore chemistry, modulating accessibility and binding/activation behavior for short- and long-chain PFAS,
Reproduced with permission [217]. Copyright 2024, Elsevier. (e) MOF-deep eutectic solvent (DES) composites illustrating cooperative interactions with fluorinated
PFAS molecules, Reproduced with permission [221]. Copyright 2024, Elsevier.
and, in many cases, phosphate and silicate species [174–176]. The environment and introduce additional hydrogen-bond donors or ac-
relative affinity of these co-anions for a given MOF node depends not ceptors near the coordination sphere [185–187]. Mixed-linker strategies
only on their HSAB character but also on their charge, geometry, and and defect engineering further allow the introduction of cationic or
hydration shell, as well as on the degree of coordination saturation at the zwitterionic sites in the pores, adjustment of the framework's point of
metal center [177]. Nodes with higher formal charge and accessible zero charge, and control over the fraction of coordinatively unsaturated
coordination positions (e.g., under-coordinated Zr6O4(OH)4 clusters metal centers [171,188–190]. As a result, for a given SBU, the acid-base
with missing linkers) typically show stronger binding to multidentate or character and local electrostatic potential experienced by PFAS head-
highly charged oxyanions, which can lead either to preferential PFAS groups can be finely tuned by linker chemistry, enabling MOFs that
uptake or to competitive blocking by carbonate/sulfate, depending on preferentially bind carboxylate versus sulfonate PFAS, or long- versus
solution composition and pH [36,178–181]. Conversely, nodes whose short-chain analogues, even when the inorganic node is nominally the
open sites are partially capped by terminal hydroxyls, aqua ligands, or same [30,36,191,192]. The role of linker functionalization in tailoring
modulators may display weaker but more selective binding, as the PFAS interaction environments within MOFs is illustrated in Fig. 8b.
effective acidity and steric environment at the metal center can be tuned
to favor PFAS headgroups over smaller inorganic anions [171].
Linker identity and functionalization provide an additional lever to 4.2. Framework families and coordination environments relevant to PFAS
modulate this effective Lewis acidity and the number and accessibility of binding
binding sites [182–184]. Electron-withdrawing carboxylate, sulfonate,
or fluorinated linkers tend to pull electron density away from the metal By varying the metal SBU and the linker backbone/functional
cluster, increasing the apparent hardness and acidity of the node, groups, one can systematically tune the electronic structure of the metal
whereas electron-donating substituents (-NH2, -OH) can soften the metal sites, the acidity/basicity of the pore surface, the distribution of open
metal coordination sites, and the geometry of adsorption domains
12

# Page 13

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
[193,194]. This design freedom has historically been exploited in gas coupled adsorption-photocatalytic or electrochemical degradation
storage and catalysis, but the same principles translate naturally to PFAS [215,216]. A clear structure-property example is provided by MIL-53
capture: coordinatively unsaturated metal sites offer Lewis-acidic analogues engineered for PFOS uptake, where performance is gov-
docking points for carboxylate and sulfonate headgroups; polar or erned jointly by coordinatively unsaturated metal sites and pore-
cationic linker functionalities enable electrostatic pairing and hydrogen window accessibility [207]. In this study, PFOS adsorption trends
bonding; and hydrophobic/aromatic pore walls favor packing of per- across different MOF nodes were rationalized by the density of unsatu-
fluoroalkyl tails via hydrophobic, fluorophilic, and π-CF interactions. rated metal sites (which controls adsorption polarity/affinity) together
MOFs used for PFAS remediation can broadly be grouped into four with pore dimensions matched to the ~1.1 nm PFOS molecular size;
practical families: MIL-type, UiO-type, zeolitic imidazolate frameworks accordingly, frameworks combining suitable apertures with accessible
(ZIFs), and other specialized frameworks. The MIL series, first intro- open metal sites delivered the highest uptake. Importantly, linker
duced by F´erey and co-workers [195], includes archetypes such as MIL- elongation systematically improved entry and adsorption: the larger-
101(Cr), a mesoporous chromium terephthalate with very high surface window MIL-53(Al)-BPDC outperformed shorter-linker analogues
area and hierarchical cage structure, and MIL-100(Fe), which replaces (NDC and BDC) because the framework “skeleton window” decreases in
Cr with Fe(III) tricarboxylate clusters and offers abundant accessible Fe the order BPDC > NDC > BDC, directly limiting PFOS access and
sites in large cages [196]. UiO-type MOFs, exemplified by UiO-66 and its loading. Cheng et al. [217] reported a green strategy to control MOF
functionalized derivatives, are built from robust Zr6O4(OH)4 clusters particle size and defect density using ammonium salt/glycolic acid deep
linked by dicarboxylates; they are renowned for their exceptional hy- eutectic solvents (DES). Tuning the hydrogen-bond donor/acceptor ratio
drothermal and chemical stability in water and over a wide pH range, (2:1–4:1) introduced moderate defects without compromising frame-
which is crucial for long-term operation in realistic PFAS-contaminated work stability, improving PFAS removal. AIMD simulations further
waters [197]. ZIFs, constructed from tetrahedrally coordinated metal showed that DES-modified UiO-66 exhibits enhanced Lewis acidity and
ions (typically
Zn2+
or
Co2+
) and imidazolate-based linkers, adopt higher activity compared with pristine UiO-66 (Fig. 8d).
zeolite-like topologies because the M-Im-M angle (~145◦) mimics the Si-
O-Si angle in zeolites, and they often show high thermal stability 4.4. MOF-based composites
(300–500 ◦C) as well as hydrophobic pore environments that are
favorable for sorption of organofluorines [198–202]. Beyond these ar- MOF-based composites provide an effective strategy to enhance
chetypes, a rapidly growing family of “other” frameworks incorporates PFAS adsorption by integrating MOFs with polymers, carbon materials,
diverse metals (e.g., Zn, Fe, Al, Zr, Hf, rare-earth metals, Th, Bi) and or other functional components, thereby combining the high adsorption
more complex or functionalized ligands (e.g., porphyrins, fluorinated capacity of MOFs with improved mechanical stability, mass transport,
linkers, cationic ammonium-bearing linkers, chiral or bio- and processability [204]. For instance, Zhang et al. [218]developed a
macromolecular linkers), enabling fine control over PFAS affinity and MOF/polyvinyl alcohol (PVA) bilayer membrane that achieved 98.4%
selectivity [29,198–203]. In many of these systems, reticular chemistry PFAS removal from landfill leachate while maintaining high moisture
principles are used to introduce defects (missing linkers or nodes), resistance and minimal flux loss. Adsorption of long-chain PFAS such as
modulate node connectivity, or embed guest species (for instance, metal PFOA and PFOS exceeded 90% when the solution pH approached the
nanoparticles, oxide clusters, redox-active co-catalysts) inside the zero-charge point of the AlFu MOF, highlighting the importance of
framework, thereby creating multi-functional microenvironments surface charge interactions. Similarly, Thang et al. [219]reported a UiO-
where PFAS can be concentrated, activated, and, in some cases, 66-NH2/PVA/graphene oxide composite in which UiO-66-NH2 provides
degraded [29,204–206]. The influence of metal-node selection and abundant adsorption sites through electrostatic interactions and Lewis
framework topology on pore architecture and PFAS binding environ- acid–base coordination between Zr4+ clusters and PFAS carboxylate
ments is summarized in Fig. 8c [207]. groups. The incorporation of PVA and GO enhances hydrophilicity and
structural stability, enabling a PFOA adsorption capacity of 9.9 mg/g at
4.3. Pore chemistry, hydrophobic/fluorophilic balance, and PFAS chain- pH 5 and maintaining about 80% efficiency after seven regeneration
length selectivity cycles. In addition to polymer composites, various functional materials
including acrylic acid, N-vinylimidazole, hydrolyzed polyacrylamide,
For PFAS capture, the interplay between hydrophobicity, hydro- carbon nanomaterials, Fe3O4 nanoparticles, and eutectic solvents have
philicity, and fluorophilicity within the MOF pores is central been integrated with MOFs to improve adsorption performance and
[204,208,209]. Frameworks with hydrophobic internal surfaces and material recovery (Fig. 8e) [21,204,220,221]. Such composite archi-
appropriate pore apertures can preferentially host perfluoroalkyl chains tectures introduce synergistic interaction pathways and improved sta-
…
over water, leading to strong van der Waals and F F contacts and bility, offering promising platforms for efficient PFAS capture and future
“cavity-driven” physisorption, even when direct metal-headgroup co- multifunctional remediation strategies.
ordination is weak [166,191]. Conversely, frameworks rich in open
+
metal sites or polar groups (-OH, -NH2, -N R3, -SO3H) provide strong, 5. Metal-organic frameworks for PFAS remediation
localized binding for anionic PFAS via Lewis acid-base coordination,
electrostatic pairing, and hydrogen bonding, while the surrounding pore 5.1. MOFs for the removal of long-chain PFAS (PFOA, PFOS and their
walls support tail packing [210,211]. Because PFAS comprise a broad analogues)
range of chain lengths and headgroup chemistries, MOFs with different
pore sizes, shapes, and surface chemistries can exhibit marked chain- Yang et al. systematically compared three monometallic Fe-based
length dependence and selectivity trends [194]. Long-chain PFAS typi- MOFs (Fe-BTC, MIL-100(Fe) and MIL-101(Fe)) for PFOA adsorption
cally benefit more from hydrophobic/fluorophilic interactions and are using batch experiments, response surface methodology (RSM) and
often captured at higher capacities, whereas efficient removal of short- density functional theory (DFT) calculations (Fig. 9a) [223]. Fe-BTC
and ultra-short-chain PFAS demands frameworks with stronger head- exhibited the highest Langmuir capacity (418 mg/g at pH 3.3). All Fe-
group binding and narrower pore environments that compensate for the MOFs followed Langmuir isotherms and pseudo-second-order kinetics,
shorter tails [212–214]. The same structural levers that are exploited in while RSM analysis identified pH as the dominant control parameter
gas storage and catalysis (node choice and connectivity, linker length (pH >dosage >Co). XPS and DFT results indicated that adsorption is
and functionality, defect engineering, post-synthetic modification) primarily governed by Lewis acid-base interactions at Fe centers, assis-
therefore provide a powerful toolbox for tailoring MOFs toward PFAS ted by π-CF interactions, hydrogen bonding and anion-π effects. Pore-
adsorption, preconcentration for sensing, and, in advanced systems, level modeling further revealed preferential adsorption within
13

# Page 14

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 9. (a) Comparison of PFOA uptake by MOFs and Fe-based MOFs: adsorption-capacity comparison under fixed conditions; Langmuir/Freundlich isotherm fits for
Fe-based MOFs (50–1000 mg/L PFOA, pH 3.3); pH-dependent uptake (pH 3–11); and simulated most stable PFOA binding configurations in MIL-100-Fe and MIL-
101-Fe, Reproduced with permission [223]. Copyright 2020, Elsevier. (b) Structure and PFOS removal performance of PCN-224, showing 1.9 nm orthogonal
microporous channels and jointed cubic pores built from Zr6 clusters with Brønsted acid sites (TCPP-lined walls), PFOS/PFHxS/PFBS accessibility, effects of
competing anions (Cl
(cid:0)
, SO4
2(cid:0)
) and humic acid on PFOS removal at pH 3.0 (100 mg/L PFOS; 500 mg/L sorbent), recyclability over repeated cycles, and a capacity
comparison with representative MOF sorbents, Reproduced with permission [225]. Copyright 2024, John Wiley and Sons. (c) Structures and PFOA uptake of ZIF
sorbents, showing the topology and molecular structure of ZIF-7, ZIF-8, and ZIF-L, together with PFOA sorption kinetics and pH-dependent uptake compared with
13×zeolite and activated carbon, Reproduced with permission [227]. Copyright 2016, Elsievier.
14

# Page 15

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
triangular and pentagonal windows rather than larger hexagonal aper- pseudo-second-order kinetics, but UiO-66-(F4) outperforms UiO-66,
tures. Yoon et al. upcycled red mud as an aluminum source to synthesize reaching ~467 mg/g (PFOA) and ~ 254 mg/g (PFOS) versus ~388
three mono-metal Al-MOFs, MIL-53(Al), MIL-96(Al) and MIL-100(Al), and ~ 160 mg/g for UiO-66; mechanistic tests with perfluorooctanol
via phase-controlled hydrothermal routes [224]. MIL-100(Al) exhibi- indicate that hydrophobic and fluorophilic van der Waals interactions
ted the best PFOA adsorption, with a Langmuir capacity of ~131.6 mg/ dominate over direct Zr coordination [37]. PCN-224, a water-stable Zr-
g, attributed to its higher surface area (~1189 m2/g) and abundant porphyrinic MOF with 1.9 nm channels and very high BET area (2639
hydrophilic Al-OH sites that promote interaction with the PFOA m2/g), exhibits rapid and strong sulfonate PFAS uptake, removing
carboxylate group; mechanistic analysis pointed to anion exchange be- ~77% PFOS, 71% PFHxS and 69% PFBS within 10 min at pH 3, with
tween coordinated NO3 (cid:0) and PFOA (cid:0) plus Lewis acid-base interactions at Sips capacities of 963, 517 and 395 mg/g, and maintains >93%
Al sites, linking MOF phase control directly to PFAS removal efficiency. adsorption in the presence of Cl (cid:0) /SO4 2(cid:0) and >95% PFOS removal over
Zhao et al. [207]further analyzed PFOS adsorption in the MIL family by five regeneration cycles (Fig. 9b) [225]. SCU-8, a mesoporous cationic
comparing MIL-53(Al), MIL-53(Fe), and MIL-101(Cr), and by system- Th-MOF with 2.2 nm channels and BET 1360 m2/g, rapidly exchanges
atically increasing the linker length in MIL-53(Al) using BDC, NDC, and PFOS anions, achieving ~96% removal from 1 mg/L in 2 min, a capacity
BPDC ligands. The adsorption kinetics followed a pseudo-second-order of 44.8 mg/g, robust performance under excess competing anions and
model, indicating a significant chemisorption contribution. XPS anal- polishing 1 μg/L PFOS down to 21 ng/L [226]. Sustainability-oriented
ysis of MIL-53(Al)-BPDC after PFOS uptake revealed the appearance of a Zr- and La-MOFs prepared from waste PET demonstrate that high
CF3 signal at 292.9 eV, confirming chemical attachment of PFOS on the PFAS capacity can be combined with low-footprint precursors [82].
MOF surface. Density functional theory calculations further suggested PET-derived La-MOF and Zr-MOF, with BET areas of ~76.9 and 293.5
that Fe3+ can enhance PFOS removal through cation-bridging and co- m2/g, show PFOA capacities of ~310 and ~ 290 mg/g under mildly
ordination interactions with the sulfonate headgroup, thereby acidic conditions (pH ≈ 3–3.7), with Langmuir isotherms, pseudo-
increasing adsorption affinity. second-order kinetics and <10% capacity loss over seven adsorption-
A compelling example of microenvironment engineering within a desorption cycles in both batch and fixed-bed configurations.
fixed Zr6 SBU framework is provided by fluorinated UiO-67 derivatives. Among non-Zr sorbents, functional-group-modified Ag-MOFs (MOF-
In this work, a UiO-67-F2 framework was synthesized by incorporating COOH, MOF-NH2, MOF-OH) with 1D interpenetrated structures
fluorinated dicarboxylate linkers, which generate a more hydrophobic demonstrate that linker pre-functionalization can tune PFOA uptake
and fluorophilic pore environment while preserving the original Zr6 [222]. MOF-NH2, with BET ~131 m2/g, achieves a capacity of 185.6
cluster topology. Compared with pristine UiO-67, the fluorinated mg/g at 100 mg/L PFOA, fits Langmuir and pseudo-second-order
analogue exhibited markedly higher adsorption capacities toward models, and retains >87% removal over five cycles; simulations indi-
PFOA, increasing from 872 mg/g for the parent material to 928–1700 cate that van der Waals interactions and steric confinement in the
mg/g for UiO-67-F2. This enhancement was attributed to stronger in- channels dominate. Chen et al. compared Zn-based ZIF-7, ZIF-8 and ZIF-
teractions between the perfluoroalkyl tail and the fluorinated pore L with zeolite 13×and activated carbon, showing that ZIF-8 and espe-
surface, as well as subtle shifts in local electrostatics arising from linker cially layered ZIF-L deliver much higher PFOA uptake and faster ki-
modification. The study demonstrates that altering the linker without netics, with ZIF-L reaching ~1.2 mmol/g (497 mg/g) at pH 5, attributed
changing the inorganic node can substantially tune pore acidity, hy- to favorable imidazolate chemistry and 2D lamellae that provide less
drophobicity, and the electrostatic potential experienced by PFAS confined diffusion pathways than 3D ZIF-8 (Fig. 9c) [227]. PCN-222
headgroups, thereby improving long-chain PFAS selectivity and overall (Fe), discussed above among high-capacity Zr-based sorbents, also fits
adsorption performance. This system highlights linker-level microenvi- into this bimetallic category [228]. It couples Zr6 nodes with Fe-
ronment design as a powerful strategy for advancing PFAS-selective Zr- porphyrin linkers to deliver an exceptional PFOS capacity of 2257
based MOFs [192]. Zr-based MOFs dominate the high-capacity land- mg/g under mildly acidic conditions, with very fast uptake, Langmuir
scape for long-chain PFAS adsorption. PCN-999, a monometallic Zr-MOF behavior and pseudo-second-order kinetics, and retains crystallinity and
built from Zr6 and biformate-bridged (Zr6)2 clusters with hierarchical performance between pH 2–10. The adsorption capacities and degra-
micro/mesopores and a BET surface area of ~1696 m2/g, achieves a dation performance of representative MOF systems reported for PFAS
PFOA capacity of ≈1089 mg/g, >99% removal from 1000 ppm and fast removal are summarized in Table 2, which compiles representative
pseudo-second-order kinetics, maintaining >94% capacity after 10 cy- adsorption capacities for different PFAS species across MOF systems.
cles; structural analysis shows initial chemisorption at (Zr6)2 SBUs fol-
lowed by hydrophobic tail-tail packing [200]. MOF-808, another Zr- 5.2. Neutral and zwitterionic PFAS: Coordination constraints and
MOF with high BET area (1610 m2/g), narrow ~1.5 nm pores and implications for MOF design
water stability over pH 2–11, delivers a PFOS capacity of 939 mg/g and
very rapid uptake (equilibrium ~30 min at 500 mg/L) [164]. PFOS Most MOF-based PFAS remediation studies have focused on long-
removal is nearly constant from pH 2–7 and only decreases above pH 7, chain anionic perfluoroalkyl carboxylates and sulfonates (PFOA and
consistent with electrostatic attraction between cationic PFOS), where adsorption is dominated by electrostatic attraction, anion
[Zr6O4(OH)4]12+ clusters (below pHₚzc ≈ 4) and PFOS (cid:0) , with hydro- exchange, and inner-sphere coordination between PFAS headgroups and
phobic interactions and hydrogen bonding contributing at higher pH; cationic metal nodes [30,165]. However, neutral and zwitterionic PFAS
thermodynamic data indicate a spontaneous, endothermic, mainly represent a fundamentally different coordination-chemistry challenge,
physisorptive process. Li et al. synthesized two topology-related and their limited treatment in the MOF literature constitutes an
TCPPDA-based monometallic Zr-MOFs (Zr-MOF-1 with sqc topology; important gap that must be explicitly acknowledged [36,229].
Zr-MOF-2 with scu topology) and showed that framework topology Neutral PFAS, such as fluorotelomer alcohols (FTOHs), and zwit-
strongly influences PFOA adsorption [208]. Zr-MOF-1 reaches a capac- terionic or cationic PFAS precursors, including sulfonamido- and
ity of ≈335 mg/g, nearly five times that of Zr-MOF-2, with pseudo- betaine-type surfactants widely used in aqueous film-forming foams
second-order kinetics and chemisorption-dominated uptake, and spec- (AFFF), do not consistently present a strongly anionic headgroup in
troscopy confirms that PFOA is accommodated in 1D channels and in- aqueous solution [230–232]. As a result, they evade the classical capture
teracts with Zr-OH sites through combined chemical and physical mechanisms that underpin many “high-capacity” MOFs optimized for
adsorption. PFOS and PFOA. In these systems, the absence of a persistent negative
Carboni et al. compared UiO-66 and its perfluorinated analogue UiO- charge prevents strong long-range electrostatic attraction to cationic
66-(F4) for PFOS and PFOA (“PFOX”) adsorption. Both water-stable, secondary building units (SBUs), and inner-sphere metal‑oxygen coor-
microporous Zr-MOFs show fast uptake (equilibrium ~60 min) and dination becomes weak or inaccessible due to hydration-shell
15

# Page 16

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Table 2
Comparison of representative MOFs and MOF-based composites for PFAS adsorption and degradation, including reported adsorption capacities.
MOFs BET surface Pollutant Experimental conditions Removal efficiency (%) and Refs.
area (m2/g) adsorption capacity (mg/g)
La-MOF 76.9 PFOA Conc.: 100 mg/L, Dose: 5.0 mg/100 mL, pH: 3–3.7, 310 mg/g [82]
Zr-MOF 293.5 Time: 24 h, Temp: 25 ◦C 290 mg/g
MOF-808 (Zr-based) 1610 PFOS Dose: 3 mg/40 mL; Conc.: 50–500 mg/L; Temp: 939 mg/g [164]
25 ◦C; Time: 30 min; pH 4–5
UiO-66-NH2(Zr) 1007 PFOA Dose: 500 mg/L, Conc.:1000 mg/L, Time: 5 min 99% and 1178 mg/g [191]
UiO-67-F2 1966 PFOA Conc.: 1000 mg/L, pH 3, 928 mg/g [192]
UiO-67 2126 872 mg/g
PCN-999 (Zr-based MOF) 1696 PFOA Conc.: 100–5000 ppm, Dose: 1 mg/1 mL, Room 1089 mg/g, 99% [200]
temperature, Time: 24 h
Zr-MOF-1 (sqc topology) – PFOA Conc.: 1000 mg/L; Time: 8 h; Room temperature; 335.4 mg/g [208]
Zr-MOF-2 (scu topology) – acidic to neutral pH 72.5 mg/g
MIL-53(Al) 1336.09 PFOS Conc. 20–80 mg/L; pH 7.0; Temp: 20 ◦C; Time: 1–2 66 mg/g [207]
MIL-53(Al)-NDC 1131.96 h; Shaking: 180 rpm 171 mg/g
MIL-53(Al)-BPDC 1417.04 305 mg/g
MOF-NH2 (Ag-based, 130.66 PFOA Dose: 10 mg/20 mL, Conc: 100 mg/L, 500 r/min, 2 >87%, 185.6 mg/g [222]
functionalized MOF) h, Room temperature
MIL-101(Fe)-NH2@MgCo-LDH – PFOA Dose: 0.03 g/L, Conc.: 1–260 mg/L, pH 3, time: 24 h 98% and 747.5 mg/g [260]
Fe-BTC – PFOA pH 3.3 418mg/g [223]
MIL-100-Fe – 349mg/g
MIL-101-Fe – 370mg/g
MIL-53(Al) 4.85 PFOA Dose: 0.5 g/L, Conc.: 60 mg/L, Time: 240 min, 4.90 mg/g [224]
MIL-96(Al) 185.8 Shaking: 30 rpm, room temperature 30.64 mg/g
MIL-100(Al) 1189.15 111.07 mg/g
UiO-66 (Zr-based MOF) >1000 PFOA Dose: 1 mg/1 mL; Time: 1 h; pH 4; Temp: 298 K; 388 mg/g [37]
PFOS Conc.: 1000 mg/L 160 mg/g
UiO-66-(F4) (perfluorinated Zr- 682 PFOA 467 mg/g
MOF) PFOS 254 mg/g
PCN-224 (Zr-porphyrinic MOF) 2639 PFOS pH 3.0; Dose: 500 mg/L; conc.: 50–500 mg/L; 77%, 963 mg/g [225]
PFHxS Temp: 20 ◦C; Shaking: 400 rpm; Time: 1 h 77%, 517 mg/g
PFBS 69%, 395 mg/g
SCU-8 (Th-based cationic MOF) 1360 PFOS Conc.: 1 mg/L; Dose: 200 mg/40 mL; room 96%, 44.79 mg/g [226]
temperature; Time: 2 h;
ZIF-L (Zn-based layered ZIF) 12 PFOA Dose: 8 mg/40 mL; Temp: 298 K; pH 5; Con.: 90%, 497 mg/g [227]
0.01–0.5 mmol/L; Time: 24 h
AF-CMOF (NH2-SiO2-modified 999 PFOS Conc.: 10–100 mg/L; dose: 140 mg/L; pH 3; 25 min; 89%, 689 mg/g [275]
Cu-BTC) room temperature
UiO-66-NH2@MIL-101(Cr) 1927 PFOA Conc.: 14 mg/50 mL; Time: 24 h; pH 3, Conc.: [261]
50–1400 mg/L; Room temperature (298 K) 860 mg/g
MIL-101(Cr)@ZIF-8 2091 PFOA Dose: 0.008 g/20 mL; Conc.: 50–1400 mg/L; Time: 90%, 625.5 mg/g [262]
60 min; pH =3, 298 K, Shaking: 150 rpm/min
Zr-metalloporphyrin MOF 1948 PFOS Conc.: 50–500 mg/L; Dose: 0.003 g/40 mL; Temp: 2257 mg/g [228]
25 ◦C; Time: 24 h, pH 5
MIL-177-HT (Ti-based MOF) 609 PFOA UV-irradiation; Dose: 2.5 g/L; 2.5% v/v TEOA (hole 83% [251]
scavenger); Conc.: 0.1–1.0 mg/L; Time: 24 h
reaction
MIL-125-NH2 (Ti-based MOF) 1378 PFOA UV (Hg lamp) photocatalysis; [PFOA]0 up to 1 mg/ 98.9% degradation [252]
L; 2.5 g/L MIL-125-NH2; 0.5 M glucose as sacrificial
reductant; pH ≈4.6–5.8; 24 h
NU-1000 2210 PFAS mixture in AFFF- 10 mg adsorbent +50 mL IDW, 50 mL In IDW 6: Total anionic PFAS [255]
impacted groundwater (IDW polypropylene tube, 150 rpm, room temperature; removal =58%, total non-
samples): 28 PFAS, spanning 8 for “role of structure” test using IDW 6: 30 min ionic PFAS removal =99%
classes contact time for NU-1000
UiO-66 1000 Same batch setup; for IDW 6 structure-comparison: In IDW 6: Total non-ionic
treated 48 h (sampled at 1 min, 10 min, 30 min, 24 PFAS removal =95%, total
h, 48 h) anionic PFAS removal =2%
ZIF-8 2100 Same batch setup; for IDW 6 structure-comparison: In IDW 6: low affinity for
treated 48 h (sampled at 1 min, 10 min, 30 min, 24 both anionic and non-ionic
h, 48 h) PFAS (removal <10%)
UiO-67-2CF3 2500 PFHxA Dose: 10 mg/150 mL, Conc.: 0.1–2500mg/L, 1386 mg/g [256]
Shaking: 250rpm, pH 4.94,
MIL-101(Cr) 2478 GenX MIL-101(Cr) suspension 80 mg/L; Conc.: 0–2 mg/L; 51.5 mg/g [257]
PFOS 2 mM NaH2PO4 buffer; pH 5.0 ±0.2; Shaking: 200 72.5 mg/g
PFHxA rpm; Time: 24 h 40.8 mg/g
PFOA 44.3 mg/g
6:2 FTS 38.4 mg/g
Mg MOF-74-engineered PES 111.6 PFHxA Pressure: 6 bar; near-neutral pH; room temperature ~90% [265]
TFC-NF membrane
ZIF-L/PEI TFN membrane (Co- – PFBA, Cross-flow nanofiltration; 3 bar; 20 ±0.2 ◦C; feed 35.5% [266]
ZIF-L in PA layer, M-5) PFBS, PFAS =200 μg/L; M-5 membrane with 5 wt% ZIF-L 47.9%
PFHxA, relative to PEI 81.5%
PFHxS, 87.9%
PFOA, 95.9%
PFOS, 98.5%
(continued on next page)
16

# Page 17

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Table 2 (continued)
MOFs BET surface Pollutant Experimental conditions Removal efficiency (%) and Refs.
area (m2/g) adsorption capacity (mg/g)
PFNA 100%
CuBTC@PVDF DCMD 781 PFHpA Conc.:1.18 ppm; Temp: 60 ◦C, 79.64% [267]
membrane
MIL-100(Fe))/PDA@Ti3C2Tx – PFOA Conc.: 10 ppm; pH 6.3; Pressure: 3.5 bar; room 91.4% [268]
temperature
Zirconium Terephthalate (UiO- – PFOA – 96% and 30 mg/g [258]
66) Gel
ChG-MOF (10%) hybrid 22.95 PFOA pH 6.8; Dose: 5 mg/10 mL; Conc.: 50–500 ppm; 495.8 mg/g [259]
cryogel (fungal chitin +10 wt room temperature; Time: 30 min ~ 95%
% MOF-808, Zr-based) PFDA 689.5 mg/g, ~86%
PNBS 271.3 mg/g
PFOS 354.7 mg/g
​ ​ ​ ​ ​ ​
PVA@UiO-66-NH2/GO (Zr- 1113 PFOA pH 5; Room temperature; Time: 80 min, Shaking: 98–99%, 9.9 mg/g [219]
MOF/polymer/GO 120 rpm, Dose: 2 mg/10 mL
composite)
CNF-Cu/C-800 membrane – PFOA Solar photo-electro-Fenton (SPEF) system; CNF-Cu/ ~98% [270]
(HKUST-1/PAN-derived C-800 as cathodic membrane; 180 min treatment;
MOF-based Cu/C) generation of .OH and h vb+via Cu(I)/Cu(II) redox
and H2O2 activation
MOF-derived In2O3 43.8–52.9 PFOA UV254 photocatalysis; MOF-derived In2O3 in 30% PFOA removed by [271]
nanospheres/rods aqueous suspension; partial adsorption in dark adsorption in dark; ~100%
followed by irradiation for 3–8 h PFOA degradation within 3
h
F-TiO2@MIL-125 (Ti-based 85.3 PFOA UV photocatalytic system with simultaneous 76.7 mg/g [273]
MOF/photocatalyst adsorption; 2.5 g/L catalyst, 2.5% v/v TEOA (hole
composite) scavenger), [PFOA]0 =0.1–1.0 mg/L; equilibrium
adsorption reached in ≈200 s
NU-1000 1567 PFOA – 90% [276]
In(tcpp) (In-based luminescent 535 PFOA Dose: 55 mg/10 mL, Time: 30 min 90%, 980 mg/g [277]
MOF)
MOF-76(Tb:Eu =29:1) 27 PFOA Dose: 0.12 g/20 mL; Time: 1 h; 400 mg/L – [278]
(bimetallic lanthanide MOF)
stabilization and charge delocalization [233,234]. This limitation ex- binding even in the absence of a formal charge [28,204,241–243].
plains why MOFs that perform exceptionally well for anionic PFAS can Recent studies provide early but important evidence that MOFs can
underperform for neutral or zwitterionic species, despite high surface engage neutral PFAS through such non-electrostatic mechanisms. In
area or abundant open metal sites [229,235,236]. For example, Zr-based particular, Zr-based MOF platforms have been shown to capture fluo-
MOFs such as MOF-808 and UiO-type frameworks achieve high PFOS rotelomer alcohols via multiple hydrogen-bonding interactions with
and PFOA capacities primarily through electrostatic interactions and node-bound hydroxyl or aqua ligands, combined with steric confine-
coordination of carboxylate or sulfonate groups to hard Zr(IV) nodes, ment within polar pore environments, rather than classical ion ex-
often supplemented by hydrogen bonding and hydrophobic tail packing change. These results demonstrate that neutral PFAS uptake by MOFs
[30,164,200,237]. By contrast, when PFAS molecules are neutral or relies on pore-level chemical patterning and directional intermolecular
internally charge-balanced, adsorption is controlled mainly by short- interactions, rather than node charge alone (Fig. 10a) [239]. Although
range host-guest interactions inside the pores. Three local effects still limited in number, such studies highlight the need to move beyond
become especially important: (i) hydrogen bonding between PFAS anion-centric design strategies when targeting PFAS precursors and
functional groups and -OH/-OH2 groups on the nodes or polar linker transformation products. Zwitterionic PFAS pose an additional chal-
sites, (ii) pore confinement and size matching that physically stabilizes lenge because their internal charge compensation reduces effective
the guest within the framework, and (iii) partitioning of the fluorinated interaction with both cationic and anionic adsorption sites. Reviews
chain into hydrophobic or fluorophilic pore regions that accommodate focused specifically on cationic and zwitterionic PFAS have emphasized
the tail. Therefore, for neutral and zwitterionic PFAS, performance de- that adsorbent performance correlates more strongly with hydrophobic
pends more on the pore microenvironment (pore size, polarity, and interactions and specific functional-group matching than with surface
functional groups) than on node charge density or anion-exchange charge density, and that materials optimized for anionic PFAS
strength, which explains why many MOFs optimized for PFOS/PFOA frequently show diminished selectivity in these cases [229]. For MOFs,
show weaker uptake for these species [83,161,238,239]. To overcome this implies that simply increasing node acidity or defect density is
these limitations, MOF design for neutral and zwitterionic PFAS must insufficient. Instead, effective capture of zwitterionic PFAS likely re-
shift from charge-driven adsorption toward host-guest recognition quires engineered microenvironments that combine weak electrostatic
enforced by confinement and cooperative weak interactions [166,240]. guidance with confinement, hydrogen bonding networks, and fluo-
Rather than relying on strong metal-ligand coordination, effective cap- rophilic pore surfaces capable of stabilizing these species against
ture requires pore microenvironments that can collectively compensate desorption [229,238].
for hydration and low polarity. Design strategies include introducing Recent advances suggest that postsynthetic modification and hybrid
directional hydrogen-bond donors and acceptors, tailoring pore size and architectures can be particularly effective for neutral and zwitterionic
topology to promote shape-selective confinement, and incorporating PFAS, because they enable functional groups that are difficult to
fluorophilic or low-polarity domains that enhance partitioning of fluo- incorporate during solvothermal synthesis to be positioned deliberately
rinated segments through noncovalent interactions. Importantly, fluo- within the pore microenvironment and at accessible interfaces
rinated or mixed-functionality linkers can create amphiphilic pores that [244–246]. Such strategies broaden the design space beyond node
stabilize both polar headgroups and perfluorinated tails, enabling acidity or defect density alone, enabling cooperative non-covalent
17

# Page 18

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 10. (a) Filter-chip-SPE-MS platform for high-throughput PFAS screening and metabolism monitoring, integrating parallel cell-culture channels with a Zr-MOF
filter (BUT-16), automated probing, and SPE-MS; the system is demonstrated by dynamic tracking of FTOH biotransformation in a CYP/P450-reductase pathway
(NADPH-driven), while quantifying BUT-16 adsorption under static and fluidic conditions via MS/MS residual FTOH and kinetic uptake curves for 6:2, 8:2, and 10:2
FTOH (500 mg/L), Reproduced with permission [239]. Copyright 2023, Royal Society of Chemistry. (b) Comparison of TFHFESE degradation in DI water and river
water under UV photolysis (3 mW/cm2), solar photolysis (0.55 mW/cm2), and ozonation (138 mg/L), together with the proposed TFHFESE degradation pathway
during advanced oxidation processes, Reproduced with permission [253]. Copyright 2021, Elsevier. (c) PFAS-MOF extraction and elution workflow and matrix
performance: PFAS classes evaluated (PFCAs, PFSAs, sulfonamides, n:2 FTS, and long-chain PFAS), comparative heatmap-style summary of PFAS adsorption from
water and methanol-based elution across MOFs (circle size reflects recovered fraction with reported confidence intervals), and multiplexed LC-MS/MS quantification
of 50 PFAS in six water matrices using UiO-66, with concentrations reported in ng/L and qualifiers for <LOD and <LOQ, Reproduced with permission [235].
Copyright 2025, Elsevier.
recognition (e.g., hydrogen-bond networks and fluorophilic micro- ozonation, O3/H2O2, and solar (±H2O2) conditions, including tests in
domains) under confinement. Collectively, these considerations rein- river water. UV-based systems achieved near-complete TFHFESE
force that neutral and zwitterionic PFAS require MOFs engineered for degradation (≈98.7–100%), and adding H2O2 increased defluorination
molecular recognition under confinement, rather than direct extrapo- during UV treatment, whereas ozonation produced comparatively
lation from anionic PFAS adsorption paradigms [28,204,242,247]. higher defluorination but was more sensitive to matrix effects. Radical-
These considerations also clarify why many degradation studies scavenger experiments further indicated that TFHFESE oxidation during
involving MOFs read as “MOF-assisted photocatalysis” rather than ozonation was driven mainly by direct reaction with molecular ozone
coordination-enabled C–F activation. In numerous reports, MOFs pri- rather than .OH, while UV-based removal was consistent with .OH-
marily function as high-surface-area adsorbents or light-harvesting mediated pathways. Collectively, these results reinforce that for neutral
scaffolds, while PFAS degradation proceeds via solution-phase reactive telomer-type PFAS, destruction is often governed by solution-phase
oxygen species. For neutral and zwitterionic PFAS in particular, the oxidants and water-matrix competition, so adsorption and degradation
absence of strong binding at metal nodes reduces residence time at are not inherently coupled unless the material design can first enforce
catalytically relevant sites, limiting opportunities for inner-sphere strong host-guest retention at catalytically relevant sites [253]. A
electron transfer or bond polarization required for selective C–F comparative example of neutral PFAS precursor degradation in DI water
cleavage. As a result, adsorption and degradation are often weakly versus river water under UV/solar photolysis and ozonation, together
coupled [2,194,248–252]. These findings underscore a fundamental but with the proposed transformation pathway, is shown in Fig. 10b [253].
underexplored distinction in PFAS remediation: anionic PFAS can often A complementary strategy to address neutral and precursor PFAS has
be addressed through classical coordination and ion-exchange chemis- recently been demonstrated using discrete coordination assemblies
try, whereas neutral and zwitterionic PFAS require MOFs designed for rather than extended MOF networks. Camdzic et al. [254] reported a
host-guest recognition rather than charge-driven capture. Explicit self-assembling, fluorinated zirconium-based metal-organic cage (F-
recognition of this distinction is essential for interpreting apparent dis- ZrMOC) capable of rapidly capturing a broad spectrum of PFAS,
crepancies in MOF performance and for guiding the rational design of including fluorotelomer alcohols, ethoxylates, sulfonamides, and other
materials capable of addressing the full chemical diversity of PFAS neutral or weakly charged species. The cage achieved an average
encountered in real water systems. removal efficiency of ~82% across 37–40 PFAS within 30 s, with
A useful reminder of how differently neutral PFAS precursors behave particularly strong performance for C7+ PFAS, and maintained high
comes from advanced-oxidation work on the telomer alcohol TFHFESE, capture efficiencies in complex matrices such as groundwater and
where degradation was evaluated under UV photolysis, UV/H2O2, wastewater. Spectroscopic and diffusion-ordered NMR analyses
18

# Page 19

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 10. (continued).
indicated that PFAS binding occurs predominantly through non- chain and structurally diverse PFAS can be achieved not only in
covalent hydrophobic and fluorophilic interactions at the cage exte- extended MOFs but also in discrete coordination cages and bio-derived
rior, rather than through classical inner-sphere metal coordination or frameworks. Camdzic et al. reported a self-assembling fluorinated zir-
full pore encapsulation. Importantly, the discrete, solution-processable conium metal-organic cage (F-ZrMOC) that rapidly captures a broad
nature of the metal-organic cage bypasses diffusion and pore- PFAS panel (37 species). At 400 ng/mL per PFAS, it achieved an average
accessibility limitations commonly encountered in extended MOF removal of ~82% in water within 30 s across carboxylates, sulfonates,
solids, highlighting how coordination-driven self-assembly can be sulfonamides, ethoxylates, and fluorotelomer-derived PFAS, and main-
exploited to recognize neutral and zwitterionic PFAS via host-guest in- tained performance in wastewater and groundwater. Although removal
teractions rather than electrostatics. A MOF-enabled PFAS extraction- was higher for ≥C7, the work highlights fluorophilic, non-framework
elution workflow and matrix-resilient LC-MS/MS quantification across coordination architectures as fast, SPE-compatible sorbents with
multiple PFAS classes are illustrated in Fig. 10c [235]. solvent-triggered methanol regeneration (Fig. 11a) [254]. Com-
plementing this, Grancha et al. demonstrated a robust, water-stable, L-
5.3. MOFs for short-chain and emerging PFAS histidine-derived Cu(II) MOF (Cu2(S,S)-hismox.5H2O) with mixed hy-
drophobic/hydrophilic channels that delivers excellent removal for
Recent work also shows that high-performance capture of short- long-chain PFAS (80–100%) while also achieving unusually strong
19

# Page 20

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 11. Representative MOF-enabled PFAS separation and destruction strategies across materials and matrices: (a) fluorinated Zr metal-organic cage (F-ZrMOC)
synthesis and chain-length-dependent PFAS capture in wastewater/groundwater versus Nanopure-water control, Reproduced with permission [254]. Copyright
2023, American Chemical Society. (b) open-framework Cu-MOF (MOF 1) structure (channels and dinuclear nodes) and time-resolved PFAS removal (5 min-30 h),
Reproduced with permission [214]. Copyright 2025, John Wiley and Sons. (c) PFAS speciation (anionic vs non-ionic) and compound-resolved removal from impacted
water (IDW 6) comparing NU-1000 (30 min) with UiO-66, ZIF-8, granular activated carbon, and control (48 h), Reproduced with permission [255]. Copyright 2021,
American Chemical Society.
short-chain capture (70% PFBA and 86% PFBS) under continuous-flow length trends,” and that MOF chemistry can enable rapid uptake of non-
solid-phase extraction with contact times <30 s; single-crystal struc- ionic PFAS that conventional adsorbents often miss. These groundwater
tures (PFBA@1 and PFOS@1) further support a confinement-driven results motivate a structure-guided view of short-chain and emerging
host-guest recognition mode relevant to “elusive” C4-C6 PFAS PFAS capture, where pore/defect accessibility and interfacial chemistry
(Fig. 11b) [214]. must be tuned to retain weakly hydrophobic C4-C6 species while still
Short-chain and emerging PFAS are more difficult targets and require accommodating bulky precursors, as illustrated by the following UiO-67
tailored microenvironments. A useful benchmark for real-matrix short- functionalization study. A defective UiO-67-based Zr-MOF series dem-
chain and precursor PFAS capture is the systematic groundwater study onstrates this clearly: using glycine hydrochloride as a dual-pKa
by Li et al. [255], which compared NU-1000, UiO-66, and ZIF-8 against modulator and fluorinated BPDC-2CF3 linkers, UiO-67-2CF3 combines
commercial GAC using AFFF-impacted groundwater and multiple PFAS a positively charged, defect-rich Zr6 cluster surface with fluorophilic
classes (Fig. 11c). NU-1000 showed the strongest overall performance, -CF3 groups and hierarchical pores (0.89/1.14 nm), achieving a PFHxA
achieving ~58% removal for anionic PFAS and ~ 99% removal for non- capacity of ~1386 mg/g, equilibrium within 4 min, high selectivity in
ionic PFAS (notably FOSA), with adsorption reaching equilibrium the presence of competing anions and natural organic matter, and col-
within ~1 min, whereas UiO-66 removed only ~2% of anionic PFAS but umn performance that reduces 1 μg/L PFHxA to <10 ng/L. Mechanistic
still ~95% of non-ionic PFAS; ZIF-8 performed poorly (<10% for both), and DFT analysis points to synergistic electrostatic attraction, Lewis
and GAC removed ~37% anionic and ~ 44% non-ionic PFAS under the acid-base coordination at unsaturated Zr sites, F … F and CF3-π in-
same conditions. Collectively, these results highlight that water-matrix teractions, anion-π interactions and hydrogen bonding [256]. A sys-
complexity and PFAS charge state can dominate apparent “chain- tematic structure-adsorption analysis on MIL-101(Cr) showed that
20

# Page 21

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
short-chain and sulfonate PFAS can exhibit higher uptake (on a μmol/g (PFDA), 271.3 mg/g (PNBS) and 354.7 mg/g (PFOS), with strong pref-
basis) than longer-chain and/or carboxylate analogues, and that erence for carboxylates and good performance in PFAS-spiked lake
branching and ether functionalities can further increase adsorption po- water. Life-cycle analysis shows that adding only 10 wt% MOF-808
tential (GenX), whereas partial replacement of -CF2- with -CH2- de- boosts the performance-sustainability indicator by 426% relative to
creases uptake (e.g., 6:2 fluorotelomer sulfonate). Adsorption was neat MOF-808 (Fig. 12b) [259]. PVA@UiO-66-NH2/GO composites
attributed to a combination of electrostatic interaction, inner-sphere combine Zr-MOF particles with a PVA/graphene oxide matrix (BET
complexation at Cr coordinatively unsaturated sites, hydrogen ~1113 m2/g) and reach ~98–99% PFOA removal at pH ≈5 within ~80
bonding, and specific π-type interactions (π-CF and π-anion), with steric/ min, with a Langmuir capacity of ~9.9 mg/g in the low concentration
diffusion effects also contributing to chain-length trends. The authors regime, pseudo-second-order/Elovich kinetics and ≥ 90% efficiency
further proposed an ‘average moiety electronegativity’ descriptor (Me), after several cycles; electrostatic attraction between a positively charged
(cid:0)
which correlated strongly with adsorption capacity and was also surface and PFOA plus hydrophobic interactions with GO dominate
consistent with removal trends in contaminated groundwater, offering a uptake [219]. A MIL-101(Fe)-NH2@MgCo-LDH hybrid shows that
practical way to anticipate PFAS-MOF affinity across diverse structures coupling Fe-MOFs with layered double hydroxides can strongly boost
[257]. PFAS uptake [260]. Incorporation of only ~5 wt% MgCo-LDH into MIL-
101(Fe)-NH2 generates a more mesoporous, higher-area composite with
5.4. Gels, foams, monoliths, membranes and composites for PFAS capture a PFOA capacity of ~748 mg/g and > 95% removal of PFOA, PFOS,
PFHxS and PFBS within a few hours, driven by synergistic Lewis acid-
Beyond powders, several studies demonstrate processable MOF ar- base interactions at Fe/Mg/Co sites, electrostatic attraction below
chitectures, including gels, cryogels, membranes, and hybrid compos- pHpzc, and hydrophobic/fluorophilic partitioning in mesopores; the
ites, which offer improved mechanical stability, easier separation, and hybrid is regenerable and reaches sub-ng/L PFAS in real water. Bime-
compatibility with continuous water-treatment systems. A mono- tallic MOF-on-MOF architectures combine complementary pore envi-
metallic Zr-MOF gel based on UiO-66 acts as an efficient, robust PFOA ronments and metal sites to boost PFOA capture. Lin et al. designed a
sorbent (Fig. 12a) [258]. The nanocrystalline, hierarchically porous gel MOF-on-MOF composite where a Cr-based mesoporous MIL-101 core is
reaches ~96% PFOA harvesting efficiency (~30 mg/g uptake) in batch coated with an amino-functionalized UiO-66-NH2 shell [261]. The
and maintains ≳93–95% efficiency in gravity-driven filtration without optimized material (6-(U-on-M)) achieves an exceptionally high surface
loss of crystallinity; spectroscopy and microscopy indicate that PFOA is area (~1927 m2/g), a Langmuir capacity of ~851–860 mg/g at pH ≈3
chemisorbed via coordination of the carboxylate group to Zr-oxo clus- and rapid pseudo-second-order kinetics. DFT, FT-IR, XPS and ζ-potential
ters and is homogeneously distributed in the gel matrix. Fungal chitin analyses indicate dominant
Cr3+ /Zr4+
-carboxylate coordination, sup-
nanofibril/Zr-MOF-808 cryogels (ChG-MOF-808) preserve an inter- ported by -NH3 + /-COO (cid:0) electrostatics, hydrogen bonding and CF2-π
connected macroporous network with micro/mesopores, providing fast hydrophobic interactions. The composite maintains >85% capacity after
kinetics and high capacities for both carboxylate- and sulfonate- five cycles and remains stable from pH 2–12 and at 100 ◦C. In a related
terminated PFAS at pH 6.8: qₘ ≈ 495.8 mg/g (PFOA), 689.5 mg/g study, Lin et al. developed another bimetallic core-shell composite, MIL-
Fig. 12. Hybrid sorbent design, and electrochemical detection/degradation of PFAS: (a) ^19F NMR analysis of PFOA before and after contact with UiO-66 (tripli-
cates), with peak assignments to terminal C–F groups and harvesting efficiency quantified from the (cid:0) 80.75 ppm signal, Reproduced with permission [258].
Copyright 2025, John Wiley and Sons. (b) design and performance of MOF-fungal nanochitin (ChNF) hybrid cryogels, including EDX mapping after PFAS uptake,
selective removal across PFAS classes, real-water performance, and regeneration/cycling for PFOA and PFOS, Reproduced with permission [259]. Copyright 2025,
Elsevier. (c) morphology and functionality of CNF-Cu/C composites, coupled with the proposed PFOA degradation mechanism in an SPEF system and colorimetric/
UV–Vis detection showing concentration-dependent response and selectivity against interferents, Reproduced with permission [270]. Copyright 2025, Elsevier.
21

# Page 22

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 12. (continued).
101(Cr)@ZIF-8 (CZDM-3), that synergistically enhances PFOA adsorp- removes ~92% HFPO-TA in 180 min, with significant defluorination,
tion [262]. CZDM-3 retains an octahedral MIL-101(Cr) core and aided by a built-in electric field that improves charge separation and
dodecahedral ZIF-8 shell, with a high surface area of about 2092 m2/g strong surface adsorption that correlates with degradation rates [263].
and combined micro-mesoporosity (~1.16 and ~ 3.4 nm). It follows Membrane-integrated MOF systems represent another promising
Langmuir and pseudo-second-order models, reaches a maximum ca- processable format for PFAS removal. Ag-MOF-based TFN nanofiltration
pacity of ~626 mg/g and attains equilibrium in roughly 60 min, clearly membranes with different integration strategies (ultrasonically inter-
outperforming MIL-101(Cr) (272 mg/g) and ZIF-8 (220 mg/g). layered, ultrasonically surface-grafted, dip-coated) show that Ag-MOF
Adsorption is spontaneous and endothermic, driven by electrostatic addition increases hydrophilicity, carboxylic group density and water
attraction, π-CF contacts, hydrogen bonding and Lewis's acid-base in- permeance while tuning MWCO; the dip-coated DS-MOF membrane
teractions at Cr/Zn sites, with >80% PFOA removal retained after five balances flux and selectivity, achieving ~93.4% PFOA rejection at 1
cycles. mg/L (pH 7), strong antifouling (FRR ≥96%) and controlled Ag + release
Hybrid heterostructures combining MOFs with semiconducting ox- below WHO limits [264]. Membrane-based strategies also target shorter
ides have also been explored to couple PFAS adsorption with photo- chains. Mg-MOF-74 embedded into PES ultrafiltration substrates and
catalytic degradation. In-MOF/BiOF heterojunctions provide a converted into a TFC-NF membrane yields ~90% PFHxA removal and ~
photocatalytic route for legacy and emerging PFAS, including HFPO-TA 98% As(V) removal from simulated groundwater, with >98% flux re-
and 6:2 Cl-PFESA. The optimal 20% In-MOF/BiOF composite has higher covery over multiple fouling cycles thanks to higher hydrophilicity,
surface area and mesoporosity than pure BiOF, enabling stronger PFAS increased negative surface charge and a thinner polyamide layer [265].
adsorption and faster kinetics; under 500 W Hg-lamp irradiation, it ZIF-L/PEI thin-film nanocomposite nanofiltration membranes on poly-
completely degrades PFOA, PFOS and 6:2 Cl-PFESA in 90–150 min and sulfone supports deliver high rejections for long-chain PFAS and
22

# Page 23

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
maintain >80% removal for PFHxA and PFHxS over a range of water ~83% PFOA removal and ~ 32% defluorination in 24 h under UV with
matrices, with enhanced water permeance (~47.56 L/m2/h/bar) and TEOA as a hole scavenger; radical quenching experiments identify hy-
good antifouling in the presence of humic acid [266]. CuBTC@PVDF drated electrons as the main reactive species and highlight the impor-
flat-sheet membranes optimized for DCMD reach ~79.6% PFHpA tance of ligand hydrophobicity, framework dimensionality and band gap
rejection at 60 ◦C feed temperature with ~13.26 L/m2/h flux, illus- over simple surface area (Fig. 13b) [251]. F-TiO2@MIL-125 composites
…
trating that MOF-loaded hydrophobic membranes can address further couple enriched adsorption (via F F interactions at surface-
intermediate-chain PFAS such as PFHpA [267]. Mixed-matrix DMMIL/ fluorinated sites) with photocatalytic PFOA degradation, increasing
CA nanofiltration membranes that incorporate MIL-100(Fe) grown on Langmuir capacity from 20.2 to ~76.7 mg/g and enabling rapid uptake
PDA-modified Ti3C2Tx (PDA@Ti3C2Tx/MOF(Fe)) achieve 91.4% PFOA and self-cleaning cycles (Fig. 13c) [273]. In-MOF/BiOF heterojunctions
rejection from 10 ppm at pH 6.3 and show significant rejection of PFHpA and MOF-derived In2O3 catalysts also provide efficient photocatalytic
and PFHxA in mixed PFAS systems and real hospital wastewater [268]. routes for legacy and emerging PFAS with significant defluorination
MOF-derived materials further extend this concept to oxide and [263,271]. These studies show that adsorption-driven concentration
carbon architectures capable of adsorption, sensing, and catalytic within MOF pores can be coupled to reductive or oxidative pathways
degradation. A heat-treated Fe-MOF derivative (H:MIL-101(Fe)) was (eaq (cid:0) , .OH, h + ) to approach mineralization rather than mere seques-
reported to remove PFOA within 5 min, regenerate in ~30 s, and retain tration. Beyond adsorption-assisted photocatalysis, rare-earth coordi-
performance over 4 cycles, attributed to a hydrophobic carbon/oxide nation chemistry also points to a more direct route toward C–F bond
interface formed during partial carbonization. With CTAB to form more activation. Sheybani et al. [274]showed that
Ho3+
and
Gd3+
can extract
hydrophobic complexes, it reportedly co-adsorbed C4-C8 PFAS from fluoride from organofluorine substrates to generate fluoro-bridged RE
surface water within 10 min (pH 7), highlighting hydrophobic- clusters, and notably reported that these ions can remove fluorine from
interaction-driven broad-spectrum capture [269]. A CNF-Cu/C mem- PFHxA and PFOA, yielding new μ 3-F-bridged RE-MOFs assembled from
brane derived from HKUST-1/PAN incorporates Cu(0)/Cu(I)/Cu(II) nonanuclear and trinuclear RE clusters with BTB linkers. This study is
species in a conductive carbon nanofiber network and functions as a important for PFAS remediation because it reframes PFAS not only as
dual platform for PFOA management: it provides peroxidase-like ac- targets for capture, but also as potential fluoride sources under strongly
tivity for colorimetric sensing (LOD 0.133 μM) and, in solar photo- Lewis-acidic RE coordination environments, highlighting a
electro-Fenton mode, achieves ~98% PFOA removal in 180 min with coordination-enabled direction that conceptually bridges sequestration
~86.6% TOC and ~ 63.2% defluorination, sustained by a Cu(I)/Cu(II) and defluorination. Representative MOFs and MOF-based composites
redox cycle (Fig. 12c) [270]. MOF-derived hydrophilic In2O3 nano- reported for PFAS adsorption and degradation are summarized in
spheres and rods, obtained by calcining In-BDC coordinative polymers, Table 2.
exhibit higher surface areas (~43.8–52.9 m2/g), mesoporosity and
super-hydrophilicity than commercial In2O3, enabling ~30% PFOA 5.6. MOF-based sensing of PFAS
adsorption in the dark and complete decomposition within 3 h under
254 nm UV, with 75–80% TOC removal and higher F (cid:0) release after 6–8 h MOF-based PFAS sensing is part of a wider push toward adsorption-
[271]. assisted detection concepts that simplify sample handling and enable
The studies discussed in Sections 5.1–5.4 indicate that PFAS more portable readouts. Rather than replacing LC-MS/MS, these plat-
adsorption in MOF-based systems arises from a combination of elec- forms aim to preconcentrate PFAS at engineered interfaces and translate
trostatic interactions between anionic PFAS headgroups and positively binding into optical or electrical signals with minimal instrumentation.
polarized metal nodes, Lewis acid–base coordination at open metal sites, MOFs are well positioned for this role because their pore microenvi-
hydrophobic and fluorophilic interactions with the perfluoroalkyl chain, ronments and coordination chemistry can be tuned to strengthen fluo-
and pore confinement effects. Defect engineering, linker functionaliza- rophilic, electrostatic, and hydrogen-bonding interactions, while their
tion, and composite architectures further enhance these interactions by processability supports integration into practical formats (e.g., SPME
introducing additional active sites and improving mass transport. These coatings, microfluidic impedance chips, paper-based fluorescence as-
mechanistic insights provide a framework for rational design of next- says, and electrode modifiers). A growing direction is hybrid or multi-
generation MOF materials for efficient PFAS capture and removal. modal sensor design, where a selective recognition layer (MOF and/or
imprinting chemistry) is coupled to an amplification/transduction
5.5. MOF-based Photocatalysis and advanced oxidation for PFAS element to improve specificity in complex matrices and reduce false
destruction positives.
Jia et al. [279]designed a dual-functionalized MIL-101(Cr) sorbent
Several systems integrate PFAS concentration with catalytic for selective PFAS enrichment in solid-phase microextraction (SPME)
destruction. PCN-1003, a robust pyrazolate MOF with 1D open channels, via sequential amination (DETA) and perfluoroalkyl functionalization,
combines high PFOA adsorption (~642 mg/g) with low-temperature producing a hydrophobic, multi-interaction surface that combines
degradation, remaining stable from pH 1–12 and operating via a electrostatic attraction, hydrophobic and F–F fluorophilic interactions,
dominant PFOA-acetate anion-exchange mechanism [272]. Once hydrogen bonding, and Lewis acid-base interactions involving Cr sites
concentrated, PFOA decomposes at 90 ◦C with roughly threefold cata- (with possible π-CF contributions). The resulting MIL-101-DETA-F SPME
lytic acceleration compared with solution-phase degradation, illus- probe delivered enrichment factors of ~70–112 for nine PFAS (PFBA,
trating an integrated “capture-and-destroy” strategy [272]. Ti-based PFHxA, PFOA, PFDA, PFDoA, PFBS, PFHxS, PFOS, PFOPA) and enabled
photocatalytic MOFs and MOF-derived systems enable UV-driven PFOA UHPLC-MS/MS quantification with LODs of 0.004–0.12 ng/L (linear
degradation. MIL-125-NH2 achieves ≈98.9% degradation with ~66.7% range 0.5–1500 ng/L; RSD <11.6%), with recoveries of 76.2–108.6% in
defluorination within 24 h under Hg-lamp irradiation in the presence of complex waters (tap, river, municipal, dyeing, and mining wastewater)
glucose as a sacrificial reductant, following pseudo-first-order kinetics (Fig. 14a). Beyond preconcentration, MOF-enabled sensing can be in-
and generating both hydrated electrons and hydroxyl radicals; LC-MS tegrated directly into electronic readout platforms. Cheng et al. [280]
and DFT identify PFOA-1e as a key intermediate, reveal that H/F ex- embedded mesoporous Cr-MIL-101 inside a microfluidic channel sand-
change at the α-C-F is thermodynamically favored, and show that •OH- wiched between interdigitated microelectrodes, where PFOS binding
assisted steps are essential for chain-shortening, while the framework produced a proportional impedance increase. Spectroscopic evidence
retains crystallinity and significant porosity (BET from 1378 to 1098 supported strong host-guest interactions involving both the fluorinated
m2/g) over several cycles (Fig. 13a) [252]. MIL-177-HT, another Ti-MOF tail and sulfonate headgroup, and the flow-through architecture enabled
with 1D Ti-oxo chains (BET ~609 m2/g, band gap ~3.4 eV), delivers ultrasensitive PFOS quantification down to 0.5 ng/L, approaching state-
23

# Page 24

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 13. (a) MIL-125-NH2 enables glucose-assisted PFOA degradation with time-resolved decay and defluorination, supported by an eaq (cid:0) /.OH-coupled chain-
shortening and H/F-exchange pathway with proposed intermediates, Reproduced with permission [252]. Copyright 2022, American Chemical Society. (b) MIL-
177-HT shows light-driven PFOA removal with TEOA, tracking concentration decay and overall defluorination over 24 h, Reproduced with permission [251].
Copyright 2025, Elsevier. (c) comparative PFOA adsorption and photocatalytic decomposition kinetics for MIL-125, F-MIL-125, TiO2@MIL-125, and F-TiO2@MIL-
125, with a schematic of the proposed PFOA removal process in F-TiO2@MIL-125, Reproduced with permission [273]. Copyright 2025, Elsevier.
24

# Page 25

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 14. (a) synthesis of MIL-101-DETA-F and construction of an SPME probe, with spiked recoveries/RSDs across five real waters and the concentrations/distri-
butions of nine PFAS detected, Reproduced with permission [279]. Copyright 2021, American Chemical Society. (b) Schematic of PFOS detection and TEM/EDS of
Cr-MIL-101 before and after PFOS exposure, showing preserved crystallinity and colocalized Cr–F signals that confirm PFOS capture, Reproduced with permission
[280]. Copyright 2020, American Chemical Society. (c) Schematic of Eu/Tb-MOF@MIPs preparation and the smartphone-assisted portable sensing platform for
visual PFOA detection, Reproduced with permission [281]. Copyright 2024, Elsevier. (d) In(tcpp) structure and switchable luminescence sensing (turn-off for PFOA,
(cid:0)
turn-on for F ), including concentration-dependent responses, photographs, and a 5 min response time, Reproduced with permission [277]. Copyright 2021, Royal
Society of Chemistry. (e) Dual-lanthanide MOF-76 (Tb/Eu) design for ratiometric monitoring of PFOA photocatalytic degradation, showing emission changes to
PFOA and F (cid:0) and the corresponding ΔI549/I619 readout, Reproduced with permission [278]. Copyright 2024, Elsevier.
of-the-art laboratory limits while remaining compatible with field limit of 0.98 nM by fluorescence and 3.26 nM by smartphone-based RGB
deployment (Fig. 14b). analysis using a portable reader. This approach illustrates translation of
Optical formats further support portable PFAS screening. A device- MOF-driven molecular recognition into field-deployable PFAS moni-
integrated strategy combined lanthanide MOFs with surface molecu- toring with simple optical readout and high selectivity (Fig. 14c) [281].
larly imprinted polymers to enable selective, ratiometric fluorescence Fluorescence “turn-on” MOF sensors can also reduce false positives
sensing of PFOA. In this platform, Eu/Tb-MOF@MIPs provide stable compared with turn-off formats. A water-stable perylene-diimide (PDI)-
multi-emission signals together with selective recognition cavities, based Zr-MOF (U-1) was reported for discriminative, rapid turn-on
allowing PFOA quantification in real water samples with a detection detection of PFOA (minimal response to PFOS), achieving an LOD of
25

# Page 26

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 14. (continued).
1.68 μM in dispersion (IUPAC 3σ) [282]. Coupling the MOF with paper- compatible with quick on-site screening. Electrochemical transduction
based solid-phase extraction (SPE) concentrated PFOA and lowered the can also be achieved using MOF electrode modifiers. Tian et al. [283]
LOD to 3.1 nM, highlighting a low-cost, point-of-sampling format developed a fluorine-functionalized cerium UiO-66 (Ce-UiO-66-F)
26

# Page 27

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
coated glassy carbon electrode, where PFOA adsorption in MOF cavities template, creating selective binding cavities that preconcentrate PFOA
blocks interfacial active sites and suppresses the redox-probe current. By at the electrode interface. The resulting MIP-Co/Fe@CNF enabled
fitting the probe-signal decrease with Langmuir and Freundlich- electrochemical PFOA detection with a linear range of 1 × 10 (cid:0) 8-9 ×
Langmuir models, the platform achieved a 0.40–450 nM working 10 (cid:0) 5 M and LOD ≈1.07 ×10 (cid:0) 9 M, and the same electrode could be
range with an LOD of 0.048 nM (20 ppt), with affinity attributed to switched to electro-Fenton operation to drive targeted degradation
combined fluorophilic, electrostatic, and anion-π interactions, high- (~93% in 180 min) with substantial mineralization (TOC removal
lighting fluorinated MOFs as deployable electrode modifiers for PFAS ~86% and defluororination ~67%). The enhanced performance was
electroanalysis. Conductive MOF films extend this concept toward solid- attributed to selective imprinting interactions (O-H-π binding) that
state sensor devices. A copper-based 2D conductive MOF (Cu-HHTP) shorten the radical-to-target distance while Co/Fe redox cycling sustains
grown as a uniform thin film was integrated into chemiresistive and H2O2/.OH production, illustrating an integrated route for selective PFAS
impedance-based sensors, enabling ultrasensitive detection of PFOA and sensing with on-demand destructive treatment [288].
PFOS directly in drinking water. Owing to strong electrostatic and redox Lanthanide MOF-76 (Tb:Eu =29:1) was developed as a ratiometric
interactions between PFAS and the CuO4 coordination nodes, the device fluorescent probe to monitor PFOA photocatalytic degradation in real
exhibited measurable conductance changes at concentrations as low as time (Fig. 14e) [278]. The bimetallic Tb/Eu framework shows distinct,
0.002 ng/L, well below current health advisory limits. Combined reversible fluorescence color changes from green
(Tb3+
emission) to
experimental spectroscopy and DFT analysis indicate that sensing is orange-red
(Eu3+
emission) as PFOA is consumed and F
(cid:0)
is produced,
governed by MOF oxidation coupled with partial PFAS defluorination, enabling simultaneous sensing of both reactant and product with low
highlighting conductive MOF films as a promising platform for highly detection limits (LOD ≈0.0127 mM for PFOA and 0.00746 mM for F (cid:0) )
sensitive, device-integrated PFAS monitoring [284]. Fluorophilic engi- and good recoveries in real waters. By correlating the green/red in-
neering can further amplify electrochemical sensitivity. Zheng et al. tensity ratio with conversion, the authors construct a three-dimensional
[285]. prepared an electroactive F-Cu-NH2BDC via post-modification of G/R-conversion-time map that supports simple smartphone-based
Cu-NH2BDC with a tetrafluorinated aldehyde; F–F interactions pro- tracking of PFOA degradation without chromatography or mass spec-
moted PFOA self-aggregation on/within the MOF, which inhibited trometry. Recently, an amine-functionalized lanthanide MOF (EuTPTC-
electrolyte access and electron transfer to the
Cu2+
/Cu
+
redox centers NH2), assembled from H4TPTC-NH2 and
Eu3+
, was reported as a water-
and produced a “signal-off” response. The sensor provided a wide linear stable ratiometric luminescent probe for PFOA detection [247]. The
range (5 pM-500 μM) with an ultralow detection limit (3.54 pM) and probe uses an internal intensity ratio (I408/I616) to minimize matrix and
was validated in commercial drinking water with good anti-interference excitation variability and enables visual ratiometric readout in real
and reproducibility. samples, including seawater, with a limit of detection of 17.0 nM and a
MOF-derived materials provide additional routes to instrument-light clear emission-color change under 365 nm UV illumination. Mechanis-
PFAS screening. Li et al. [286] prepared cobalt-embedded N-doped tically, experiments and DFT support cooperative hydrogen bonding and
…
porous carbon nanosheets (CoNCN) from a 2D ZIF-L precursor, which electrostatic interactions, along with weak C-F H-Ar interactions be-
shows enhanced oxidase-like activity toward TMB; PFOS suppresses tween PFOA and the aromatic linker; importantly, PFOA-induced pro-
oxTMB formation (blue fading), enabling colorimetric PFOS detection tonation of the amine site suppresses linker ICT and weakens energy
with a linear range of 0.01–100 μM and an LOD of 20 nM. The method transfer to Eu3+ , producing the ratiometric response. The system also
was validated in river, lake, and tap water using standard addition with shows strong anti-interference performance against common ions and
recoveries of 95.73–104.44% and good storage stability (>90% activity PFAS analogs, highlighting Ln-MOF ratiometric sensing as a practical
retained after 5 weeks). Beyond MOF frameworks, additive- route for rapid PFOA screening in complex aqueous matrices. Beyond
manufactured plasmonic substrates provide a complementary route for direct signal transduction, MOFs are increasingly used as analytical PFAS
rapid PFAS screening. Aerosol jet-printed Ag and Ag/graphene SERS sorbents for rapid preconcentration prior to LC-MS. Petromelidou et al.
patches on flexible Kapton enabled Raman detection of PFOS down to [289]developed a MOF-polymeric monolith composite sorbent based on
10 (cid:0) 12 M (≈0.5 ng/L) and PFOA down to 10 (cid:0) 9 M, with stronger signals an Fe-MOF and an acrylic-acid/1-vinylimidazole copolymer (P(AA-VI))
under basic conditions; graphene addition increased PFAS adsorption for dispersive solid-phase extraction (dSPE) of 18 PFAS from environ-
and SERS intensity. This additive-manufacturing route offers repro- mental waters, followed by UHPLC-Orbitrap HRMS. Under optimized
ducible, low-cost, portable substrates for point-of-sampling PFAS conditions (pH 7, 10 mg sorbent with 10 mL sample, 15 min extraction;
screening [287]. elution with 750 μL MeOH assisted by ultrasonication), the method
Some MOFs function as both sensors and adsorbents. UiO-66-N delivered >70% recoveries, method detection limits of 1–46 ng/L, and
(CH3)3+ , obtained by quaternizing UiO-66-NH2, introduces cationic good precision (RSD < 20%), and was demonstrated in complex
ammonium sites for PFOA ion exchange and delivers a Langmuir ca- matrices including marine water, river water, effluent, and runoff. Data-
pacity of 1178 mg/g, ≈97% removal from 100 ppm and >99% removal driven approaches complement experimental work. Kim et al. [290]
of 50 ppb PFOA within 5 min, with high efficiency in the presence of compiled a 390-point dataset for adsorption of five endocrine-disrupting
common salts and over at least five regeneration cycles [191]. Uptake is compounds (BPA, CBM, EE2, PFOA, IBP) on Al-MOFs and benchmarked
dominated by electrostatic anion exchange between iodide and PFOA at 19 machine-learning models, finding that tree-based ensembles (Cat-
the quaternary ammonium groups rather than Zr coordination, and the Boost, XGBoost, GradientBoosting) predict adsorption capacity from
same material can be converted into a “turn-on” fluorescent sensor (UiO- operating conditions with R2 > 0.95, while a multimodal 1D-CNN
66-N(CH3)3+
@SRB) for selective PFOA detection [191]. In(tcpp) is a combining conditions with post-adsorption FT-IR spectra further im-
water-stable indium-based luminescent MOF (BET ≈535 m2/g) that acts proves accuracy and provides mechanistic signatures via Grad-CAM.
as a switchable dual sensor and scavenger for F- and PFOA, showing SHAP analysis ranks MOF dosage, contaminant concentration and con-
turn-on fluorescence for F- (LOD 1.3 μg/L), turn-off for PFOA (LOD 19 tact time as dominant variables, with pH effects emerging under alkaline
μg/L) and adsorption capacities of about 36.7 mg/g (F-) and 980 mg/g conditions, offering guidance for dose-time trade-offs, re-use and matrix
(PFOA), with ~90% PFOA removal within 30 min at 15 mM (Fig. 14d) effects. Representative MOFs and MOF-based composites reported for
[277]. CNF-Cu/C membranes combine peroxidase-like colorimetric PFAS sensing, are summarized in Table 3.
detection with solar-driven SPEF degradation in a single MOF-derived
platform [270]. A closely related “sense-and-treat” strategy couples 5.7. Computational insights and design principles
molecular imprinting with MOF-derived carbon nanofiber electrodes. A
Co/Fe-MOF-derived carbon nanofiber (Co/Fe@CNF) was coated with a Several studies use simulation to extract general design rules.
polypyrrole molecularly imprinted polymer (MIP) using PFOA as the Alkhatib et al. [276]used explicit-water MD to study PFOA adsorption
27

# Page 28

Table 3
Overview of MOFs-based analytical techniques for PFAS detection.
MOFs BET Detection Pollutant Sample LOD (nM) LOQ LDR Reproducibility Stability Refs.
surface method (nM) (nM) (RSD) and recovery
area (m2/ (R)
g)
UiO-66-N(CH₃)₃+ ​ Fluorescence “turn-on” PFOA Acetonitrile/water sensing 0.000022 nM – 0–5 ×106 nM – – [191]
(Zr) sensing via indicator medium; validated
displacement assay (IDA) selectivity against PFOS
using sulforhodamine B (SRB) and common interferents
EuTPTC-NH2 – Ratiometric luminescence PFOA Distilled water 16.1 nM – 0–500 nM – Stable luminescence [247]
(dual emission ratio I408/ within 24 h; pH stability
I616) 5–10
Seawater (spiked) 17.0 nM – RSD 0.442–0.593%; Stable in seawater over
R: 96.44–108.70%; 24 h
CNF-Cu/C-800 – Colorimetric (peroxidase-like PFOA – 133 nM – 1000–50,000 – – [270]
membrane TMB system; absorbance nM
(HKUST-1/PAN- readout)
derived Cu/C;
“nanozyme”
membrane)
MOF-76 (Tb:Eu = 27 Ratiometric fluorescence PFOA Seawater +drinking water 12,700 nM – – RSD =2.2–4.4%; R Framework stable in [278]
29:1) (smartphone RGB / (real samples; standard =99.3–102.7% water (used in aqueous
chromaticity-based readout addition) sensing); reported
for real-time monitoring of thermal stability up to
photocatalytic degradation) ~600 ◦C
MIL-101(Cr) 358.4 SPME (MIL-101-DETA-F PFBA, PFHxA, ultrapure water ~9.7 ×10(cid:0)6 -2.9 × ~2.4 × ~0.0012–3.62 RSD: 1.8–11.4%; R: Retains extraction [279]
coated probe) +UHPLC-MS/ PFOA, PFDA, (calibration) +real waters 10(cid:0)4 nM 10(cid:0)5 nM 76.2–108.6% efficiency over 150
MS PFDoA, PFBS, (tap, river, municipal -9.7 × consecutive runs
PFHxS, PFOS, wastewater, dyeing 10(cid:0)4 nM
PFOPA wastewater, mining
wastewater)
Cr-MIL-101 – Microfluidic electrochemical PFOS Laboratory water 0.001 nM 0.001 – – – [280]
impedance spectroscopy (EIS) (calibration); nM
with interdigitated demonstrated capability in
microelectrodes (IDμE) groundwater matrices
Eu/Tb-MOFs@MIPs – Ratiometric fluorescence; PFOA Tap water, lake water, 0.98 nM – 20–2800 nM RSD: 2.32–5.84%; – [281]
smartphone RGB readout river water (fluorescence, S/N R: 97.20–103.30%
platform =3), 3.26 nM
(smartphone, 3σ)
U-1 (PDI-based Zr- 1263 Fluorescence turn-on (MOF- PFOA Tap and 1.07 nM ​ 5.0–50 nM R: 91.4–99.2% – [282]
MOF) PFOA complex) in water/ drinking
DMF suspension water
Ce-UiO-66-F 656.9 LSV PFOA tap water, river water, 0.048 nM – 0.4–450 nM RSD: 2.45% (10 nM, Minimal decrease over [283]
campus lake water 5 successive 10 cycles
measurements)
R: 94.98–118.42%
Cu-HHTP thin film – EIS/chemiresistive PFOA contaminated/drinking 0.000005 nM – – – – [284]
device conductance change water F-Cu-NH2BDC – SWV (Cu2+/Cu+signal PFOA Commercial drinking 0.00354 nM – 0.005–500,000 RSD: 3.53%; R: 10 days with 4.30% [285] suppression) water nM 95.81–109.2% attenuation
Co/Fe bi-MOFs- – DPV PFOA Wastewater 1.073 nM – 10–90,000 nM R: 95.97–100.01% Good reproducibility [288] derived Co/ over 5 repeated
Fe@CNF with PPy- detections
based MIP
Au@ZIF-on-MIL + – Ratio fluorescence sensor PFNA – ~25.64 nM – – – Photostable [291]
AgAu@ZIF-on-MIL array +ML classification PFOA 30.67 nM
(sensor array) GenX (HFPO- 28.78 nM
DA)
PFHxA 30.89 nM
28
F.
Mashkoor
et
al.
C
o
o r d
i n
a
t i o
n C
h e m i s t r y
R e v i e w
s 559
(2026)
217818

# Page 29

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
in NU-1000 and two fluorinated derivatives (NU-PF with perfluoroalkyl chains in NU-PF block pore volume and reduce performance at high
chains, NU-F with 4-fluorobenzoate ligands), showing that hydrophobic loading, whereas NU-F balances hydrophobicity and pore accessibility,
interactions between the PFOA tail and pore walls dominate uptake and delivering superior removal and faster pseudo-second-order kinetics
that NU-1000 already reaches ≈90% removal at 4 mM PFOA. Fluori- across the concentration range; simulations also show lower removal for
nation strengthens tail-wall interactions, but bulky perfluoroalkyl shorter-chain PFCAs (PFPeA, PFPrA). Erkal et al. [215] screened 15
Fig. 15. Computational insights into PFAS-MOF binding. (a) MD simulations of PFOS uptake in SCU-8 showing adsorption pathway, COM distance, contact ratio,
binding free-energy landscape with representative basins/modes, and time evolution of desolvation, heavy-atom contacts, sulfonate-coordinated-water H-bonding,
and electrostatic/vdW interactions with key intermediates, Reproduced with permission [226]. Copyright 2017, Springer Nature. (b) DFT-derived HOMO-LUMO gaps
and optimized binding sites for ChG-MOF with PFOA, PFDA, PNBS, and PFOS, Reproduced with permission [259]. Copyright 2025, Elsevier. (c) UiO-67-2CF3/PFHxA
electronic descriptors (HOMO/LUMO, MESP), predicted attack sites, and charge-density differences, Reproduced with permission [256]. Copyright 2025, Elsevier.
(d) U-on-M SBU-PFOA optimized complexes comparing hydrogen bonding, coordination, hydrophobic, and electrostatic binding motifs with MESP maps, Repro-
duced with permission [261]. Copyright 2025, Royal Society of Chemistry. (e) MESP distribution of the (Zr6)2 SBU and optimized structures of (Zr6)2 and Zr6 SBUs
before and after PFOA binding at representative binding sites (C, O, F, and Zr shown in gray, red, light cyan, and cyan; H omitted for clarity), Reproduced with
permission [200]. Copyright 2024, American Chemical Society. (f) M@ZIF-on-MIL ratio-fluorescence sensor array and ML-enabled PFAS discrimination: XRD and
Zn2+ release before/after PFOA; ZIF-8-PFOA geometry; ratio-response statistics and ΔR/R0 patterns for eight PFAS; heat map, HCA, accuracy comparison across ML
models, and LDA clustering; validation in seawater, lake water, and river water with LDA score plots and confusion matrices, Reproduced with permission [291].
Copyright 2025, American Chemical Society. (For interpretation of the references to color in this figure legend, the reader is referred to the web version of
this article.)
29

# Page 30

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 15. (continued).
fluorinated MOFs and all-silica zeolite Beta for PFOA capture and immobilization stabilized by H-bonding to coordinated water plus hy-
concluded that the most effective sorbents combine strong PFOA- drophobic/vdW confinement in the pore. This points to a practical rule
framework interactions with low water affinity, hydrophobic pores set for PFAS sorbents: combine a positively charged framework (anion
and pore diameters in the 8–10 Å range, and that excessively PFOA- pre-concentration) with sufficiently open mesopores and localized hy-
philic SIFSIX/TIFSIX phases suffer from competitive water adsorption. drophobic pockets/H-bond donors to lock the headgroup while
Related explicit-water MD/DFT-guided analysis of the cationic meso- confining the fluorinated tail (Fig. 15a) [226]. DFT-based mechanistic
porous Th-MOF SCU-8 shows a staged PFOS uptake pathway: electro- work embedded in several experimental studies (ChG-MOF-808)
static anchoring of the sulfonate is followed by tail insertion and final (Fig. 15b) [259], Fe-MOFs [223], UiO-67-2CF3 (Fig. 15c) [256], PCN-
30

# Page 31

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 15. (continued).
1003 [272], MIL-125-NH2 [252], In(tcpp) [273], MOF-808 [164], UiO- with natural organic matter (NOM) that can screen charge, occupy
66-NH2@MIL-101(Cr) (Fig. 15d) [261], PCN-999 (Fig. 15e) [200]and adsorption domains, or form persistent surface coatings. Performance
others) converges on a consistent picture: PFAS capture in MOFs arises can therefore decay through progressive site capping and node-
from a tunable balance of electrostatic/ion-exchange interactions, Lewis environment changes even when crystallinity appears preserved. This
acid-base coordination, hydrophobic/fluorophilic confinement and highlights an important distinction that is often underemphasized:
specific π- or H-bonding contacts. These computational insights com- structural robustness (retained PXRD patterns) is not equivalent to co-
plement the experimental data and help define a structural “design map” ordination robustness (persistence of accessible, selective node envi-
for next-generation MOFs and MOF-based composites for PFAS ronments). A second unresolved challenge is the limited generalizability
remediation. of adsorption paradigms derived from PFOS and PFOA. Long-chain
In parallel with atomistic simulations, emerging data-driven anionic PFAS are well served by electrostatics, anion exchange, and
computational approaches extend these design principles by statisti- inner-sphere coordination at cationic SBUs, often reinforced by tail
cally decoding complex MOF-PFAS interaction landscapes that are packing in hydrophobic or fluorophilic pores. These drivers weaken
difficult to resolve using first-principles methods alone. Recent machine- substantially for short-chain PFAS, where hydration penalties and
learning-assisted studies have shown that MOF-on-MOF architectures reduced tail contributions demand more cooperative binding, and they
integrated with multi-channel optical readouts can generate PFAS- largely fail for neutral and zwitterionic PFAS precursors prevalent in
specific interaction fingerprints arising from coordination effects, hy- AFFF formulations. In those cases, uptake depends more on pore
drophobic interactions, and hydrogen bonding (Fig. 15f) [291]. Rather microenvironment engineering than on node charge density. Confine-
than explicitly computing adsorption energies, these approaches extract ment, polarity gradients, hydrogen-bond networks, and fluorophilic
discriminatory patterns from high-dimensional response data, enabling domains must collectively compensate for low polarizability and strong
reliable differentiation of structurally similar PFAS species even in solvation. Even in studies that recognize this shift, these microenvi-
complex water matrices. From a design perspective, such results rein- ronment effects are frequently treated qualitatively, leaving a gap in
force the importance of framework stability, tunable coordination en- transferable, predictive design rules. Defect chemistry introduces a
vironments, and responsive host-guest coupling as computationally further capacity-durability tension. Defect-rich MOFs can offer higher
tractable descriptors, particularly for sensing and screening platforms initial PFAS uptake by increasing the density of coordinatively unsatu-
where conventional adsorption metrics are insufficient. rated sites and amplifying local electrostatic fields. The same features
can accelerate irreversible poisoning by oxyanions, promote node hy-
6. Challenges and future outlook drolysis or ligand lability during cycling, and intensify sensitivity to
alkalinity and pH swings. The field still lacks consistent protocols to
Despite rapid progress in MOF-enabled PFAS remediation, several separate beneficial, regenerable “open-site” chemistry from defect
coordination-chemistry bottlenecks still limit translation from proof-of- landscapes that undermine long-term performance, particularly at
concept demonstrations to durable treatment platforms. A recurring environmentally relevant concentrations and in matrices containing
issue is that many high-performing MOFs rely on hard-hard interactions NOM and multivalent inorganic species. A closely related bottleneck is
between anionic PFAS headgroups and oxophilic, high-valent metal regeneration and life-cycle durability. Many studies demonstrate
nodes such as Zr(IV), Al(III), Fe(III), Th(IV), or rare-earth centers. In “regeneration” in short batch cycles under conditions that may not be
realistic waters, these same Lewis-acidic motifs are strongly competed compatible with field operation, such as aggressive pH swings, high
for by carbonate/bicarbonate, sulfate, phosphate, and silicate, along ionic strength eluents, organic solvents, or oxidants. These approaches
31

# Page 32

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
Fig. 15. (continued).
can restore apparent capacity but may gradually alter node speciation, design rules. The relationship between PFAS capture and PFAS
remove modulators, change defect density, or accumulate strongly destruction remains another central limitation. In many systems,
bound co-ions and organics that reduce selectivity over time. Long-term adsorption and degradation are demonstrated as loosely coupled steps
testing under continuous flow, with repeated regeneration and realistic rather than as a single coordination-enabled process. Strong binding can
water chemistry, is still limited. Without standardized metrics for ca- immobilize PFAS in geometries that hinder electron transfer or radical
pacity recovery, selectivity retention, leaching, and by-product man- access, while weaker binding undermines preconcentration and selec-
agement, it remains difficult to compare systems and identify stable tivity. A major practical gap is incomplete accounting of transformation
32

# Page 33

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
products and fluoride balance, which can mask partial defluorination, 7. Technology integration toward Field-based PFAS remediation
chain-shortening, or formation of persistent intermediates. The most
impactful architectures will be those that co-localize binding motifs and The transition of PFAS remediation from bench-scale adsorption
activation motifs in a way that controls distance, orientation, and local experiments to field deployment is, in essence, a systems-integration
solvation around the bound PFAS, enabling adsorption-assisted trans- problem. Candidate materials must be manufactured in deployable
formation to evolve into true coordination-enabled C–F activation with form factors, embedded within hydraulically stable unit operations, and
rigorous product closure. operated under continuous flow while influent composition, particulate
These challenges point to clear opportunities. MOF design needs to burden, and operating conditions evolve dynamically. Notably,
move beyond HSAB matching as a standalone principle and embrace contemporary full-scale practice remains anchored in capture-based
cooperative recognition under confinement, particularly for short-chain, media, dominated by activated carbon and anion-exchange resins sup-
neutral, and zwitterionic PFAS. Linker electronics, functional-group plied by a comparatively small cohort of industrial vendors (Table 4).
orientation, pore topology, and fluorophilicity should be treated as This state of practice underscores the persistent disconnect between
primary design variables rather than secondary modifiers. At the node laboratory demonstrations of PFAS “destruction” and technologies that
level, selectivity in the presence of competition should be prioritized can be qualified, permitted, and operated with high reliability at scale.
over maximal Lewis acidity, using strategies such as controlled site Field operation imposes stringent and quantifiable performance re-
saturation, steric modulation around open metal sites, and mixed-linker quirements. Media must preserve selectivity and working capacity at
microenvironments that bias binding equilibria away from ubiquitous ultra-trace concentrations across fluctuations in ionic strength, alka-
inorganic oxyanions and NOM-derived ligands. Heterometallic and linity, pH, and natural organic matter (NOM), while exhibiting pre-
redox-addressable SBUs offer an underused route to decouple PFAS af- dictable breakthrough behavior under sustained throughput. Long-
finity from competitive-anion poisoning while positioning redox-active duration campaigns additionally demand mechanical robustness, toler-
centers near adsorption domains, which is essential for integrated ance to attrition, and resistance to fouling, coupled with clearly defined
capture-to-destruction concepts. Progress toward predictive design and changeout and/or regeneration protocols that minimize secondary
real-world relevance will also depend on mechanistic validation under waste generation and associated liabilities. For MOF-enabled strategies,
realistic conditions. Operando and in situ tools that directly report node durability cannot be inferred solely from crystallinity or surface-area
speciation, coordination mode, hydration state, and competitive binding retention; rather, it is governed by the persistence and accessibility of
during uptake and cycling are needed, alongside theory that treats sol- the relevant coordination environments, including node speciation,
vation, confinement, and competition explicitly. More standardized open-metal sites, defect-associated binding motifs, and local microen-
reporting of matrix composition, continuous-flow performance, regen- vironments that confer PFAS affinity. Accordingly, deployment hinges
eration chemistry, metal/linker leaching, and transformation-product on process-compatible architectures. MOFs must be translated into
accounting (including fluoride mass balance) will be crucial for fixed-bed-compatible pellets or beads, structured monoliths, or immo-
comparing systems and identifying design rules that remain valid bilized composites on mechanically robust supports that can deliver
beyond idealized laboratory water. Overall, MOF-based PFAS remedia- controlled residence times at low pressure drop. However, intrinsic
tion is best advanced by treating it as a coordination-control problem sorbent selectivity is readily degraded by system-level constraints.
rather than an adsorption-capacity contest. Materials that preserve Channeling, maldistribution, and progressive pressure-drop growth
functional node environments in competitive waters, extend molecular reduce effective contact time, while binder chemistry and compaction
recognition to neutral and zwitterionic PFAS through engineered pore can occlude pore entrances and suppress access to coordination sites. In
microenvironments, and genuinely couple adsorption with chemically parallel, NOM, colloids, and suspended solids can foul external surfaces
enabled defluorination pathways are the ones most likely to define the and obstruct transport pathways, frequently shifting operation from a
next stage of progress. chemistry-limited regime to diffusion-limited performance. These re-
alities favor staged treatment trains, with upstream NOM/particulate
management, followed by PFAS-selective capture, and downstream
polishing where ultra-trace compliance is required. Beyond capture-only
Table 4
Commercially available PFAS adsorption media and representative suppliers currently used in drinking-water, groundwater, and industrial treatment systems.
Commercial adsorbent Representative Example commercial Typical deployment PFAS removal strengths Key limitations in practice
class companies products / offerings (practical trend)
Granular activated Calgon Carbon [292]; FILTRASORB® series; Fixed-bed vessels (often Well established for long- Reduced efficiency for short-chain and
carbon (GAC) Jacobi Carbons [293]; AquaSorb® series; YP- lead-lag); permanent or chain PFAS (PFOS, PFOA) ether PFAS; sensitive to NOM;
Kuraray [294] series carbons mobile systems under favorable water breakthrough strongly site-specific;
chemistry generates PFAS-laden spent carbon
Powdered activated Cabot Corporation DARCO® PAC; Dosed into treatment Rapid response option; can Separation and sludge handling;
carbon (PAC) [295]; Chemviron AquaPAC™ trains (coagulation/ reduce PFAS under inconsistent long-term PFAS control
[296] clarification or contact optimized conditions compared with GAC
basins)
PFAS-selective anion Purolite (Ecolab) Purofine™ PFA694E; Fixed-bed vessels or Often stronger for short- Competing anions reduce capacity;
exchange (AIX) [297]; DuPont [298] AmberLite™ PSR2 Plus packaged skid systems chain anionic PFAS; typically single-use; concentrated
resins smaller footprint than GAC PFAS on spent resin
Conventional strong- Lanxess [299]; Lewatit® S series; Columns in groundwater Broad anion removal Lower PFAS selectivity; regeneration
base anion exchange Mitsubishi Chemical DIAION™ series or industrial streams including PFAS produces PFAS-bearing brines
resins [300]
Integrated PFAS Xylem [301] GAC/IX packaged Utility and industrial Turn-key deployment; Still capture-only; downstream waste
treatment systems systems, mobile units installations compliance-focused design management required
(media +vessels +
service)
Point-of-use / point-of- 3 M [302]; Pentair Carbon block cartridges Household or small- Effective for long-chain Limited capacity; cartridge
entry carbon media [303] (NSF-certified variants) system protection PFAS with proper replacement critical; not a substitute
maintenance for plant-scale treatment
33

# Page 34

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
operation, coupling sorption with in situ regeneration or activation of- photoactive centers within controlled spatial and solvation environ-
fers a credible pathway to reduce residual burdens. Electrochemical and ments offers a pathway to move beyond sequestration toward true
photochemical modules can, in principle, enable capture-and-destroy coordination-enabled C–F bond activation. However, realizing these
cycling, but only when PFAS bound at coordination sites remains potential demands rigorous accounting of transformation products,
within effective proximity to reactive centers and when matrix constit- fluoride balance, and framework integrity to ensure that apparent
uents do not dominate radical or electron-transfer pathways. Regener- degradation corresponds to meaningful detoxification rather than par-
ation must therefore be engineered to preserve framework integrity, tial transformation or chain shortening. Looking forward, the translation
suppress metal leaching, avoid irreversible site poisoning, and prevent of MOF-based PFAS remediation from laboratory demonstrations to
formation of persistent transformation products that simply reallocate practical treatment technologies will depend on treating PFAS removal
risk to new waste streams. Achieving this requires explicit interfacial as a coordination-control problem embedded within a systems-
design, mass-transport control, and rigorous transformation-product engineering context. Advances in heterometallic and redox-
accounting as part of performance validation. Field readiness also de- addressable nodes, mixed-linker microenvironments, scalable synthe-
pends on monitoring and control. Online sensing, coupled with sis and shaping strategies, and operando characterization under realistic
chemistry-aware control rules and process models, can stabilize per- conditions will be central to this effort. When coupled with thoughtful
formance under matrix variability by optimizing flow, staging, and integration into treatment architectures and responsible regeneration
regeneration timing, while tracking breakthrough and capacity decay in strategies, MOFs offer a compelling pathway toward selective, durable,
real time. Such approaches can improve media utilization and reduce and potentially transformative solutions for PFAS-contaminated waters.
operational uncertainty by identifying conditions that accelerate
fouling, coordination-site poisoning, or framework aging. MOF-based
Declaration of competing interest
PFAS remediation should be treated as a coupled chemistry-
engineering design space, in which coordination selectivity, manufac-
The authors declare that they have no known competing financial
turable form factors, pretreatment and staging, regeneration strategy,
interests or personal relationships that could have appeared to influence
and operational intelligence must be co-optimized to deliver predictable
the work reported in this paper.
long-term performance in realistic waters.
Acknowledgement
8. Conclusions
This work was financially supported by the Korea Ministry of Envi-
Metal-organic frameworks have emerged as uniquely powerful
ronment (MOE) through the program Graduate School specialized in
platforms for addressing the persistent challenge of PFAS contamination
Integrated Water Resources Management. It was also supported by the
in water, owing to their unparalleled structural tunability, well-defined
National Research Foundation of Korea (NRF) grant funded by the Korea
coordination environments, and ability to couple molecular recognition
government (Ministry of Science and ICT, MSIT) (No. RS-2019-
with chemical transformation. Unlike conventional sorbents that rely
NR040065). Technical assistance for HR-TEM analysis was provided
largely on nonspecific hydrophobic partitioning or ion exchange, MOFs
by the Core Research Support Center for Natural Products and Medical
enable PFAS capture to be rationalized and engineered at the level of
Materials (CRCNM). Additionally, the authors extend their appreciation
coordination chemistry, where metal-node identity, linker electronics,
to the Deanship of Research and Graduate Studies at King Khalid Uni-
defect chemistry, and pore microenvironments collectively govern
versity for funding this work through Large Research Project under grant
selectivity, capacity, and durability. This review has shown that PFAS-
number RGP 2/604/46.
MOF interactions span a spectrum from outer-sphere electrostatic as-
sociation to inner-sphere metal-headgroup coordination, modulated by
Data availability
confinement effects and fluorophilic or hydrophobic tail interactions,
and that no single interaction mode is sufficient across the structural
No data was used for the research described in the article.
diversity of PFAS. A critical insight emerging from recent studies is that
design strategies optimized for long-chain anionic PFAS such as PFOS
References
and PFOA cannot be directly extrapolated to short-chain, neutral, or
zwitterionic PFAS, which increasingly dominate environmental and
[1] D.T. Adamson, J. Gamlin, Y. Jin, W. Casteel, C. Schaefer, C.P. Higgins, J. Hazard.
AFFF-related contamination. For these species, effective remediation Mater. 503 (2026) 141121.
depends less on maximizing Lewis's acidity or surface area and more on [2] A. Najafidoust, R. Ghanbari, J. Farahbakhsh, R. Permala, S. Iglauer, M. Zargar,
engineering cooperative pore microenvironments that compensate for Coord. Chem. Rev. 549 (2026) 217264.
[3] V. Chugh, P. Gaskin, W. Zhang, Sensors & Diagnostics 5 (2026).
strong hydration and low polarizability through confinement, polarity [4] F. Boschet, B. Ameduri, Chem. Rev. 114 (2014) 927–980.
gradients, hydrogen-bond networks, and tailored fluorophilicity. This [5] R.J. Plunkett, in: High Performance Polymers: Their Origin and Development:
shift highlights the need to move beyond adsorption-capacity bench- Proceedings of the Symposium on the History of High Performance Polymers at
the American Chemical Society Meeting held in New York, April 15–18, 1986,
marking toward coordination-informed design rules that remain valid Springer, 1986, pp. 261–266.
under realistic water chemistries. The review also underscores that [6] G.S. Kirshenbaum, High Performance Polymers: Their Origin and Development:
apparent framework stability, as inferred from retained crystallinity, Proceedings of the Symposium on the History of High Performance Polymers at
the American Chemical Society Meeting Held in New York, April 15–18, 1986,
does not guarantee sustained remediation performance. Competitive Springer Science & Business Media, 2012.
anions, natural organic matter, and regeneration-induced changes can [7] M. Hamza, R.T. Ayinla, I. Elsayed, E.B. Hassan, Environments 12 (2025) 330.
progressively alter node speciation, defect landscapes, and site accessi- [8] D.J. Liwara, A.R.L. Araújo, A. Pavlov, J.E. Johansen, H. Liu, J. Koekkoek,
M. Heinzelmann, J. de Boer, P.E.G. Leonards, S. Brandsma, Sci. Total Environ.
bility, leading to performance decay even in nominally robust MOFs.
993 (2025) 180006.
Addressing this challenge requires clearer differentiation between [9] A.L. Jarvis, J.R. Justice, M.C. Elias, B. Schnitker, K. Gallagher, Environ. Toxicol.
beneficial, regenerable coordination sites and defect chemistries that Chem. 40 (2021) 2425–2442.
compromise long-term durability, as well as standardized evaluation [10] G. Choi, J.M. Braun, A.P. Keil, T.J. Woodruff, S.H. Liu, X. Hong, G. Wang, S.
P. O'Leary, C.H. Yu, Z.T. Fan, C. Pearson, M. Wills-Karp, X. Wang, J.P. Buckley,
under environmentally relevant concentrations, matrices, and Environ. Int. 204 (2025) 109842.
continuous-flow conditions. Importantly, while adsorption remains the [11] H. Zang, Y. Feng, S. Gao, M. Su, Q. Feng, X. Chen, Environmental Science:
most mature application of MOFs for PFAS removal, the greatest long- Advances 4 (2025) 1712–1734.
[12] E.J. Itumoh, S. Data, J.L.-Y. Chen, M. Kah, L.P. Padhye, E.M. Leitao, Rsc
term impact is likely to come from architectures that integrate capture Sustainability 2 (2024) 3183–3201.
with destruction. Coordinating PFAS binding sites with redox-active or [13] G. Lorenzi, Archivio antropologico mediterraneo 26 (2024).
34

# Page 35

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
[14] G. Lorenzi, 2023. [65] E.R. Parnham, R.E. Morris, Acc. Chem. Res. 40 (2007) 1005–1013.
[15] U.O.P. Human Rights Centre, “Antonio Papisca”, in: Human Rights Centre [66] H.M. Titi, J.-L. Do, A.J. Howarth, K. Nagapudi, T. Friˇsˇci´c, Chem. Sci. 11 (2020)
“Antonio Papisca”, University of Padova, Human Rights Centre “Antonio 7578–7584.
Papisca”, University of Padova, Padova, Italy (location of the Centre/University), [67] J.M. Marrett, F. Effaty, X. Ottenwaelder, T. Friˇsˇci´c, Adv. Mater. 37 (2026)
2025. 2418707.
[16] A. Maerten, E. Callewaert, J. Sanz-Serrano, L. Devisscher, M. Vinken, Sci. Total [68] T. Friˇsˇci´c, D.G. Reid, I. Halasz, R.S. Stein, R.E. Dinnebier, M.J. Duer, Angew.
Environ. 954 (2024) 176717. Chem. Int. Ed. 49 (2010) 712–715.
[17] B.E. Blake, S.E. Fenton, Toxicology 443 (2020) 152565. [69] D. Chen, J. Zhao, P. Zhang, S. Dai, Polyhedron 162 (2019) 59–64.
[18] Z. Wang, J.C. DeWitt, C.P. Higgins, I.T. Cousins, Environ. Sci. Technol. 51 (2017) [70] C. McKinstry, R.J. Cathcart, E.J. Cussen, A.J. Fletcher, S.V. Patwardhan, J. Sefcik,
2508–2518. Chem. Eng. J. 285 (2016) 718–725.
[19] J.N. Meegoda, J.A. Kewalramani, B. Li, R.W. Marsh, Int. J. Environ. Res. Public [71] R. Rahman, F. Malik, Z. Min Hein, J. Huang, H. You, Y. Zhu, ChemPlusChem 90
Health 17 (2020) 8117. (2025) e202400634.
[20] X. Lei, Q. Lian, X. Zhang, T.K. Karsili, W. Holmes, Y. Chen, M.E. Zappi, D.D. Gang, [72] E.G. Rasmussen, J. Kramlich, I.V. Novosselov, Chem. Eng. J. 450 (2022) 138053.
Environ. Pollut. 321 (2023) 121138. [73] C. Sun, S.T. Pham, S.L. Boyall, B. Douglas, A.J. Britton, S. Micklethwaite, T.
[21] R.-R. Liang, Z. Liu, J. Rushlow, J. Huo, Z. Han, Y. Yang, H. Lin, H.-C. Zhou, ACS W. Chamberlain, M.O. Besenhard, R. Drummond-Brydson, K.-J. Wu, S.M. Collins,
Materials Letters 7 (2025) 3252–3274. Communications Chemistry 8 (2025) 154.
[22] M.L. Chaudhary, R. Patel, K.J. Chaudhary, R.K. Gupta, Industrial & Engineering [74] T.K. Vo, V.N. Le, V.C. Nguyen, M. Song, D. Kim, K.S. Yoo, B.J. Park, J. Kim, J. Ind.
Chemistry Research 64 (2025) 13536–13556. Eng. Chem. 86 (2020) 178–185.
[23] Y. Li, T. Fletcher, D. Mucs, K. Scott, C.H. Lindh, P. Tallving, K. Jakobsson, Occup. [75] Z.U. Nisa, N.A. Ashashi, H.N. Sheikh, Chapter 8 - synthesis of metal–organic
Environ. Med. 75 (2018) 46–51. frameworks with ionic liquids, in: Y. Azim, S.-U. Rather, S.A. Bhawani, P.M. Bhatt
[24] Y. Xu, T. Fletcher, D. Pineda, C.H. Lindh, C. Nilsson, A. Glynn, C. Vogs, (Eds.), Synthesis of Metal-Organic Frameworks Via Water-Based Routes, Elsevier,
K. Norstro¨m, K. Lilja, K. Jakobsson, Y. Li, Environ. Health Perspect. 128 (2020) 2024, pp. 143–158.
77004. [76] X. Sang, J. Zhang, J. Xiang, J. Cui, L. Zheng, J. Zhang, Z. Wu, Z. Li, G. Mo, Y. Xu,
[25] M.H. Russell, H. Nilsson, R.C. Buck, Chemosphere 93 (2013) 2419–2425. J. Song, C. Liu, X. Tan, T. Luo, B. Zhang, B. Han, Nat. Commun. 8 (2017) 175.
[26] Y. Shi, R. Vestergren, L. Xu, Z. Zhou, C. Li, Y. Liang, Y. Cai, Environ. Sci. Technol. [77] E. Virmani, J.M. Rotter, A. Ma¨hringer, T. von Zons, A. Godt, T. Bein, S. Wuttke, D.
50 (2016) 2396–2404. D. Medina, J. Am. Chem. Soc. 140 (2018) 4812–4819.
[27] B. Jin, H. Liu, S. Che, J. Gao, Y. Yu, J. Liu, Y. Men, Nat Water 1 (2023) 451–461. [78] Z. Zheng, H.L. Nguyen, N. Hanikel, K.K.-Y. Li, Z. Zhou, T. Ma, O.M. Yaghi, Nat.
[28] L. Gan, D. Wei, M. Hu, Y. Wang, M. Zhou, Small 22 (2026) e09977. Protoc. 18 (2023) 136–156.
[29] Z. Liu, M. Liao, L. Wang, S. Zhuang, Rev. Environ. Sci. Biotechnol. 24 (2025) [79] Z. Zheng, A.H. Alawadhi, O.M. Yaghi, Molecular Frontiers Journal 07 (2023)
63–95. 20–39.
[30] D. Lee, B.-M. Jun, J. Park, M. Jang, S. Lee, S.A. Snyder, C.M. Park, Y. Yoon, Nano [80] Q. Ma, T. Zhang, B. Wang, Matter 5 (2022) 1070–1091.
Convergence 12 (2025) 56. [81] X.-J. Kong, J.-R. Li, Engineering 7 (2021) 1115–1139.
[31] D. Castelvecchi, M. Naddaf, in, Nature portfolio Heidelberger Platz 3, Berlin, [82] A.E. Jery, R.D.C. Pecho, M. Tania Churampi Arellano, M. Aldrdery, A. Elkhaleefa,
14197, Germany, 2025. C. Wang, S.S. Sammen, H.H. Tizkam, Sustainability 15 (2023) 10617.
[32] N.P. Outreach, in: NobelPrize.org, Nobel Prize Outreach, NobelPrize.org, 2026. [83] N. Ili´c, K. Tan, F. Mayr, S. Hou, B.M. Aumeier, E.M.C. Morales, U. Hübner,
[33] A. Valavanidis, Nature 646 (2025) 522–523. J. Cookman, A. Schneemann, A. Gagliardi, Adv. Mater. 37 (2025) 2413120.
[34] M. Peplow, Nat. Biotechnol. 43 (2025) 1751. [84] S. Ko, F. Gao, X. Yao, H. Yi, X. Tang, C. Wang, H. Liu, N. Luo, Z. Qi, New J. Chem.
[35] K.O. Kirlikovali, S.L. Hanna, F.A. Son, O.K. Farha, ACS Nanoscience Au 3 (2023) 46 (2022) 15758–15775.
37–45. [85] H. Furukawa, K.E. Cordova, M. O'Keeffe, O.M. Yaghi, Science 341 (2013)
[36] R. Li, N.N. Adarsh, H. Lu, M. Wriedt, Matter 5 (2022) 3161–3193. 1230444.
[37] K. Sini, D. Bourgeois, M. Idouhar, M. Carboni, D. Meyer, New J. Chem. 42 (2018) [86] N. Stock, S. Biswas, Chem. Rev. 112 (2012) 933–969.
17889–17894. [87] M.J. Katz, Z.J. Brown, Y.J. Colo´n, P.W. Siu, K.A. Scheidt, R.Q. Snurr, J.T. Hupp,
[38] Y. Okawa, H. Konno, Sep. Purif. Technol. 382 (2026) 135956. O.K. Farha, Chem. Commun. 49 (2013) 9449–9451.
[39] C.S. Diercks, M.J. Kalmutzki, N.J. Diercks, O.M. Yaghi, ACS Cent. Sci. 4 (2018) [88] G. F´erey, Chem. Soc. Rev. 37 (2008) 191–214.
1457–1464. [89] J. Łuczak, M. Kroczewska, M. Baluk, J. Sowik, P. Mazierski, A. Zaleska-Medynska,
[40] H. Li, M. Eddaoudi, M. O'Keeffe, O.M. Yaghi, nature 402 (1999) 276–279. Adv. Colloid Interface Sci. 314 (2023) 102864.
[41] H. Li, M. Eddaoudi, T.L. Groy, O. Yaghi, J. Am. Chem. Soc. 120 (1998) [90] R.S. Forgan, Chem. Sci. 11 (2020) 4546–4562.
8571–8572. [91] D. Jiang, A.D. Burrows, K.J. Edler, CrystEngComm 13 (2011) 6916–6919.
[42] B. Deeraj, J.S. Jayan, A. Raman, A. Asok, R. Paul, A. Saritha, K. Joseph, Surf. [92] M. Zou, M. Dong, T. Zhao, Int. J. Mol. Sci. 23 (2022) 9396.
Interfaces 43 (2023) 103574. [93] G.C. Shearer, S. Chavan, S. Bordiga, S. Svelle, U. Olsbye, K.P. Lillerud, Chem.
[43] D.J. Tranchemontagne, J.R. Hunt, O.M. Yaghi, Tetrahedron 64 (2008) Mater. 28 (2016) 3749–3761.
8553–8557. [94] D.K. Sannes, S. Øien-Ødegaard, E. Aunan, A. Nova, U. Olsbye, Chem. Mater. 35
[44] E.N. Augustus, A. Nimibofa, I.A. Kesiye, W. Donbebe, Am. J. Environ. Prot 5 (2023) 3793–3800.
(2017) 61–67. [95] X. Feng, J. Hajek, H.S. Jena, G. Wang, S.K.P. Veerapandian, R. Morent, N. De
[45] S. Kitagawa, R. Kitaura, S.I. Noro, Angew. Chem. Int. Ed. 43 (2004) 2334–2375. Geyter, K. Leyssens, A.E.J. Hoffman, V. Meynen, C. Marquez, D.E. De Vos, V. Van
[46] O.M. Yaghi, M. O'Keeffe, N.W. Ockwig, H.K. Chae, M. Eddaoudi, J. Kim, Nature Speybroeck, K. Leus, P. Van Der Voort, J. Am. Chem. Soc. 142 (2020) 3174–3183.
423 (2003) 705–714. [96] W. Zhang, Z. Shahnavaz, X. Yan, X. Huang, S. Wu, H. Chen, J. Pan, T. Li, J. Wang,
[47] S.R. Batten, S.M. Neville, D.R. Turner, Coordination Polymers: Design, Analysis Inorg. Chem. 61 (2022) 15287–15301.
and Application, Royal Society of Chemistry, 2009. [97] J. Cravillon, S. Münzer, S.-J. Lohmeier, A. Feldhoff, K. Huber, M. Wiebcke, Chem.
[48] A.Y. Robin, K.M. Fromm, Coord. Chem. Rev. 250 (2006) 2127–2157. Mater. 21 (2009) 1410–1412.
[49] N.W. Ockwig, O. Delgado-Friedrichs, M. O'Keeffe, O.M. Yaghi, Acc. Chem. Res. 38 [98] Y. Pan, Y. Liu, G. Zeng, L. Zhao, Z. Lai, Chem. Commun. 47 (2011) 2071–2073.
(2005) 176–182. [99] A. Akhundzadeh Tezerjani, R. Halladj, S. Askari, RSC Advances 11 (2021)
[50] Z. Ji, H. Wang, S. Canossa, S. Wuttke, O.M. Yaghi, Adv. Funct. Mater. 30 (2020) 19914–19923.
2000238. [100] A.H. Assen, K. Adil, K.E. Cordova, Y. Belmabkhout, Coord. Chem. Rev. 468 (2022)
[51] J.H. Cavka, S. Jakobsen, U. Olsbye, N. Guillou, C. Lamberti, S. Bordiga, K. 214644.
P. Lillerud, J. Am. Chem. Soc. 130 (2008) 13850–13851. [101] D. Senthil Raja, D.-H. Tsai, Chem. Commun. 60 (2024) 8497–8515.
[52] C.A. Trickett, K.J. Gagnon, S. Lee, F. G´andara, H.B. Bürgi, O.M. Yaghi, Angew. [102] A.K. Gupta, M. Saraf, P.K. Bharadwaj, S.M. Mobin, Inorg. Chem. 58 (2019)
Chem. Int. Ed. 54 (2015) 11162–11167. 9844–9854.
[53] S. Yuan, J.-S. Qin, C.T. Lollar, H.-C. Zhou, ACS Cent. Sci. 4 (2018) 440–450. [103] S.S. Mabaleha, A. Sandaruwani, C. Peng, D. Zou, W. Ren, C.-X. Zhao, X. Xu,
[54] W. Morris, C.J. Doonan, O.M. Yaghi, Inorg. Chem. 50 (2011) 6853–6855. Materials Science and Engineering: R: Reports 165 (2025) 101005.
[55] W. Chen, Z. Wang, Q. Wang, K. El-Yanboui, K. Tan, H.M. Barkholtz, D.-J. Liu, [104] M. Faustini, J. Kim, G.-Y. Jeong, J.Y. Kim, H.R. Moon, W.-S. Ahn, D.-P. Kim,
P. Cai, L. Feng, Y. Li, J. Am. Chem. Soc. 145 (2023) 4736–4745. J. Am. Chem. Soc. 135 (2013) 14619–14626.
[56] P. Horcajada, S. Surbl´e, C. Serre, D.-Y. Hong, Y.-K. Seo, J.-S. Chang, J.- [105] J. Shen, M. Shafiq, M. Ma, H. Chen, Nanomaterials 10 (2020) 1177.
M. Gren`eche, I. Margiolaki, G. F´erey, Chem. Commun. (2007) 2820–2822. [106] E. Karbassiyazdi, M. Kasula, S. Modak, J. Pala, M. Kalantari, A. Altaee, M.
[57] D. Bara, E.G. Meekel, I. Pakamore˙, C. Wilson, S. Ling, R.S. Forgan, Mater. Horiz. 8 R. Esfahani, A. Razmjou, Chemosphere 311 (2023) 136933.
(2021) 3377–3386. [107] S. Li, J. Ma, J. Cheng, G. Wu, S. Wang, C. Huang, J. Li, L. Chen, Langmuir 40
[58] N. Ogiwara, W. Zhou, S. Uchida, Chem. Sci. 15 (2024) 19212–19224. (2024) 2815–2829.
[59] H. Reinsch, M. Krüger, J. Wack, J. Senker, F. Salles, G. Maurin, N. Stock, [108] H.-Y. Wu, C.-L. Wu, W. Liao, B.M. Matsagar, K.-Y. Chang, J.-H. Huang, K.C.
Microporous Mesoporous Mater. 157 (2012) 50–55. W. Wu, J. Mater. Chem. A 11 (2023) 9427–9435.
[60] C.D. Tutson, A.E. Gorden, Coord. Chem. Rev. 333 (2017) 27–43. [109] T. Bailey, M. Pinto, N. Hondow, K.-J. Wu, MethodsX 8 (2021) 101246.
[61] K. Patra, H. Pal, RSC Sustainability 3 (2025) 629–660. [110] J. Cui, N. Gao, X. Yin, W. Zhang, Y. Liang, L. Tian, K. Zhou, S. Wang, G. Li,
[62] D. Yang, B.C. Gates, J. Phys. Chem. C 128 (2024) 8551–8559. Nanoscale 10 (2018) 9192–9198.
[63] D. Chakraborty, A. Yurdusen, G. Mouchaham, F. Nouar, C. Serre, Adv. Funct. [111] J. Klinowski, F.A.A. Paz, P. Silva, J. Rocha, Dalton Trans. 40 (2011) 321–330.
Mater. 34 (2024) 2309089. [112] J.-S. Choi, W.-J. Son, J. Kim, W.-S. Ahn, Microporous and Mesoporous Materials
[64] T.J. Azbell, T.A. Pitt, M.M. Bollmeyer, C. Cong, K.M. Lancaster, P.J. Milner, 116 (2008) 727–731.
Angew. Chem. Int. Ed. 62 (2023) e202218252. [113] P.T. Phan, J. Hong, N. Tran, T.H. Le, Nanomaterials 13 (2023) 352.
35

# Page 36

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
[114] C. McKinstry, E.J. Cussen, A.J. Fletcher, S.V. Patwardhan, J. Sefcik, Chem. Eng. J. [165] H. Li, A.L. Junker, J. Wen, L. Ahrens, M. Sillanp¨a¨a, J. Tian, F. Cui, L. Vergeynst,
326 (2017) 570–577. Z. Wei, Chem. Eng. J. 452 (2023) 139202.
[115] Z. Zhao, H. Li, K. Zhao, L. Wang, X. Gao, Chem. Eng. J. 428 (2022) 131006. [166] L. García, P. García-Atienza, S. Armenta, J.M. Herrero-Martínez, M. Prejano`,
[116] H. Liu, Y. Zhao, C. Zhou, B. Mu, L. Chen, Chem. Phys. Lett. 780 (2021) 138906. T. Marino, D. Armentano, T. Grancha, J. Ferrando-Soria, E. Pardo, J. Mater.
[117] S. Tanaka, Chapter 10 - Mechanochemical synthesis of MOFs, in: M. Mozafari Chem. A 13 (2025) 42204–42214.
(Ed.), Metal-Organic Frameworks for Biomedical Applications, Woodhead [167] A. Pramanik, O.P. Kolawole, S. Kundu, K. Gates, S. Rai, M.K. Shukla, P.C. Ray,
Publishing, 2020, pp. 197–222. ACS Omega 9 (2024) 49452–49462.
[118] A. Pichon, A. Lazuen-Garay, S.L. James, CrystEngComm 8 (2006) 211–214. [168] C.T. Vu, T. Wu, Crit. Rev. Environ. Sci. Technol. 52 (2022) 90–129.
[119] D. Matoga, M. Oszajca, M. Molenda, Chem. Commun. 51 (2015) 7637–7640. [169] L.N. Pincus, H.E. Rudel, P.V. Petrovi´c, S. Gupta, P. Westerhoff, C.L. Muhich, J.
[120] T. Friˇsˇci´c, L. Fa´bi´an, CrystEngComm 11 (2009) 743–745. B. Zimmerman, Environ. Sci. Technol. 54 (2020) 9769–9790.
[121] S. Głowniak, B. Szczę´sniak, J. Choma, M. Jaroniec, Mater. Today 46 (2021) [170] N. Assaad, G. Sabeh, M. Hmadeh, ACS Appl. Nano Mater. 3 (2020) 8997–9008.
109–124. [171] S. Daliran, A.R. Oveisi, C.-W. Kung, U. Sen, A. Dhakshinamoorthy, C.-H. Chuang,
[122] L. Sondermann, Q. Smith, T. Strothmann, A. Vollrath, T.H. Yen Beglau, C. Janiak, M. Khajeh, M. Erkartal, J.T. Hupp, Chem. Soc. Rev. 53 (2024) 6244–6294.
RSC Mechanochemistry 1 (2024) 296–307. [172] M. Zhang, A.O. Yazaydin, Chem. Eng. J. 499 (2024) 155851.
[123] Z. Wang, Z. Li, M. Ng, P.J. Milner, Dalton Trans. 49 (2020) 16238–16244. [173] J. Mikel, B. Berens, G. Versnik, K. Wadzinski, T. Rottiger, M. Siewert,
[124] A. Harrison, P. Julien, A. Pang. O. Stellpflug, S.C. Riha, J.E. Mondloch, ACS Omega 10 (2025) 44311–44320.
[125] K. Uˇzarevi´c, T.C. Wang, S.-Y. Moon, A.M. Fidelli, J.T. Hupp, O.K. Farha, T. Friˇsˇci´c, [174] H.-M. Tan, C.-G. Pan, C. Yin, K. Yu, Toxics 11 (2023) 161.
Chem. Commun. 52 (2016) 2133–2136. [175] X. Min, J. Huo, Q. Dong, S. Xu, Y. Wang, Chem. Eng. J. 446 (2022) 137019.
[126] D. Crawford, J. Casaban, R. Haydon, N. Giri, T. McNally, S.L. James, Chem. Sci. 6 [176] H.-H. Kim, P.G. Koster van Groos, Y. Zhao, A.L.-T. Pham, Water Res. 260 (2024)
(2015) 1645–1649. 121925.
[127] P.A. Julien, K. Uzarevic, A.D. Katsenis, S.A. Kimber, T. Wang, O.K. Farha, [177] M. Hubab, I.E. Gilani, M.A. Al-Ghouti, Environ. Technol. Innovation 37 (2025)
Y. Zhang, J. Casaban, L.S. Germann, M. Etter, J. Am. Chem. Soc. 138 (2016) 104004.
2929–2932. [178] J.A. Sleep, S.J. Miklavcic, A.L. Juhasz, Chemosphere 319 (2023) 137910.
[128] A.D. Katsenis, A. Puˇskari´c, V. S ˇ trukil, C. Mottillo, P.A. Julien, K. Uˇzarevi´c, M.- [179] S. Zhou, L. Shi, Y. Li, T. Yang, S. Zhao, Adv. Funct. Mater. 34 (2024) 2400767.
H. Pham, T.-O. Do, S.A. Kimber, P. Lazi´c, Nat. Commun. 6 (2015) 6662. [180] M. Sun, H. Liu, X. Wang, X. Yang, F. Gao, D. Xie, W. Fan, Y. Han, B. Xu, D. Sun,
[129] M. Taheri, T.G. Enge, T. Tsuzuki, Materials Today Chemistry 16 (2020) 100231. Chin. J. Struct. Chem. 42 (2023) 100146.
[130] C. Vaitsis, G. Sourkouni, C. Argirusis, Ultrason. Sonochem. 52 (2019) 106–119. [181] C.A. Clark, K.N. Heck, C.D. Powell, M.S. Wong, ACS Sustain. Chem. Eng. 7 (2019)
[131] W.-J. Son, J. Kim, J. Kim, W.-S. Ahn, Chem. Commun. (2008) 6336–6338. 6619–6628.
[132] C.P. Raptopoulou, Materials 14 (2021) 310. [182] V.V. Torbina, Y.A. Belik, O.V. Vodyankina, React. Chem. Eng. 10 (2025)
[133] S. Głowniak, B. Szczę´sniak, J. Choma, M. Jaroniec, Molecules 28 (2023) 2639. 1197–1215.
[134] D.-W. Jung, D.-A. Yang, J. Kim, J. Kim, W.-S. Ahn, Dalton Trans. 39 (2010) [183] P. Ji, T. Drake, A. Murakami, P. Oliveres, J.H. Skone, W. Lin, J. Am. Chem. Soc.
2883–2887. 140 (2018) 10553–10561.
[135] J. Kim, S.-T. Yang, S.B. Choi, J. Sim, J. Kim, W.-S. Ahn, J. Mater. Chem. 21 (2011) [184] F. Vermoortele, M. Vandichel, B. Van de Voorde, R. Ameloot, M. Waroquier,
3070–3076. V. Van Speybroeck, D.E. De Vos, Angew. Chem. Int. Ed. 51 (2012) 4887–4890.
[136] K. Yu, Y.-R. Lee, J.Y. Seo, K.-Y. Baek, Y.-M. Chung, W.-S. Ahn, Microporous and [185] Z.H. Rada, H.R. Abid, H. Sun, J. Shang, J. Li, Y. He, S. Liu, S. Wang, Prog. Nat.
Mesoporous Materials 316 (2021) 110985. Sci.: Mater. Int. 28 (2018) 160–167.
[137] J.H. Lee, Y. Ahn, S.-Y. Kwak, ACS Omega 7 (2022) 23213–23222. [186] G.E. Cmarik, M. Kim, S.M. Cohen, K.S. Walton, Langmuir 28 (2012)
[138] S. Bagheri, F. Pazoki, A. Heydari, ACS Omega 5 (2020) 21412–21419. 15606–15613.
[139] F. Lo Presti, A.L. Pellegrino, N. Consoli, G. Malandrino, Molecules 28 (2023) [187] K. Chakarova, I. Strauss, M. Mihaylov, N. Drenchev, K. Hadjiivanov, Microporous
6088. and Mesoporous Materials 281 (2019) 110–122.
[140] H.-Y. Cho, J. Kim, S.-N. Kim, W.-S. Ahn, Microporous and Mesoporous Materials [188] C. Nanthamathee, C. Chantarangkul, C. Jakkrawhad, A. Payaka,
169 (2013) 180–184. P. Dechatiwongse, Heliyon 8 (2022) e08961.
[141] H. Ren, T. Wei, ChemElectroChem 9 (2022) e202200196. [189] L.W. Bingel, Z. Yu, D.S. Sholl, K.S. Walton, J. Phys. Chem. C 127 (2023)
[142] U. Mueller, M. Schubert, F. Teich, H. Puetter, K. Schierle-Arndt, J. Pastr´e, 20881–20889.
J. Mater. Chem. 16 (2006) 626–636. [190] Y. Feng, Q. Chen, M. Jiang, J. Yao, Industrial & Engineering Chemistry Research
[143] A. Ghoorchian, A. Afkhami, T. Madrakian, M. Ahmadi, Chapter 9 - 58 (2019) 17646–17659.
electrochemical synthesis of MOFs, in: M. Mozafari (Ed.), Metal-Organic [191] R. Dalapati, J. Shi, M. Hunter, L. Zang, J. Mater. Chem. C 13 (2025)
Frameworks for Biomedical Applications, Woodhead Publishing, 2020, 16753–16762.
pp. 177–195. [192] D. Hedbom, P. Gaiser, T. Günther, O. Cheung, M. Strømme, M. Åhl´en, M. Sjo¨din,
[144] W. Wu, G.E. Decker, A.E. Weaver, A.I. Arnoff, E.D. Bloch, J. Rosenthal, ACS J. Mater. Chem. A 13 (2025) 1731–1737.
Central Science 7 (2021) 1427–1433. [193] G.H. Pham, C.Z. Dinu, RSC Sustainability 1 (2023) 1125–1149.
[145] N. Campagnol, T.R.C. Van Assche, M. Li, L. Stappers, M. Dinca˘, J.F.M. Denayer, [194] L.I. FitzGerald, J.F. Olorunyomi, R. Singh, C.M. Doherty, ChemSusChem 15
K. Binnemans, D.E. De Vos, J. Fransaer, J. Mater. Chem. A 4 (2016) 3914–3925. (2022) e202201136.
[146] R. Ameloot, L. Stappers, J. Fransaer, L. Alaerts, B.F. Sels, D.E. De Vos, Chem. [195] G. F´erey, C. Mellot-Draznieks, C. Serre, F. Millange, J. Dutour, S. Surbl´e,
Mater. 21 (2009) 2580–2582. I. Margiolaki, Science 309 (2005) 2040–2042.
[147] N. Campagnol, T. Van Assche, T. Boudewijns, J. Denayer, K. Binnemans, D. De [196] A.C. Tella, J.T. Bamgbose, V.O. Adimula, M. Omotoso, S.E. Elaigwu, V.
Vos, J. Fransaer, J. Mater. Chem. A 1 (2013) 5827–5830. T. Olayemi, O.A. Odunola, SN Appl. Sci. 3 (2021) 136.
[148] T.R.C. Van Assche, N. Campagnol, T. Muselle, H. Terryn, J. Fransaer, J.F. [197] J. Winarta, B. Shan, S.M. McIntyre, L. Ye, C. Wang, J. Liu, B. Mu, Cryst. Growth
M. Denayer, Microporous and Mesoporous Materials 224 (2016) 302–310. Des. 20 (2020) 1347–1362.
[149] T.R.C. Van Assche, G. Desmet, R. Ameloot, D.E. De Vos, H. Terryn, J.F. [198] M. Arhangelskis, A.D. Katsenis, N. Novendra, Z. Akimbekov, D. Gandrath, J.
M. Denayer, Microporous and Mesoporous Materials 158 (2012) 209–213. M. Marrett, G. Ayoub, A.J. Morris, O.K. Farha, T. Friˇsˇci´c, A. Navrotsky, Chem.
[150] S. Zhou, O. Shekhah, J. Jia, J. Czaban-Jo´´zwiak, P.M. Bhatt, A. Ramírez, J. Gascon, Mater. 31 (2019) 3777–3783.
M. Eddaoudi, Nat. Energy 6 (2021) 882–891. [199] Y.-Q. Tian, Y.-M. Zhao, Z.-X. Chen, G.-N. Zhang, L.-H. Weng, D.-Y. Zhao,
[151] J.-Z. Wei, F.-X. Gong, X.-J. Sun, Y. Li, T. Zhang, X.-J. Zhao, F.-M. Zhang, Inorg. Chemistry – A European Journal 13 (2007) 4146–4154.
Chem. 58 (2019) 6742–6747. [200] R.-R. Liang, S. Xu, Z. Han, Y. Yang, K.-Y. Wang, Z. Huang, J. Rushlow, P. Cai,
[152] L. Wan, C. Zhou, K. Xu, B. Feng, A. Huang, Microporous and Mesoporous P. Samorì, H.-C. Zhou, J. Am. Chem. Soc. 146 (2024) 9811–9818.
Materials 252 (2017) 207–213. [201] Y. Hu, M. Guo, S. Zhang, W. Jiang, T. Xiu, S. Yang, M. Kang, Z. Dongye, Z. Li,
[153] A. Micero, T. Hashem, H. Gliemann, A. L´eon, Membranes 11 (2021) 735. L. Wang, Microporous and Mesoporous Materials 333 (2022) 111740.
[154] W. Dong, J. Yan, T. Ji, M. Wu, K. Yu, Y. Liu, W. Hu, Y. Liu, Advanced Membranes [202] K.S. Park, Z. Ni, A.P. Coˆt´e, J.Y. Choi, R. Huang, F.J. Uribe-Romo, H.K. Chae,
5 (2025) 100142. M. O'Keeffe, O.M. Yaghi, Proc. Natl. Acad. Sci. 103 (2006) 10186–10191.
[155] Z. Han, Y. Yang, J. Rushlow, J. Huo, Z. Liu, Y.-C. Hsu, R. Yin, M. Wang, R. Liang, [203] M. Nazari, F. Zadehahmadi, M.M. Sadiq, A.L. Sutton, H. Mahdavi, M.R. Hill,
K.-Y. Wang, H.-C. Zhou, Chem. Soc. Rev. 54 (2025) 367–395. Commun. Mater. 5 (2024) 170.
[156] A.O.C. Iroegbu, M.L. Teffo, E.R. Sadiku, R. Meijboom, S.P. Hlangothi, npj Clean [204] F. Liu, J. Cheng, Y. Guo, W. Yao, H. Qian, Z. Yu, T. Zhao, Y. Xie, Environ. Res. 291
Water 8 (2025) 85. (2026) 123494.
[157] W.-J. Li, J. Lü, S.-Y. Gao, Q.-H. Li, R. Cao, J. Mater. Chem. A 2 (2014) [205] D. Marchetti, E. Dalcanale, R. Pinalli, M. Gemmi, A. Pedrini, C. Massera, RSC
19473–19478. Mechanochemistry 2 (2025) 662–669.
[158] J.L.C. Rowsell, O.M. Yaghi, Microporous Mesoporous Mater. 73 (2004) 3–14. [206] R. Li, S. Alomari, R. Stanton, M.C. Wasson, T. Islamoglu, O.K. Farha, T.M. Holsen,
[159] C. Xiao, J. Tian, Q. Chen, M. Hong, Chem. Sci. 15 (2024) 1570–1610. S.M. Thagard, D.J. Trivedi, M. Wriedt, Chem. Mater. 33 (2021) 3276–3285.
[160] S. Singh, N. Sivaram, B. Nath, N.A. Khan, J. Singh, P.C. Ramamurthy, npj Clean [207] C. Zhao, Y. Xu, F. Xiao, J. Ma, Y. Zou, W. Tang, Chem. Eng. J. 406 (2021) 126852.
Water 7 (2024) 124. [208] S.-F. Li, T.-T. Liu, L.-J. Ye, J. Su, G. Zhang, Ind. Eng. Chem. Res. 64 (2025)
[161] S.C.E. Leung, D. Wanninayake, D. Chen, N.-T. Nguyen, Q. Li, Sci. Total Environ. 11544–11550.
905 (2023) 166764. [209] P. Reichert, F.G. Christensen, M.H. Petersen, S. Gopalakrishnan, J. Sundberg,
[162] R.G. Pearson, Coord. Chem. Rev. 100 (1990) 403–425. (2025).
[163] C. Wang, J. Yan, S. Chen, Y. Liu, ChemPlusChem 88 (2023) e202200462. [210] R. Zhang, C. Fan, M. Jin, Microchem. J. 218 (2025) 115272.
[164] P.-H. Chang, C.-Y. Chen, R. Mukhopadhyay, W. Chen, Y.-M. Tzou, B. Sarkar, [211] J. Luo, F. Luo, H. Li, C. Mao, Y. Pan, Z. Fang, D. Yu, H. Liu, K. Fu, Angew. Chem.
J. Colloid Interface Sci. 623 (2022) 627–636. 64 (2025) e202514746.
36

# Page 37

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
[212] J. Kim, X. Xin, B.T. Mamo, G.L. Hawkins, K. Li, Y. Chen, Q. Huang, C.-H. Huang, [258] G. Di Palma, P. Banerjee, K. Enemark-Rasmussen, S. Talebi Deylamani, J.
ACS EST Water 2 (2022) 1380–1390. R. Jinschek, Advanced Materials, Interfaces (2025) 2500166.
[213] D. Li, C.-S. Lee, Y. Zhang, R. Das, F. Akter, A.K. Venkatesan, B.S. Hsiao, J. Mater. [259] S. Dutta, M.A. Aretxabaleta, M.M. Shirolkar, S. Wuttke, E. Lizundia, Chem. Eng. J.
Chem. A 11 (2023) 9868–9883. 526 (2025) 170898.
[214] T. Grancha, P. García-Atienza, L. García, S. Armenta, J.M. Herrero-Martínez, [260] A.S. Abouzied, A.B. Al, N.S. Alsaiari, S.A. Aldaghfag, M.A. Ismail, M. Karimov,
D. Armentano, T.F. Mastropietro, J. Ferrando Soria, E. Pardo, Small 21 (2025) A. Abduvokhidov, O. Mukhitdinov, I. Mahariq, Sep. Purif. Technol. 382 (2025)
e10000. 136051.
[215] T.S. Erkal, N. Shamsuddin, S. Kirmizialtin, A.O. Yazaydin, J. Phys. Chem. C 127 [261] H. Lin, Z. Xia, K. Xue, X. Zhou, Y. Yao, N. Ma, W. Dai, J. Mater. Chem. A 13 (2025)
(2023) 3204–3216. 33276–33293.
[216] K. Zhang, P. Cheng, Y. Liu, S. Xia, Water Res. 265 (2024) 122276. [262] H. Lin, Z. Xia, K. Xue, X. Zhou, Y. Yao, N. Ma, W. Dai, Particuology 97 (2025)
[217] L. Cheng, C. Fan, W. Deng, Chemosphere 358 (2024) 142155. 130–142.
[218] J. Zhang, Z. Huang, L. Gao, S. Gray, Z. Xie, Sci. Total Environ. 806 (2022) [263] J. Wang, C.-S. Cao, J. Wang, Y. Zhang, L. Zhu, Appl. Catal. Environ. 304 (2022)
151207. 121013.
[219] V. Van Thang, N. Tran Duy Nguyen, M.N. Nadagouda, T.M. Aminabhavi, [264] M. Pilevar, H. Jafarian, N. Behzadnia, Q. Liang, S.E. Maleki, S.A. Aktij,
Y. Vasseghian, S.-W. Joo, J. Environ. Manage. 368 (2024) 122248. M. Sadrzadeh, L. Terry, M. Elliott, M.D. Firouzjaei, Water Research X 27 (2025)
[220] X. Zhang, H. Wu, Y. Wang, Y. Wang, Y. Deng, Y. Zhu, S. Zhang, H. Rijnaarts, 100358.
H. Bruning, J. Qin, Q. Lin, Z. Ni, R. Qiu, Water Res. 268 (2025) 122625. [265] M. Koli, S.P. Singh, Desalination 619 (2025) 119559.
[221] Y. Han, C. Fan, Y. Shan, X. Cao, Microchem. J. 197 (2024) 109884. [266] Y. Bi, X. Meng, Z. Tan, Q. Geng, J. Peng, Q. Yong, X. Sun, M. Guo, X. Wang, Sci.
[222] Q. Li, S. Zhu, F. Chen, C. Guo, Environ. Res. 211 (2022) 113083. Total Environ. 925 (2024) 171727.
[223] Y. Yang, Z. Zheng, W. Ji, J. Xu, X. Zhang, J. Hazard. Mater. 395 (2020) 122686. [267] M. Prajapati, S. Kalla, A. Sivaiah, Process Saf. Environ. Prot. 194 (2025) 152–163.
[224] S. Yoon, J. Park, A.K.R. Police, J.K. Choe, S. Bae, J. Hazard. Mater. 483 (2025) [268] S.A. Minhas, R.P. Pandey, M. Abi Jaoude, S.W. Hasan, Sep. Purif. Technol. 370
136687. (2025) 133139.
[225] Y. Zhang, K. Kong, Q. Wu, T. Ma, J. Liang, R. Wang, ChemSusChem 17 (2024) [269] Y. Qi, F. Li, C. Zhang, X. Tang, C. Wang, Y. Liang, H. Sun, B. Xing, ACS ES&T Eng.
e202400069. 5 (2025) 1405–1416.
[226] Y. Li, Z. Yang, Y. Wang, Z. Bai, T. Zheng, X. Dai, S. Liu, D. Gui, W. Liu, M. Chen, [270] C. Hou, F. Chen, D. Cheng, S. Zou, J. Wang, M. Shen, Y. Wang, Chem. Eng. J. 481
Nat. Commun. 8 (2017) 1354. (2024) 148467.
[227] M.-J. Chen, A.-C. Yang, N.-H. Wang, H.-C. Chiu, Y.-L. Li, D.-Y. Kang, S.-L. Lo, [271] X. Liu, B. Xu, X. Duan, Q. Hao, W. Wei, S. Wang, B.-J. Ni, Environ. Sci. Nano 8
Microporous and Mesoporous Materials 236 (2016) 202–210. (2021) 1010–1018.
[228] P.-H. Chang, R. Mukhopadhyay, B. Zhong, Q.-Y. Yang, S. Zhou, Y.-M. Tzou, [272] R.-R. Liang, Y. Fu, Z. Han, Y. Yang, V.I. Bakhmutov, Z. Liu, J. Rushlow, H.-
B. Sarkar, J. Colloid Interface Sci. 636 (2023) 459–469. C. Zhou, Nature Water 2 (2024) 1218–1225.
[229] L. Jiang, R. Cao, Z. Huang, J. Jin, Z. Du, H. Li, Chem. Eng. J. 502 (2024) 158161. [273] Z. Kong, L. Lu, C. Zhu, J. Xu, Q. Fang, R. Liu, Y. Shen, Sep. Purif. Technol. 297
[230] B.J. Place, J.A. Field, Environ. Sci. Technol. 46 (2012) 7120–7127. (2022) 121449.
[231] L.A. D'Agostino, S.A. Mabury, Environ. Sci. Technol. 48 (2014) 121–129. [274] S. Sheybani, M. Abbas, H.R. Firouzi, Z. Xiao, H.-C. Zhou, K.J. Balkus Jr., Inorg.
[232] K.A. Barzen-Hanson, S.C. Roberts, S. Choyke, K. Oetjen, A. McAlees, N. Riddell, Chem. 62 (2023) 4314–4321.
R. McCrindle, P.L. Ferguson, C.P. Higgins, J.A. Field, Environ. Sci. Technol. 51 [275] A. Amari, A.I. Saber, H. Osman, V. Spalevic, B. Dudic, Appl Water Sci 14 (2024)
(2017) 2047–2057. 200.
[233] K.A. Barzen-Hanson, S.E. Davis, M. Kleber, J.A. Field, Environ. Sci. Technol. 51 [276] N. Alkhatib, A.O. Yazaydin, S. Kirmizialtin, Chem. Mater. 37 (2025) 4027–4037.
(2017) 12394–12404. [277] H.-Q. Yin, K. Tan, S. Jensen, S.J. Teat, S. Ullah, X. Hei, E. Velasco, K. Oyekan,
[234] C.S. Tshangana, S.T. Nhlengethwa, S. Glass, S. Denison, A.T. Kuvarega, T.T. N. Meyer, X.-Y. Wang, Chem. Sci. 12 (2021) 14189–14197.
I. Nkambule, B.B. Mamba, P.J.J. Alvarez, A.A. Muleja, npj Clean, Water 8 (2025) [278] M. Song, R. Yu, Y. Shang, K. Tashpulatov, H. Sun, J. Zeng, Chemosphere 363
41. (2024) 142946.
[235] L. Hua, M.B. Solomon, D.M. D'Alessandro, W.A. Donald, J. Hazard. Mater. 494 [279] Y. Jia, J. Qian, B. Pan, Anal. Chem. 93 (2021) 11116–11122.
(2025) 138679. [280] Y.H. Cheng, D. Barpaga, J.A. Soltis, V. Shutthanandan, R. Kargupta, K.S. Han, B.
[236] F. Dixit, G. Munoz, M. Mirzaei, B. Barbeau, J. Liu, S.V. Duy, S. Sauv´e, P. McGrail, R.K. Motkuri, S. Basuray, S. Chatterjee, ACS Appl. Mater. Interfaces 12
B. Kandasubramanian, M. Mohseni, Environ. Sci. Technol. 56 (2022) 6212–6222. (2020) 10503–10514.
[237] P.S. Pauletto, M. Florent, T.J. Bandosz, Carbon 191 (2022) 535–545. [281] Y. Yang, X. Liu, B. Mu, S. Meng, S. Mao, W. Tao, Z. Li, Biosens. Bioelectron. 257
[238] S. Kabiri, C.L. Monaghan, D. Navarro, M.J. McLaughlin, Environ. Sci.: Water Res. (2024) 116330.
Technol. 10 (2024) 420–430. [282] R. Dalapati, M. Hunter, M. Sk, X. Yang, L. Zang, ACS Appl. Mater. Interfaces 16
[239] N. Xu, H. Lin, Q. Du, S. Dong, J. Cheng, P. Wang, J.-M. Lin, Lab Chip 23 (2023) (2024) 32344–32356.
3062–3069. [283] Q. Tian, S. Chen, M. Shi, T. Gao, M. Zhang, C. Liao, X. Li, Q. Dong, C. Wang, Sens.
[240] Y. Zhao, L. Wu, K. Wu, R.-J. Wei, H. Zeng, H. Pang, W. Lu, D. Li, Coord. Chem. Actuators B 404 (2024) 135309.
Rev. 524 (2025) 216302. [284] H. Roh, T.J. Quill, G. Chen, H. Gong, Y. Cho, H.J. Kulik, Z. Bao, A. Salleo,
[241] K. Fu, J. Huang, F. Luo, Z. Fang, D. Yu, X. Zhang, D. Wang, M. Xing, J. Luo, A. Gumyusenge, ACS Nano 19 (2025) 6332–6341.
Environ. Sci. Technol. 58 (2024) 16669–16689. [285] X. Zheng, C. Li, N. Yang, L. Niu, F. Gao, Q. Wang, Anal. Chem. 97 (2025)
[242] B. Yan, J. Liu, Water Res X 19 (2023) 100175. 6347–6358.
[243] T.C. Ricard, T.C. Schutt, C.G. Bresnahan, M.K. Shukla, Environmental Science: [286] Y. Li, Y. Lu, X. Zhang, H. Cao, Y. Huang, Microchem. J. 181 (2022) 107814.
Advances 4 (2025) 1633–1649. [287] C. McDonnell, F.M. Albarghouthi, R. Selhorst, N. Kelley-Loughnane, A.
[244] L. Figueroa-Quintero, D. Villalgordo-Herna´ndez, J.J. Delgado-Marín, J. Narciso, D. Franklin, R. Rao, ACS Omega 8 (2023) 1597–1605.
V.K. Velisoju, P. Castan˜o, J. Gasco´n, E.V. Ramos-Ferna´ndez, Small Methods 7 [288] Y. Wang, R. Ren, F. Chen, L. Jing, Z. Tian, Z. Li, J. Wang, C. Hou, Sep. Purif.
(2023) 2201413. Technol. 310 (2023) 123257.
[245] S. Mandal, S. Natarajan, P. Mani, A. Pankajakshan, Adv. Funct. Mater. 31 (2021) [289] S. Petromelidou, T. Zoi, V. Alampanos, D.N. Bikiaris, D.A. Lambropoulou,
2006291. Microchem. J. 207 (2024) 111795.
[246] Y.-X. Wang, R. Wang, Z.-X. Wang, Q. Shen, S. Liu, G. Li, Inorg. Chem. Front. 13 [290] H.G. Kim, B.-M. Jun, H. Jeong, Y. Yoon, K.H. Cho, J. Water Process Eng. 80
(2026) 1376–1420. (2025) 109105.
[247] W. Xia, Q. Niu, X. Liu, H. Zhuo, J. Liu, X. He, S. Zhou, Z. Ge, B. Liang, Z. Li, ACS [291] M. Wang, Y. Han, G. Sun, J. Chen, X. Zhao, K. Qiu, S. Lu, D. Liu, S. Wang,
Appl. Mater. Interfaces 17 (2025) 52276–52284. H. Wang, Anal. Chem. 97 (2025) 18010–18019.
[248] X. Chen, T. Yuan, X. Yang, S. Ding, M. Ma, Catalysts 13 (2023) 1308. [292] C.C. Corporation, in: PFAS (Industrial / Remediation), Calgon Carbon
[249] P. Su, C. Zhang, Y. Liu, J. Zhang, R. Djellabi, R. Wang, J. Guo, R. Zhang, H. Guo, Corporation, Pittsburgh, PA, USA (Calgon Carbon headquarters), 2019 pp. (Web
X. Ding, X. Liu, J. Environ. Chem. Eng. 11 (2023) 110765. brochure describing Calgon Carbon's activated carbon and related technologies
[250] L.A. Gonz´alez Fern´andez, N.A. Medellín Castillo, M. Sa´nchez Polo, J.E. Vilaso´- for PFAS removal from wastewater and environmental remediation).
Cadre, I.A. Reyes-Domínguez, L.D. de Leo´n-Martínez, Catalysts 15 (2025) 946. [293] J.C. Group, in: PFAS Treatment in Drinking Water and Wastewater – Jacobi
[251] Y. Wen, A. Kirchon, G.S. Day, H. Lin, M.F. Smith, A. Boehme, R.O.K. Ozdemir, V. Group, Jacobi Carbons Group, Kalmar, Sweden (Jacobi Carbons Group
K. Sharma, X. Ma, H.-C. Zhou, Sep. Purif. Technol. 354 (2025) 128877. headquarters), 2025 pp. (Web article and brochure describing PFAS
[252] Y. Wen, A ´ . Rentería-Go´mez, G.S. Day, M.F. Smith, T.-H. Yan, R.O.K. Ozdemir, contamination issues and Jacobi's activated carbon and ion exchange solutions for
O. Gutierrez, V.K. Sharma, X. Ma, H.-C. Zhou, J. Am. Chem. Soc. 144 (2022) drinking water and industrial wastewater).
11840–11850. [294] K.E. GmbH, in: Waste water treatment – Kuraray Europe GmbH, Kuraray Europe
[253] S. Barisci, R. Suri, J. Water Process Eng. 39 (2021) 101745. GmbH, Hattersheim am Main, Germany (Kuraray Europe GmbH headquarters),
[254] D. Camdzic, H.K. Welgama, M.R. Crawley, A. Avasthi, T.R. Cook, D.S. Aga, ACS 2024 pp. Product page describing Kuraray's activated carbon products and
Applied Engineering Materials 2 (2024) 87–95. services for drinking water and wastewater treatment, including mobile filters
[255] R. Li, S. Alomari, T. Islamoglu, O.K. Farha, S. Fernando, S.M. Thagard, T. and reactivation.
M. Holsen, M. Wriedt, Environ. Sci. Technol. 55 (2021) 15162–15171. [295] C. Corporation, In: news release details – Cabot Corporation, Cabot Corporation,
[256] X. Zhang, X. Zeng, M. Rong, M. Yu, H. Yu, J. Niu, J. Hazard. Mater.498 (2025) Boston, MA, USA (Cabot headquarters), 2017 pp. press release announcing
139877. HYDRODARCO 4000 and NORIT GAC 4400 granular activated carbons for
[257] H. Guo, T. Hu, X. Yang, Z. Liu, Q. Cui, C. Qu, F. Guo, S. Liu, A.J. Sweetman, removal of PFAS (including PFOA and PFOS) from public water systems and
J. Hou, W. Tan, Environ. Res. 251 (2024) 118679. compliance with U.S. EPA health advisory limits.
37

# Page 38

F. Mashkoor et al. C o o r d i n a t i o n C h e m i s t r y R e v i e w s 559 (2026) 217818
[296] C.a.K. company, in: PFAS removal – Chemviron solutions, Chemviron, Europe (MCAM Europe HQ; if your style requires a city, use Düsseldorf for Engineering
(Chemviron European Operations of Calgon Carbon; if a city is required, use Plastics Shapes), 2025 pp. Explains the ECHA February 7, 2023 REACH Annex
Brussels, Belgium, where Chemviron S.A. is registered), 2025 pp. Technical XVII proposal to restrict over 2010,2000 PFAS, discusses implications for PTFE-
overview of PFAS, explaining Chemviron's granular activated carbon, mobile and PVDF-containing engineering plastics, lists affected MCAM stock shapes, and
filter systems, and thermal reactivation services for removing long- and short- outlines how the company supports customers in selecting PFAS-free alternatives.
chain PFAS from drinking water, wastewater, air, and remediation streams. [301] X. Inc., in: Making Waves – Water Utilities News, Xylem Inc., Washington, DC,
[297] E. (Purolite), in: PFAS removal – ion exchange resin for drinking water systems USA (Xylem US corporate base for this content; if your style needs a city, use
and industrial discharge, Purolite, an Ecolab company, King of Prussia, PA, USA Washington, DC or Rye Brook, NY where Xylem is headquartered), 2024 pp.
(Purolite headquarters), 2025 pp. Product and technology overview describing Technical overview explaining PFAS characteristics, regulatory drivers (including
Ecolab's Purofine PFA694 ion exchange resins for removal of short- and long- the April 2024 US national PFAS drinking-water standard and EU rules), and
chain PFAS from drinking water and industrial discharge, including discussion of available treatment technologies such as GAC, ion exchange, advanced adsorption
regulations, advantages over GAC, and disposal options for spent resin. media, and reverse osmosis, with recommendations for utilities.
[298] I. DuPont de Nemours, in: PFAS | DuPont, DuPont de Nemours, Inc., Wilmington, [302] M. Company, in: 3M's PFAS Stewardship – PFAS & Their Uses, 3M Company, St.
DE, USA (DuPont corporate headquarters), 2025 pp. Corporate statement Paul, MN, USA (3M corporate headquarters), 2025 pp. Corporate overview
explaining that DuPont de Nemours, established in 2019, has never manufactured explaining what PFAS are, listing major application sectors, and summarizing
PFOA, PFOS, or firefighting foam, uses only select PFAS under strict management 3M's plan to exit PFAS manufacturing and discontinue PFAS use across its product
as substances of concern, is seeking alternatives, and commits to compliance with portfolio by the end of 2025, with links to the “2023M PFAS in Products
PFAS regulations and high standards of chemical stewardship. Supplemental Report.
[299] L.D.G.L. brand, in: Lewatit® ion exchange resins – case studies and stories, [303] P. plc, in: Commercial PFAS reduction – Issues & Solutions, Pentair Commercial
LANXESS Deutschland GmbH, Cologne, Germany (LANXESS headquarters), 2025 Filtration, Minneapolis, MN, USA (Pentair U.S. base; Pentair plc is headquartered
pp. Application note describing PFAS contamination issues and the performance in the UK, but the page targets US commercial filtration customers), 2025 pp.
of Lewatit TP 108 DW and other Lewatit ion exchange resins for removing PFAS Short commercial overview describing PFAS as persistent “forever chemicals,”
to ppt levels, comparing performance and cost to activated carbon and emphasizing EPA resources and certified lab testing, and promoting Pentair's
summarizing field results at Australian airport fire-training sites. third-party tested Everpure PFAS reduction filters and systems for foodservice and
[300] M.C.G.E.S.S. Division, in: PFAS: What you need to know – PFAS alternatives in commercial drinking-water applications.
engineering plastics, Mitsubishi Chemical Group (MCAM), Düsseldorf, Germany
38

