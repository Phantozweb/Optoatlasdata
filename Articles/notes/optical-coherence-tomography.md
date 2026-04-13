

# Optical Coherence Tomography

---

**Optical Coherence Tomography (OCT)** is a non-invasive, high-resolution, cross-sectional imaging modality that utilizes [[low-coherence interferometry]] to generate two-dimensional and three-dimensional images of biological tissue microstructure in vivo. Since its introduction into clinical ophthalmology in the early 1990s, OCT has fundamentally transformed the diagnosis, monitoring, and management of a vast spectrum of ocular diseases affecting the [[retina]], [[optic nerve head]], [[choroid]], and [[anterior segment]]. Often described as performing an "optical biopsy," OCT provides near-histological resolution of ocular tissues without the need for tissue excision, making it one of the most indispensable diagnostic instruments in modern [[optometry]] and [[ophthalmology]] practice.

The technology was pioneered by Dr. David Huang and colleagues at the Massachusetts Institute of Technology (MIT) in 1991, with the first in vivo retinal images published shortly thereafter. Since that seminal work, OCT has undergone multiple generational advances—from Time-Domain OCT (TD-OCT) to Spectral-Domain OCT (SD-OCT), Swept-Source OCT (SS-OCT), and Enhanced Depth Imaging OCT (EDI-OCT)—each iteration providing superior axial resolution, faster scan speeds, and deeper tissue penetration. Today, OCT and its derivative technologies, including [[OCT Angiography]] (OCTA), are considered the standard of care in the evaluation and longitudinal management of conditions such as [[glaucoma]], [[age-related macular degeneration]], [[diabetic retinopathy]], and numerous other [[vitreoretinal]] and [[anterior segment]] pathologies.

---

## Physical Principles and Technology

### Fundamental Physics of OCT

OCT operates on the principle of **[[low-coherence interferometry]]**, analogous to [[ultrasonography]] (B-scan) but using light instead of sound. Because the speed of light (~3 × 10⁸ m/s) is approximately six orders of magnitude faster than the speed of sound in tissue, direct measurement of optical echo time delays is not feasible with conventional electronics. Instead, OCT employs an [[interferometer]]—most commonly a [[Michelson interferometer]]—to measure the echo time delay and magnitude of backscattered or back-reflected light from tissue microstructures.

In a basic OCT system, a beam of broadband, low-coherence light (typically from a [[superluminescent diode]] or a swept-source laser) is split by a [[beam splitter]] into two arms:

1. **Reference Arm**: Light travels to a reference mirror at a known distance.
2. **Sample Arm**: Light is directed into the tissue being imaged (e.g., the [[retina]]).

Light reflected from the reference mirror and backscattered from tissue structures recombines at the beam splitter. Constructive interference occurs only when the optical path lengths of the two arms match to within the [[coherence length]] of the light source. By analyzing this interference pattern, the system constructs a depth-resolved reflectivity profile of the tissue, known as an **A-scan** (axial scan). Multiple adjacent A-scans are combined to form a **B-scan** (cross-sectional image), and multiple B-scans can be assembled into a volumetric **C-scan** (three-dimensional dataset).

### Generations of OCT Technology

| **Generation** | **Technology** | **Axial Resolution** | **Scan Speed (A-scans/sec)** | **Light Source** | **Key Features** |
|---|---|---|---|---|---|
| **TD-OCT** | Time-Domain | ~10 µm | 400 | [[Superluminescent diode]] (SLD), ~820 nm | Mechanically scanning reference mirror; first commercial systems (e.g., Stratus OCT) |
| **SD-OCT** | Spectral-Domain (Fourier-Domain) | 5–7 µm | 20,000–100,000 | SLD, ~840 nm | Stationary reference mirror; spectrometer-based detection; dramatically faster |
| **SS-OCT** | Swept-Source (Fourier-Domain) | 5–8 µm | 100,000–400,000+ | Tunable swept laser, ~1050 nm | Longer wavelength enables deeper penetration (choroid, sclera); reduced signal roll-off |
| **EDI-OCT** | Enhanced Depth Imaging | 5–7 µm | Same as SD-OCT | SLD, ~840 nm | Inverted image; optimized for [[choroidal]] imaging |
| **UHR-OCT** | Ultra-High Resolution | 2–3 µm | Variable | Femtosecond laser / ultra-broadband SLD | Research-grade; resolves individual retinal sublayers |

#### Time-Domain OCT (TD-OCT)

The first-generation clinical OCT systems, exemplified by the **Zeiss Stratus OCT (OCT3)**, employed TD-OCT. In this configuration, the reference mirror is mechanically translated to vary the optical path length, and interference is detected sequentially at each depth position. While revolutionary at the time, TD-OCT was limited by relatively slow acquisition speeds (~400 A-scans/second), lower axial resolution (~10 µm), and susceptibility to motion artifacts. Despite these limitations, TD-OCT established the foundational normative databases and clinical paradigms for retinal and [[optic nerve head]] assessment.

#### Spectral-Domain OCT (SD-OCT)

SD-OCT, also known as Fourier-Domain OCT, represents a paradigm shift. Rather than mechanically scanning the reference mirror, SD-OCT uses a stationary reference mirror and a [[spectrometer]] to simultaneously detect all frequency components of the interference signal. A mathematical [[Fourier transform]] is then applied to the spectral data to reconstruct the depth profile. This approach yields acquisition speeds 50–100 times faster than TD-OCT (typically 20,000–100,000 A-scans/second) with improved axial resolution (5–7 µm) and superior signal-to-noise ratio. The dramatic increase in speed enables dense raster scanning, volumetric imaging, and significantly reduced motion artifacts. Major commercial SD-OCT platforms include the **Heidelberg Spectralis**, **Zeiss Cirrus HD-OCT**, **Optovue Avanti RTVue**, and **Topcon 3D OCT**.

#### Swept-Source OCT (SS-OCT)

SS-OCT is another form of Fourier-Domain OCT that uses a rapidly tunable (swept) laser source, typically centered around **1050 nm** (compared to ~840 nm for SD-OCT). The longer wavelength provides several advantages:

- **Deeper tissue penetration** through the [[retinal pigment epithelium]] (RPE) and into the [[choroid]] and [[sclera]]
- **Reduced signal attenuation** in eyes with [[media opacities]] such as [[cataracts]]
- **Reduced sensitivity roll-off** with depth, enabling more uniform image quality across the full imaging range
- **Ultra-fast scan speeds** exceeding 100,000–400,000 A-scans/second

SS-OCT is particularly valuable for imaging the [[choroid]], evaluating [[pachychoroid spectrum diseases]], and imaging through dense cataracts or [[vitreous hemorrhage]]. The **Zeiss PLEX Elite 9000** and **Topcon DRI OCT Triton** are prominent SS-OCT platforms.

#### Enhanced Depth Imaging OCT (EDI-OCT)

EDI-OCT is a technique developed by Spaide et al. that can be implemented on standard SD-OCT platforms (notably the Heidelberg Spectralis). By positioning the instrument closer to the eye and inverting the image, the zero-delay line is placed near the [[choroid]] rather than the inner retina, thereby optimizing sensitivity for deeper structures. EDI-OCT enabled the first systematic measurements of [[choroidal thickness]] and has been instrumental in characterizing conditions such as [[central serous chorioretinopathy]], [[Vogt-Koyanagi-Harada disease]], and [[polypoidal choroidal vasculopathy]].

---

## OCT Angiography (OCTA)

**[[OCT Angiography]]** (OCTA) is a functional extension of OCT that provides non-invasive, dye-free visualization of retinal and choroidal vasculature. OCTA detects the motion of [[erythrocytes]] within blood vessels by comparing sequential B-scans acquired at the same retinal location. Decorrelation algorithms (e.g., split-spectrum amplitude-decorrelation angiography [SSADA], optical microangiography [OMAG]) identify voxels with signal change between consecutive scans, which correspond to blood flow, and distinguish them from static tissue.

OCTA generates **en face** angiograms of distinct vascular layers:

- **Superficial capillary plexus (SCP)**
- **Deep capillary plexus (DCP)**
- **Intermediate capillary plexus (ICP)** (in some segmentation protocols)
- **Outer retina** (normally avascular; flow here suggests [[choroidal neovascularization]])
- **Choriocapillaris**
- **Choroidal vasculature**

OCTA has become invaluable in the evaluation of [[diabetic retinopathy]] (detecting [[microaneurysms]], non-perfusion areas, and [[neovascularization]]), [[age-related macular degeneration]] (identifying and monitoring [[choroidal neovascular membranes]]), retinal vascular occlusions, and [[glaucoma]] (assessing peripapillary and macular vessel density).

**Limitations of OCTA** include a limited field of view (though widefield OCTA montages are now available), susceptibility to motion and projection artifacts, inability to detect leakage (unlike [[fluorescein angiography]]), and segmentation errors in eyes with significant pathology.

---

## Anatomy as Visualized on OCT

A thorough understanding of normal retinal anatomy on OCT is essential for identifying pathological changes. On a standard SD-OCT B-scan through the [[fovea]], the following layers are identifiable from innermost (vitreous side) to outermost (scleral side):

| **Layer** | **OCT Appearance** | **Anatomical Correlate** |
|---|---|---|
| [[Internal limiting membrane]] (ILM) | Thin hyperreflective line | Basement membrane of [[Müller cells]] |
| [[Retinal nerve fiber layer]] (RNFL) | Hyperreflective band (thickest near [[optic disc]]) | [[Ganglion cell]] axons |
| [[Ganglion cell layer]] (GCL) | Hyporeflective | Ganglion cell bodies |
| [[Inner plexiform layer]] (IPL) | Hyperreflective | Synapses between ganglion, [[bipolar cells|bipolar]], and [[amacrine cells]] |
| [[Inner nuclear layer]] (INL) | Hyporeflective | Bipolar, amacrine, horizontal, and Müller cell nuclei |
| [[Outer plexiform layer]] (OPL) | Hyperreflective | Synapses between bipolar cells and [[photoreceptors]] (Henle fiber layer at fovea) |
| [[Outer nuclear layer]] (ONL) | Hyporeflective | Photoreceptor nuclei |
| [[External limiting membrane]] (ELM) | Thin hyperreflective line | Junctional complexes between Müller cells and photoreceptors |
| [[Ellipsoid zone]] (EZ) / IS/OS junction | Prominent hyperreflective band | Photoreceptor inner segment ellipsoid (mitochondria-rich) |
| [[Interdigitation zone]] (IZ) | Hyperreflective line | Apical processes of RPE interdigitating with photoreceptor outer segments |
| [[Retinal pigment epithelium]] (RPE)/[[Bruch's membrane]] complex | Thick hyperreflective band | RPE cell layer and Bruch's membrane |
| [[Choroid]] | Moderate reflectivity with vascular lumina | Choroidal stroma and vasculature |

The **[[foveal pit]]** is characterized by the absence of inner retinal layers (RNFL, GCL, IPL, INL), with only the outer retinal layers and a thickened ONL (containing densely packed [[cone photoreceptors]]) present at the foveal center. The central foveal thickness (CFT) is typically measured from the ILM to the RPE/Bruch's membrane complex and normally ranges from approximately **200–280 µm** depending on the OCT platform and measurement protocol.

---

## Clinical Applications in Ocular Disease

### Retinal Diseases

#### Age-Related Macular Degeneration (AMD)

OCT is the cornerstone imaging modality for the diagnosis and management of both **dry** (non-exudative) and **wet** (exudative/neovascular) [[age-related macular degeneration]].

- **Dry AMD**: OCT identifies [[drusen]] (focal elevations of the RPE over Bruch's membrane), [[reticular pseudodrusen]] (subretinal drusenoid deposits appearing as hyperreflective material above the RPE), [[geographic atrophy]] (loss of RPE, photoreceptors, and choriocapillaris with increased signal transmission into the choroid), and nascent geographic atrophy. Quantitative drusen volume and area measurements can be tracked longitudinally.
- **Wet AMD**: OCT detects hallmark features of [[choroidal neovascularization]] (CNV) including [[subretinal fluid]] (SRF), [[intraretinal fluid]] (IRF)/cystoid spaces, [[pigment epithelial detachment]] (PED), sub-RPE hyperreflective material, and subretinal hyperreflective material (SHRM). OCT is the primary tool for guiding [[anti-VEGF]] treatment decisions (treat-and-extend, pro re nata protocols) by monitoring fluid status.

#### Diabetic Retinopathy and Diabetic Macular Edema

OCT is essential for evaluating **[[diabetic macular edema]]** (DME), the leading cause of vision loss in [[diabetic retinopathy]]. OCT quantifies central macular thickness, identifies patterns of edema (diffuse, cystoid, serous detachment), detects [[hard exudates]] (hyperreflective foci), and identifies [[vitreomacular traction]] that may contribute to refractory edema. OCTA further characterizes the [[foveal avascular zone]] (FAZ) enlargement, capillary non-perfusion, and [[microaneurysms]]. OCT findings directly guide treatment with [[anti-VEGF]] agents, [[intravitreal corticosteroids]], or [[focal/grid laser photocoagulation]].

#### Retinal Vein Occlusions

In [[branch retinal vein occlusion]] (BRVO) and [[central retinal vein occlusion]] (CRVO), OCT quantifies macular edema, identifies cystoid changes, subretinal fluid, and hemorrhage, and monitors treatment response to [[anti-VEGF]] therapy. OCTA delineates areas of capillary non-perfusion and collateral vessel formation.

#### Vitreomacular Interface Disorders

OCT is the definitive diagnostic tool for:

- **[[Vitreomacular traction]]** (VMT): Partial [[posterior vitreous detachment]] with persistent attachment and traction at the fovea, causing distortion of the foveal contour.
- **[[Epiretinal membrane]]** (ERM): Hyperreflective membrane on the inner retinal surface causing wrinkling and thickening of the underlying retina.
- **[[Macular hole]]**: Full-thickness defect in the foveal neurosensory retina. OCT classifies macular holes by stage (Gass classification), measures minimum hole diameter and base diameter, and identifies prognostic features such as the hole form factor and presence of an operculum.
- **[[Lamellar macular hole]]**: Partial-thickness foveal defect with irregular foveal contour but intact photoreceptor layer.

#### Central Serous Chorioretinopathy (CSC)

OCT reveals [[neurosensory retinal detachment]] (dome-shaped elevation of the neurosensory retina with optically clear subretinal fluid), [[pigment epithelial detachment]], and in chronic cases, RPE atrophy and outer retinal thinning. EDI-OCT or SS-OCT demonstrates characteristic **[[pachychoroid]]** (increased choroidal thickness, often >400 µm) with dilated Haller layer vessels ([[pachyvessels]]).

### Glaucoma

OCT has become an indispensable tool in the diagnosis and management of [[glaucoma]], providing objective, quantitative assessment of structural damage to the [[optic nerve head]] (ONH), [[retinal nerve fiber layer]] (RNFL), and [[ganglion cell complex]] (GCC)/[[ganglion cell-inner plexiform layer]] (GCIPL).

#### RNFL Analysis

OCT measures peripapillary RNFL thickness in a circular scan around the optic disc, generating a TSNIT (temporal-superior-nasal-inferior-temporal) profile. RNFL thinning, particularly in the inferior and superior quadrants, is a hallmark of glaucomatous damage. Results are compared to age-matched normative databases and displayed using color-coded probability maps (green = normal, yellow = borderline, red = abnormal).

#### Ganglion Cell Analysis

Macular ganglion cell analysis (e.g., Cirrus GCA, Spectralis Posterior Pole Asymmetry Analysis) measures the thickness of the GCIPL in the macular region. Because approximately 50% of all [[retinal ganglion cells]] reside within the macula, macular GCIPL thinning can detect early glaucomatous damage, sometimes before detectable RNFL loss. Asymmetry analysis between hemispheres and between eyes enhances diagnostic sensitivity.

#### Optic Nerve Head Analysis

OCT provides quantitative measurements of the [[optic disc]], [[neuroretinal rim]], and [[optic cup]], including:

- Disc area
- Rim area
- Cup-to-disc ratio (C/D ratio)
- Cup volume
- **Bruch's membrane opening–minimum rim width (BMO-MRW)**: A newer parameter that measures the minimum distance from [[Bruch's membrane opening]] to the ILM, providing a more anatomically accurate assessment of neuroretinal rim tissue than traditional planimetric measurements.

#### OCTA in Glaucoma

OCTA demonstrates reduced peripapillary and macular vessel density in glaucomatous eyes, correlating with RNFL and GCIPL thinning. While not yet a standalone diagnostic tool, OCTA provides complementary vascular information that may enhance understanding of glaucoma pathophysiology and improve early detection.

#### Progression Analysis

Serial OCT measurements enable detection of progressive structural loss over time using guided progression analysis (GPA) and trend-based analysis. Event-based analysis flags statistically significant change from baseline, while trend-based analysis calculates rates of RNFL or GCIPL thinning (µm/year). Rates exceeding age-related decline (approximately 0.5–1.0 µm/year for RNFL) suggest pathological progression.

### Anterior Segment OCT (AS-OCT)

Anterior segment OCT (AS-OCT) extends the utility of OCT beyond the posterior segment. Using longer wavelengths (typically 1310 nm) or adapted SD-OCT systems, AS-OCT provides high-resolution cross-sectional imaging of:

- **[[Cornea]]**: Measurement of [[corneal thickness]] ([[pachymetry]]), evaluation of [[corneal ectasia]] (e.g., [[keratoconus]]), [[corneal scars]], [[Descemet membrane detachment]], [[corneal dystrophies]], and post-surgical changes (e.g., [[LASIK]] flap assessment, [[DMEK]]/[[DSAEK]] graft adherence).
- **[[Anterior chamber angle]]**: Assessment of angle anatomy for [[angle-closure glaucoma]] screening, measurement of angle opening distance (AOD), trabecular-iris space area (TISA), and identification of [[plateau iris]] configuration.
- **[[Iris]]**: Evaluation of [[iris cysts]], [[iris tumors]], and iris configuration.
- **[[Crystalline lens]] and [[intraocular lens]] (IOL)**: Assessment of lens position, IOL centration, and vault measurement in [[phakic IOL]] implantation (e.g., [[ICL]]).
- **[[Filtering blebs]]**: Post-[[trabeculectomy]] bleb morphology assessment.

---

## Interpretation and Artifacts

### Key Principles of OCT Interpretation

Accurate OCT interpretation requires systematic evaluation of:

1. **Signal strength/quality**: Low signal (due to [[media opacities]], poor fixation, dry [[cornea]], or small [[pupil]]) can produce unreliable measurements and mimic pathology.
2. **Segmentation accuracy**: Automated segmentation algorithms delineate retinal layer boundaries. Errors are common in eyes with significant pathology (e.g., large drusen, epiretinal membranes, macular holes) and must be identified and corrected manually when possible.
3. **Scan centration**: Decentered scans can produce artifactual asymmetry in RNFL and GCIPL thickness maps.
4. **Normative database applicability**: Normative databases may not adequately represent all ethnicities, high [[myopia]], or [[optic disc]] anomalies (e.g., [[tilted disc]], [[optic disc drusen]]).

### Common OCT Artifacts

| **Artifact** | **Cause** | **Clinical Impact** |
|---|---|---|
| **Segmentation error** | Pathology disrupting layer boundaries | Inaccurate thickness measurements; false positives/negatives |
| **Motion artifact** | Patient movement during acquisition | Discontinuities in B-scans; misregistration |
| **Mirror artifact** | Image inversion when tissue crosses zero-delay line | Inverted image superimposed on true image |
| **Projection artifact** (OCTA) | Superficial vessel shadows projected onto deeper layers | False flow signal in deep layers |
| **Signal attenuation** | Media opacity, vitreous hemorrhage | Reduced image quality; unreliable measurements |
| **Decentration artifact** | Off-center scan placement | Asymmetric thickness maps mimicking pathology |
| **Blink artifact** | Eyelid interruption during scan | Horizontal black lines across B-scan |

---

## Role in Treatment Monitoring and Clinical Decision-Making

OCT is not merely a diagnostic tool but serves as the primary instrument for **treatment monitoring** and **clinical decision-making** in numerous conditions:

- **Anti-VEGF therapy for wet AMD and DME**: Treatment decisions (injection, observation, extension of treatment interval) are predominantly guided by OCT findings—specifically the presence or absence of intraretinal fluid, subretinal fluid, and changes in PED height. Major clinical trials (CATT, HARBOR, VIEW, Protocol T) have established OCT-guided treatment paradigms.
- **Glaucoma management**: OCT progression analysis informs decisions regarding escalation of [[intraocular pressure]]-lowering therapy, addition of medications, [[selective laser trabeculoplasty]] (SLT), or surgical intervention.
- **Post-surgical monitoring**: OCT monitors outcomes following [[vitrectomy]] (e.g., macular hole closure, ERM peeling), [[cataract surgery]] (e.g., [[cystoid macular edema]]), [[corneal transplantation]], and [[glaucoma surgery]].
- **Clinical trials**: OCT serves as a primary or secondary endpoint in virtually all retinal and glaucoma clinical trials, providing objective, reproducible structural outcome measures.

---

## Emerging Technologies and Future Directions

### Adaptive Optics OCT (AO-OCT)

**[[Adaptive optics]]** OCT combines OCT with adaptive optics wavefront correction to achieve cellular-level resolution, enabling visualization of individual [[cone photoreceptors]], [[rod photoreceptors]], [[retinal ganglion cells]], and [[RPE cells]]. While primarily a research tool, AO-OCT holds promise for ultra-early detection of photoreceptor loss in conditions such as [[retinitis pigmentosa]] and [[Stargardt disease]].

### Intraoperative OCT (iOCT)

**Intraoperative OCT** integrates OCT imaging into the surgical microscope, providing real-time cross-sectional imaging during vitreoretinal and anterior segment surgery. iOCT has been shown to alter surgical decision-making in a significant proportion of cases, particularly during [[macular hole]] surgery, [[epiretinal membrane]] peeling, and [[DMEK]]/[[DSAEK]] procedures (DISCOVER and PIONEER studies).

### Artificial Intelligence and Deep Learning

**[[Artificial intelligence]]** (AI) and **[[deep learning]]** algorithms are being increasingly applied to OCT data for:

- Automated detection and classification of retinal pathology (e.g., AMD, DME, glaucoma)
- Improved segmentation accuracy
- Predictive modeling of disease progression and treatment response
- Screening applications in primary care and telemedicine settings

Notable AI-OCT systems include IDx-DR (now Digital Diagnostics) for diabetic retinopathy screening and various deep learning models for AMD fluid detection that have demonstrated performance comparable to expert retinal specialists.

### Visible-Light OCT (vis-OCT)

Visible-light OCT uses shorter wavelengths (500–600 nm) to achieve ultra-high axial resolution (<2 µm) and enables **retinal oximetry**—measurement of blood oxygen saturation—providing both structural and metabolic information.

### Full-Field OCT and Polarization-Sensitive OCT

- **Full-field OCT (FF-OCT)**: Acquires en face images at a single depth, achieving isotropic ultra-high resolution approaching that of histology.
- **[[Polarization-sensitive OCT]] (PS-OCT)**: Measures tissue birefringence, enabling characterization of the RNFL (which is birefringent due to microtubule organization), RPE depigmentation, and fibrosis.

---

## Clinical Protocols and Practical Considerations

### Patient Preparation

- **[[Pupil dilation]]**: While many modern OCT systems can image through undilated pupils, dilation (typically with [[tropicamide]] 1% and/or [[phenylephrine]] 2.5%) improves signal quality, reduces artifacts, and enables wider field imaging.
- **Fixation**: Patients should fixate on the internal fixation target. Poor fixation (e.g., in patients with central [[scotoma]]) may require external fixation targets or manual scan placement.
- **Tear film**: A stable [[tear film]] is essential for optimal image quality. Artificial tears should be instilled if the corneal surface is dry.

### Scan Protocols

| **Scan Type** | **Application** |
|---|---|
| **Macular cube** (e.g., 512 × 128, 200 × 200) | Macular thickness mapping, GCL analysis, volumetric assessment |
| **Radial lines** (6 or 12 high-density radial B-scans through fovea) | Detailed foveal morphology, macular hole measurement |
| **Raster/line scan** (single or averaged B-scans) | High-resolution cross-sectional imaging of specific lesions |
| **Optic disc cube** (e.g., 200 × 200) | ONH analysis, RNFL thickness, C/D ratio |
| **Peripapillary circle scan** (3.46 mm diameter) | RNFL thickness profile (TSNIT) |
| **Anterior segment scan** | Corneal pachymetry, angle assessment, IOL evaluation |
| **OCTA scan** (e.g., 3×3 mm, 6×6 mm, 12×12 mm) | Retinal and choroidal vascular imaging |

### Frequency of OCT Monitoring

The frequency of OCT imaging depends on the clinical context:

- **Wet AMD on anti-VEGF therapy**: Every 4–12 weeks depending on treatment regimen (monthly, treat-and-extend, PRN)
- **DME on treatment**: Every 4–8 weeks during loading phase; extended intervals during maintenance
- **Glaucoma**: Every 6–12 months for stable patients; more frequently if progression is suspected
- **Post-operative monitoring**: Variable; often at 1 day, 1 week, 1 month, and 3 months post-surgery

---

## Limitations

Despite its transformative impact, OCT has several important limitations:

1. **Media opacities**: Dense [[cataracts]], [[vitreous hemorrhage]], and [[corneal edema]] can significantly degrade image quality, though SS-OCT partially mitigates this limitation.
2. **Cooperation-dependent**: Requires patient fixation and relative stillness; challenging in pediatric patients, patients with [[nystagmus]], or those with cognitive impairment.
3. **Structural, not functional**: OCT measures structure, not visual function. Structural changes may precede or lag behind functional changes. Correlation with [[visual field testing]], [[visual acuity]], and other functional measures remains essential.
4. **Floor effect**: In advanced glaucoma, RNFL thickness reaches a measurement floor (residual thickness of non-neural tissue ~40–50 µm), limiting the ability to detect further progression.
5. **Normative database limitations**: May not be representative for all populations, particularly those with high [[axial myopia]], [[optic disc]] anomalies, or certain ethnic groups.
6. **Cost and accessibility**: While increasingly widespread, OCT remains a significant capital investment and may not be available in all clinical settings, particularly in resource-limited environments.

---

## Summary

Optical Coherence Tomography has revolutionized the practice of [[optometry]] and [[ophthalmology]], providing non-invasive, high-resolution, quantitative imaging of ocular structures that was previously obtainable only through histological examination. From its origins in TD-OCT to the current era of SS-OCT, OCTA, and AI-enhanced analysis, OCT continues to evolve at a remarkable pace. Its applications span the full breadth of ocular disease—from [[glaucoma]] and [[age-related macular degeneration]] to [[diabetic retinopathy]], [[vitreomacular interface disorders]], and [[anterior segment]] pathology. For the modern eye care practitioner, proficiency in OCT acquisition, interpretation, and clinical application is not merely advantageous—it is essential.

---

## References

1. Huang D, Swanson EA, Lin CP, et al. Optical coherence tomography. *Science*. 1991;254(5035):1178-1181. doi:10.1126/science.1957169. [https://pubmed.ncbi.nlm.nih.gov/1957169/](https://pubmed.ncbi.nlm.nih.gov/1957169/)

2. Drexler W, Fujimoto JG. *Optical Coherence Tomography: Technology and Applications*. 2nd ed. Springer; 2015. [https://link.springer.com/book/10.1007/978-3-319-06419-2](https://link.springer.com/book/10.1007/978-3-319-06419-2)

3. Spaide RF, Koizumi H, Pozonni MC. Enhanced depth imaging spectral-domain optical coherence tomography. *Am J Ophthalmol*. 2008;146(4):496-500. doi:10.1016/j.ajo.2008.05.032. [https://pubmed.ncbi.nlm.nih.gov/18639219/](https://pubmed.ncbi.nlm.nih.gov/18639219/)

4. Jia Y, Tan O, Tokayer J, et al. Split-spectrum amplitude-decorrelation angiography with optical coherence tomography. *Opt Express*. 2012;20(4):4710-4725. doi:10.1364/OE.20.004710. [https://pubmed.ncbi.nlm.nih.gov/22418228/](https://pubmed.ncbi.nlm.nih.gov/22418228/)

5. Staurenghi G, Sadda S, Chakravarthy U, Spaide RF; International Nomenclature for Optical Coherence Tomography (IN•OCT) Panel. Proposed lexicon for anatomic landmarks in normal posterior segment spectral-domain optical coherence tomography. *Ophthalmology*. 2014;121(8):1572-1578. doi:10.1016/j.ophtha.2014.02.023. [https://pubmed.ncbi.nlm.nih.gov/24755005/](https://pubmed.ncbi.nlm.nih.gov/24755005/)

6. Bussel II, Wollstein G, Schuman JS. OCT for glaucoma diagnosis, screening and detection of glaucoma progression. *Br J Ophthalmol*. 2014;98(Suppl 2):ii15-ii19. doi:10.1136/bjophthalmol-2013-304326. [https://pubmed.ncbi.nlm.nih.gov/24357497/](https://pubmed.ncbi.nlm.nih.gov/24357497/)

7. Comparison of Age-related Macular Degeneration Treatments Trials (CATT) Research Group. Ranibizumab and bevacizumab for neovascular age-related macular degeneration. *N Engl J Med*. 2011;364(20):1897-1908. doi:10.1056/NEJMoa1102673. [https://pubmed.ncbi.nlm.nih.gov/21526923/](https://pubmed.ncbi.nlm.nih.gov/21526923/)

8. Diabetic Retinopathy Clinical Research Network. Aflibercept, bevacizumab, or ranibizumab for diabetic macular edema (Protocol T). *N Engl J Med*. 2015;372(13):1193-1203. doi:10.1056/NEJMoa1414264. [https://pubmed.ncbi.nlm.nih.gov/25692915/](https://pubmed.ncbi.nlm.nih.gov/25692915/)

9. Ehlers JP, Dupps WJ, Kaiser PK, et al. The Prospective Intraoperative and Perioperative Ophthalmic ImagiNg with Optical CoherEncE TomogRaphy (PIONEER) Study. *Am J Ophthalmol*. 2014;158(5):999-1007. doi:10.1016/j.ajo.2014.07.023. [https://pubmed.ncbi.nlm.nih.gov/25077834/](https://pubmed.ncbi.nlm.nih.gov/25077834/)

10. Ting DSW, Cheung CY, Lim G, et al. Development and validation of a deep learning system for diabetic retinopathy and related eye diseases using retinal images from multiethnic populations with diabetes. *JAMA*. 2017;318(22):2211-2223. doi:10.1001/jama.2017.18152. [https://pubmed.ncbi.nlm.nih.gov/29234807/](https://pubmed.ncbi.nlm.nih.gov/29234807/)

11. Spaide RF, Fujimoto JG, Waheed NK, Sadda SR, Staurenghi G. Optical coherence tomography angiography. *Prog Retin Eye Res*. 2018;64:1-55. doi:10.1016/j.preteyeres.2017.11.003. [https://pubmed.ncbi.nlm.nih.gov/29229445/](https://pubmed.ncbi.nlm.nih.gov/29229445/)

12. Schuman JS, Puliafito CA, Fujimoto JG, Duker JS. *Optical Coherence Tomography of Ocular Diseases*. 4th ed. SLACK Incorporated; 2021.

---

*This article is intended for eye care professionals and students of [[optometry]] and [[ophthalmology]]. Clinical decisions should always be based on comprehensive patient evaluation, and OCT findings should be interpreted in the context of the full clinical picture, including patient history, visual acuity, [[intraocular pressure]], [[slit-lamp examination]], [[dilated fundus examination]], and ancillary testing as indicated.*