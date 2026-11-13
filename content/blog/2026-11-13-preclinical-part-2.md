+++
title = "Preclinical Research, Part 2: Exposure, Safety, and Translation"
date = 2026-11-16T10:00:00
description = "How material identity, achieved exposure, safety findings, and model relevance shape a defensible decision to enter clinical development."
+++

![Evidence about a characterized product follows different routes: exposure and biological response for medicines, physical performance and tissue contact for devices, and measurement and interpretation for diagnostics. Each route reaches a proposed human use through explicit relevance and uncertainty checks; new observations can reopen the inference.](/images/2026-11-13-part-2.png)

**Figure 1. Connecting tested products to proposed human use.** *The evidence needed for translation depends on the product’s action and the decision being made. Material identity, relevant observations, and the limits of extrapolation must remain connected; these illustrative routes can overlap in combination products and do not constitute a readiness score.*

A candidate produces the intended response in a disease model and causes no obvious harm at the doses tested. What would make that evidence sufficient to begin studying it in people? The answer depends on what was administered, what reached the relevant tissue, which hazards the studies could detect, and how the proposed human use differs from the experiment.

Part 1 examined how an experimental response earns a biological interpretation. Morgan and colleagues’ exposure–binding–function framework remains useful here: before interpreting a response or its absence, establish whether the intervention reached the relevant site and adequately tested the intended mechanism. (1)

Part 2 follows the next inference: from a characterized candidate and its exposure to a clinical-entry rationale. Safety emerges from relationships among material, exposure, response, injury, time, and the intended population. A negative result is informative only within the challenge actually delivered and the biology actually represented. A favorable result may justify a next step while leaving substantial uncertainty about longer exposure, different patients, or another formulation.

This is a narrative practitioner guide for scientifically informed readers, rather than a universal development checklist. It develops a common reasoning framework and then shows where proteins, vaccines, anti-infectives, living products, devices, and diagnostics require different evidence. Detailed quality systems and legal applicability belong primarily to Part 3; qualifications needed to understand a candidate remain beside the relevant claims here. FDA guidance recommendations are distinguished from binding statutory or regulatory provisions. ICH texts and WHO or IMDRF recommendations do not by themselves establish identical legal obligations across jurisdictions.

## Begin with the product that will actually be used

A candidate is more than an active-ingredient name. It includes the material’s composition and state, how it is manufactured and stored, its formulation and delivery system, and the intended route and duration. The question is whether findings obtained with one material can support use of another.

Comparability begins with the attributes that could alter the intended action. For a small molecule, examine whether the new material changes dissolution or impurity exposure. For a protein, compare structure and relevant biological functions. For a cell product, assess the state and activity of the cells that will actually be administered. These are product-specific questions, not a demand that every measured difference trigger the same follow-up.

For biotechnology products within its scope, ICH Q5E frames comparability around whether manufacturing changes adversely affect quality, safety, or efficacy. It does not prescribe one analytical, nonclinical, or clinical strategy. Its quality emphasis supports a staged question: what do the analytical and functional comparisons establish, and what consequential uncertainty remains? (2) A manufacturing change does not automatically require an animal study, and an analytically similar profile does not automatically settle a functional difference.

| Product or change | Attribute that can alter the inference | Evidence that must remain distinct |
| --- | --- | --- |
| Small-molecule salt, polymorph, or synthesis change | Dissolution, impurity identity, or achieved exposure | Chemical identity; formulation performance; impurity exposure; systemic and local effects |
| Antibody or fusion-protein process change | Higher-order structure, glycosylation, aggregates, or biological activity | Total protein; target-binding function; effector function; immunogenicity |
| Antibody–drug conjugate | Linker stability and the distribution of payload loading | Conjugated antibody; total antibody; unconjugated payload |
| RNA delivery formulation | Cargo integrity, carrier composition, delivery, and expression | Administered RNA; carrier-related material; intracellular payload; expressed product |
| Cellular product after manufacture or thawing | Identity, viable fraction, subpopulation composition, and potency | Cell count; membrane integrity; functional activity; subsequent persistence |
| Implant or delivery device | Material composition, geometry, surface state, or delivered volume | Engineering performance; chemical release; tissue response; user interaction |

The table identifies attributes to investigate; it does not define release specifications. Select tests according to the material, intended action, and consequences of a meaningful difference.

Material identity must survive preparation and administration. Examine the actual delivery process: does a suspension remain uniform, is protein recovered through the administration set, what fraction of an aerosol reaches its intended location, and how does a depot release its contents over time? The relevant exposure is what was delivered under the study conditions, not simply what was loaded into the device.

The same principle applies to an in vitro assay. Define whether a reported concentration is nominal input, recovered material, or a free concentration near the cells. Part 1 discusses device and medium interactions as characterization questions. Use measurements appropriate to the system instead of assuming that increasing the nominal input proportionately increases active exposure.

## Establish what the exposure measurement represents

**Pharmacokinetics (PK)** describes the time course of a specified entity in a specified compartment. **Toxicokinetics (TK)** supplies exposure information in or alongside toxicity studies so that findings can be interpreted in relation to systemic exposure. ICH S3A explicitly connects that information with toxicological interpretation and clinical safety questions for human pharmaceuticals. (3) A stated dose in milligrams per kilogram and a concentration profile answer different questions.

The analyte definition comes first. Measuring total antibody cannot automatically establish the trajectory of an attached cytotoxic payload. A vector-genome signal does not establish expression of the intended protein. Human DNA in a tissue does not establish viable therapeutic cells. A model can interpret a measurement only after its biological object has been defined.

### Separate analytical performance from sampling and interpretation

A concentration estimate depends on calibration, selectivity, matrix effects, stability, and processing. A metabolite that converts back to parent after collection can make the measured parent concentration partly an ex vivo product. FDA’s November 2022 M10 guidance addresses bioanalytical measurements supporting regulatory submissions, including chromatographic and ligand-binding methods. Its scope and handling requirements should be applied to the particular analyte and study; it is not a universal specification for discovery readouts. (4)

**Incurred sample reanalysis (ISR)** tests repeatability in authentic study specimens, which may behave differently from spiked quality controls. M10 calculates repeat–initial percentage differences using their pair mean. At least two-thirds of repeat results should fall within ±20% for chromatographic methods or ±30% for ligand-binding methods. Overall failure or systematic patterns warrant investigation; ISR values do not replace the original study values. (4) These are scoped analytical criteria, rather than evidence of biological relevance or a license to disregard a directional failure.

Sampling determines a different layer of uncertainty. Serial observations from an individual can describe an individual trajectory. A composite curve formed from different animals at different times is a group-level construction. It cannot be presented as though every animal experienced that observed curve.

The area under the concentration–time curve (**AUC**) summarizes exposure over a stated interval; **Cmax** is the peak concentration. Nedelman, Gibiansky, and Lau describe an approach to AUC uncertainty for sparse sampling. (5) The general planning issue is whether the design supports the intended individual or group-level estimate. Microsampling may enable serial profiles, but reduced specimen volume alone does not establish sufficient timing, assay validity, or complete individual data.

| Exposure statement | What it can mean | Additional information needed |
| --- | --- | --- |
| “Below quantification” | The result lies outside a validated quantitative range | Original bound/flag; assay sensitivity; a justified treatment in analysis |
| “AUC increased” | Greater integrated concentration over the stated interval | Analyte, matrix, interval, units, sampling, and uncertainty |
| “Cmax increased” | A higher observed or estimated peak | Sampling around the peak; measured versus modeled value; free versus total basis |
| “Tissue accumulation” | More measured material in the sampled tissue | Parent versus metabolite or label; extracellular versus intracellular location; persistence and function |
| “No late toxicity” | No specified finding in the observed window | Sustained relevant exposure, endpoint sensitivity, latency, and loss of exposed cells or animals |

These distinctions are an interpretation framework. In particular, preserve a below-quantification result as a bound or flagged observation and justify how it enters the analysis; do not silently turn it into an observed zero.

This separation helps diagnose an apparent contradiction. If efficacy falls during repeated dosing, possibilities include lower exposure, neutralization, altered target abundance, or an insensitive response assay. An exposure assay and an anti-drug-antibody assay can each have interference problems. One favorable analytical result cannot resolve the entire chain.

## Explain why dose and active exposure diverge

Absorption, distribution, metabolism, and excretion—**ADME**—connect administration with the entity available to act. For an oral product, dissolution makes material available in solution, epithelial transport governs entry, and intestinal or hepatic removal can reduce what reaches systemic circulation. Improving one process does not establish that the others are no longer limiting.

Separate absorption from systemic availability. For an oral product, ask how much material enters the gut wall and how much escapes intestinal and hepatic removal. A change in dissolution or uptake does not establish the resulting human exposure without evidence about the remaining processes.

Distribution adds binding, transport, and compartmental access. Total plasma concentration, unbound blood concentration, and intracellular concentration need not follow the same trajectory. A low plasma level may accompany tissue retention; a high total level may coexist with limited free concentration at the target. Apparent distribution volume is a proportionality between body amount and circulating concentration, rather than an anatomical space.

### A clearance model exposes its assumptions

A commonly used well-stirred liver model makes the interaction among blood flow, binding, and intrinsic elimination explicit:

\[
CL_H=\frac{Q_H f_{u,b}CL_{int}}{Q_H+f_{u,b}CL_{int}}.
\]

Here \(CL_H\) is hepatic clearance, \(Q_H\) is hepatic blood flow, \(f_{u,b}\) is the fraction unbound in blood, and \(CL_{int}\) is intrinsic clearance scaled to a compatible whole-organ basis. Flow and the two clearance quantities must share compatible volume/time units; the unbound fraction is dimensionless. An in vitro value per milligram of microsomal protein cannot enter unchanged beside whole-organ blood flow.

The model assumes a well-mixed liver compartment. Its algebra compares \(f_{u,b}CL_{int}\) with \(Q_H\): when the former is much smaller, the expression approaches \(f_{u,b}CL_{int}\); when much larger, it approaches \(Q_H\). These are limiting consequences of the displayed expression. They show why omitting binding from the comparison can be misleading.

Rowland, Benet, and Graham provide the foundational clearance framework. (6) Benet’s later review presents the binding-inclusive equation and its limiting cases. (7) Whole-organ scaling and compatible units are necessary conditions for using this expression; they do not validate a candidate-specific prediction.

A nonlinear dose–exposure curve needs a mechanistic explanation. Ask whether dissolution, transport, elimination, or target-mediated removal could account for it, and which observation would distinguish those alternatives. Curve shape alone does not identify the cause. The modeling section returns to this problem.

### Distinguish metabolite coverage from interaction potential

Metabolism can remove parent, create an active species, or produce a reactive intermediate. “Drug-related material” therefore does not necessarily mean intact active parent. Radioactivity recovery can help describe mass balance, while chemical identification and analyte-specific measurements answer what that recovered material contains.

FDA’s March 2020 Revision 2 of *Safety Testing of Drug Metabolites* addresses human-only or disproportionate human metabolites. Its text identifies greater than 10% of total drug-related exposure at steady state as a general concern level; comparison is usually AUC-based, with justified alternatives. It also recognizes concern below that general plasma criterion and case-specific local toxicity. (8) This is not a universal safe-below threshold. The useful question is whether exposure to the relevant metabolite was represented by the safety studies, rather than whether its name appeared in an animal sample. Specific follow-up still depends on chemical class, indication, patient population, exposure, and duration.

A **drug–drug interaction** asks whether one product changes another’s exposure or response. For PK interactions, FDA’s August 2024 ICH M12 uses **object** for the affected drug and **precipitant** for the interacting agent; victim and perpetrator are older terms. The same candidate can occupy both roles. The scope focuses on enzyme- and transporter-mediated PK interactions, principally small molecules, with brief coverage of monoclonal antibodies and conjugates. It excludes pharmacodynamic (**PD**) interactions and several other PK mechanisms; it is not an all-modality interaction framework. (9)

An inhibition constant, the fraction eliminated through a pathway, and an increase in another drug’s AUC are different quantities. A model-derived intestinal concentration is also different from a measured local concentration. Apply the relevant M12 assessment to the interacting drugs, route, exposure, and intended patient context; a screening calculation is one step in that argument. (9)

## Interpret toxicity through exposure, function, and tissue change

A toxicity study asks what harm can occur under specified conditions. Its answer depends on the material, species, route, duration, achieved exposure, endpoints, and opportunities to observe delayed effects. Calling a study “28-day” says little about whether it supports the intended clinical use without those other fields.

ICH M3(R2) relates nonclinical support to the scope and duration of pharmaceutical clinical trials and marketing applications. FDA’s implementation is dated January 2010. (10) That purpose differs from an industrial-chemical hazard-classification study. A chemical-sector limit dose or testing duration cannot be transferred into a therapeutic program merely because the experiment uses the same species.

General toxicology integrates in-life signs, clinical pathology, TK, gross examination, and microscopic findings. Each layer locates a different part of the problem. Reduced food intake can help explain body-weight change but does not uniquely identify toxicity. An increased relative organ weight can arise partly through its body-weight denominator. A biomarker can precede a visible lesion without establishing that all such signals represent the same tissue process.

### Adversity is a judgment about harm

A treatment-related change and an adverse change are different judgments. Kerlin and colleagues’ Society of Toxicologic Pathology recommendations define adversity in terms of harm to the test animal in the study context. They call for an integrated interpretation across contributing disciplines and for establishing the study NOAEL at the overall-report level. (11) The judgment should explain how severity, function, associated findings, and time course support the conclusion.

The **no-observed-adverse-effect level (NOAEL)** is a tested level interpreted within a particular study. It depends on dose spacing, endpoints, sampling, and the ability to observe an effect. The **lowest-observed-adverse-effect level (LOAEL)** is likewise a tested level, rather than a precisely located biological threshold. A **benchmark dose** is estimated from a defined response and fitted dose–response relationship; its lower confidence bound also depends on the statistical specification.

Recovery adds information about the course of change. It does not erase harm that occurred while an effect was present. Conversely, persistence of a measurable change does not establish that it damaged function. The interpretation needs severity, physiological reserve, progression, and the relationship among observations.

| Finding | Comparison that clarifies its meaning | Conclusion that remains conditional |
| --- | --- | --- |
| Hepatocellular enlargement | Degeneration, necrosis, biochemical injury, pharmacology, and time course | Adaptive hypertrophy under one exposure does not establish absence of every long-term hazard |
| Particle-containing alveolar macrophages | Inflammation, epithelial injury, fibrosis, burden, and clearance | A clearance response cannot be called nonadverse from the cell finding alone |
| A lesion also present in controls | Incidence, severity, dose pattern, and treatment-related exacerbation | A background lesion can still worsen with treatment |
| A lesion that resolves | Functional loss while present and recovery of reserve | Reversibility does not independently decide adversity |
| A statistically significant change | Magnitude, consistency, biological context, and related endpoints | A p value is not a measure of harm |

These comparisons organize an adversity assessment. Kerlin and colleagues support evaluating related pathology and chemistry findings together, considering treatment-related exacerbation of background changes, and distinguishing statistical from biological significance. (11) Each organ-specific conclusion still needs its own evidence.

### A biomarker needs an intended use

Analytical validity concerns how reliably a quantity is measured. Biological interpretation concerns what it means. Clinical utility concerns whether using it improves a decision. Qualification is a separate authority decision for a specified **context of use**. FDA’s overview supports the distinction between biomarkers and direct assessments of how a person feels, functions, or survives, and the context-bound nature of qualification. (12)

Two dated official decisions illustrate why a biomarker name is insufficient:

| Marker and decision | Scope of the decision | Extension not established |
| --- | --- | --- |
| Urinary kidney injury molecule-1 (KIM-1), FDA letter dated 14 April 2008 | Included among markers for voluntary complementary assessment of acute drug-induced nephrotoxicity in rats, with defined tubular/glomerular contexts | Individual human qualification, universal sensitivity, or equivalence to every renal-injury marker (13) |
| Serum glutamate dehydrogenase (GLDH), FDA determination dated 12 November 2025 | Used with standard hepatic markers in clinical-trial participants with muscle-related transaminase elevation when drug-induced liver injury is considered | General-population performance or performance in pre-existing liver disease, which the determination says was not studied (14) |

These dated qualification decisions apply to their specified contexts; qualification of one marker does not extend to another by association. A marker that helps assess injury also does not demonstrate therapeutic benefit.

## Examine vital function and immune mechanisms on their own terms

Structural pathology and functional safety pharmacology overlap but are not interchangeable. A product can alter cardiac conduction, breathing, or neurological function before a visible lesion develops. Conversely, absence of a functional signal during a short observation does not exclude cumulative tissue injury.

FDA’s 2001 S7A guidance generally places cardiovascular, respiratory, and central nervous system function in a core battery before first human administration. Its sections permit scientifically justified exclusions and appropriate incorporation of endpoints into other studies; follow-up is selected for the concern, rather than imposed as a fixed supplementary panel. (15) The comparisons below explain distinct questions, rather than prescribe one package for every product.

For cardiac repolarization, inhibition of the hERG potassium channel, a change in the electrocardiogram’s QT interval, and clinical arrhythmia are different observations. A concentration margin needs a defined free/total basis and denominator. Other currents and delayed effects can alter interpretation. No universal hERG cutoff or computational superiority estimate is established here.

FDA’s October 2026 E14/S7B Q&A R1 is nonbinding guidance. E14 5.1 distinguishes omission of a separate positive control from omission of clinical evidence: high-quality electrocardiogram (ECG) response data commonly covering twice high clinical exposure can suffice; if only high exposure is achieved, justified dose limitations and a low-risk nonclinical assessment are needed. High clinical exposure includes the factor producing the largest increase in steady-state peak concentration at the maximum therapeutic dose. (16)

E14 6.1 instead addresses infeasible conventional assessments and retains alternative clinical ECG evidence. Its additional nonclinical sensitivity expectation—effects comparable to those detectable in dedicated clinical QT studies—does not apply identically before first human dosing or under 5.1. E14 6.3 permits omission of a thorough-QT study for specified unlikely-hERG-interaction modalities unless mechanism or observations suggest proarrhythmic risk. Systemically available conjugate components require separate consideration. These are conditional settings, not a blanket biologic exemption. (16)

Respiratory measurements show a similar endpoint problem. Box-pressure-derived enhanced pause (**Penh**), expiratory flow, pulmonary resistance, and dynamic compliance are different outputs. Hoymann’s review describes Penh as an empirical, timing-dependent variable that can fail to track resistance. It contrasts Penh with head-out midexpiratory flow (EF50), which correlated with resistance in the bronchoconstriction studies reviewed. (17) That comparison is specific to the methods and settings described; restraint, instrumentation, species, and challenge remain relevant.

Neurological follow-up also needs a defined question. General observations, electrographic seizure detection, learned drug cues, and reinforcement do not measure the same property. An absence of visible convulsions is a different observation from absence of electrographic events.

### Separate immune suppression, immunogenicity, and inflammatory syndromes

Immune suppression concerns impaired immune function. Immunogenicity concerns an immune response against the product, including anti-drug antibodies (**ADAs**). Neutralization, changed exposure, immune-complex effects, and hypersensitivity require different observations. S6(R1) supports considering these consequences in interpreting animal studies. (18) A negative ADA assay also depends on drug tolerance: therapeutic protein present in the sample can interfere with detection. FDA’s January 2019 guidance discusses this explicitly for clinical therapeutic-protein assays; it does not formally prescribe development or validation of animal ADA assays. (19) No universal interference correction or assay-performance value follows.

An animal ADA response can explain lost exposure without predicting human ADA incidence. S6(R1), Part II section 4, uses immunogenicity assessment to interpret findings and subsequent study design, including changed PD, unexpected exposure, and immune-mediated reactions. Its discussion of neutralizing activity is conditional on the available PD evidence. (18) A negative long-duration toxicity result is consequently difficult to interpret if sustained pharmacological exposure was lost. This is an interpretability argument, rather than a forecast of human immunogenicity.

TGN1412 provides a more specific source-supported warning. Eastwood and colleagues described CD28 expression on human CD4-positive effector-memory T cells and its absence on the corresponding macaque subset as an explanation for the unexpected human cytokine response. (20) Binding to the species’ target therefore did not establish the same responding-cell system. This bounded explanation does not prove every clinical causal step.

A nominal-dose ratio is not an exposure safety margin. A useful comparison would need relevant PK, responding-cell sensitivity, target occupancy, and signaling context. The TGN1412 example makes the biological relevance of that comparison particularly important. (20)

Cytokine-release syndrome (**CRS**) and immune effector cell-associated neurotoxicity syndrome (**ICANS**) require distinct assessments. A model that reproduces selected systemic inflammatory findings cannot, on that basis alone, be treated as a validated predictor of neurological injury. Define the syndrome, the measured features, and the proposed predictive use before judging model performance.

## Keep delayed and developmental hazards separate

Genetic damage, fixed mutation, tumor formation, and developmental injury occupy different places in a causal sequence. None is a universal substitute for the others.

Genotoxicity testing asks several questions: whether an intervention can cause mutation, chromosome damage, or other DNA damage under the tested conditions. FDA’s S2(R1) guidance addresses the standard battery, interpretation, and follow-up for human pharmaceuticals. (21) Preserve the specific assay endpoint; a negative result in one assay does not answer every genetic-hazard question.

Exposure is part of genetic interpretation. S2(R1) section 4.4 links the value of negative in vivo results to adequate target-tissue exposure, especially after convincing in vitro positives or when no in vitro mammalian assay is used. The guidance permits different kinds of exposure evidence according to the setting. (21) Interpreting those findings is a separate task from deciding how a potentially mutagenic impurity should be controlled in the manufactured product.

Potentially mutagenic impurities require their own identity, exposure, duration, and mechanistic assessment. FDA’s July 2023 M7(R2) text applies to specified pharmaceutical development and change contexts. Its scope excludes, among other categories, biological/biotechnological products, peptides, oligonucleotides, radiopharmaceuticals, and S9 advanced-cancer products. (22) No bulk percentage, generic 1.5-µg/day threshold, or potency-category range is presented as a universal control limit. Daily mass intake and parts per million require different information and cannot be interchanged.

### Ask what a carcinogenicity study would add

Tumor incidence depends partly on survival and the opportunity to observe late tumors. The assessment should explain the handling of survival, cause of death, and background incidence. Historical controls need a justified relationship to the current cohort; a shared strain name alone does not make them interchangeable.

The 2022 S1B(R1) addendum asks whether integrated evidence makes a two-year rat study informative for human carcinogenicity assessment. Target biology, secondary pharmacology, chronic pathology, endocrine effects, genetic toxicology, and immune effects contribute to the argument. Its text distinguishes likely, unlikely, and uncertain human carcinogenic potential in relation to study added value and regulatory consultation. It directs biotechnology-derived products to S6(R1). (23) Omission of a study does not mean absence of a hazard; a positive rodent result also requires a mechanism-specific argument about human relevance.

A relevance argument needs evidence linking the observed lesion to the proposed mechanism in the tested species and then to the human setting. A familiar mechanistic label cannot dismiss a finding for a new compound. The integrated assessment must explain which evidence changes the interpretation. (23)

### Identify the exposed developmental entity and window

Fertility, embryo-fetal development, birth, lactation, and later offspring function require different observation windows. Maternal plasma, placental transfer, fetal tissue, milk, and infant systemic exposure are separate compartments. Maternal toxicity can mediate a developmental effect without proving that every fetal finding is secondary. The dam, litter, and fetus also represent different levels of observation and allocation.

FDA’s May 2021 S5(R3) guidance addresses developmental and reproductive toxicity (**DART**) strategies, exposure margins, alternative assays, and deferral scenarios. It cautions against simply assuming that developmental toxicity is secondary to maternal toxicity; the relationship needs evidence. Comparing litter findings with the dam’s toxicity can inform that judgment. (24) The study design and analysis should preserve the distinct roles of dam, litter, and fetus.

Pediatric development requires another relevance judgment. The youngest intended patient, target ontogeny, duration, adult data, and developing-organ vulnerability can matter more than a generic conversion of animal age to human age. ICH S11 is the identified guidance for pediatric nonclinical safety. The May 2021 final S11 text uses a weight-of-evidence approach to additional investigations and distinguishes small molecules and S6 biotechnology products from excluded product classes such as gene/cell therapies, tissue-engineered products, and vaccines. (25) A juvenile study is not asserted to be routine for every product, and a neural developmental milestone is not treated as a whole-body age equivalence.

Pregnancy, organ impairment, multimorbidity, and frailty can change exposure and susceptibility through different mechanisms. Predicting clearance is only one part of predicting harm. A healthy adult model can be useful while omitting reduced reserve or an immature target system.

## Use quantitative models to expose the missing link

A model is valuable when it makes a proposed translation explicit enough to challenge. It can predict exposure, represent a delayed response, or test the consequences of uncertain inputs. Those roles require different evidence.

| Approach | Question it addresses | Assumption that can change the answer |
| --- | --- | --- |
| Empirical allometry | How might a parameter scale with body size? | Relevant species, parameter, size range, and product-specific biology |
| Physiologically based pharmacokinetic modeling (PBPK) | What concentration–time profile follows from drug properties and physiology? | Binding, metabolism, transport, tissue partitioning, and population inputs |
| In vitro–in vivo correlation (IVIVC) | Does formulation dissolution relate predictively to in vivo input? | Matched formulations and a relevant rate-limiting process |
| Target-mediated drug disposition (TMDD) | Does binding and target-mediated loss alter drug kinetics? | Target abundance, binding, internalization, turnover, and measurable states |
| Turnover or transit model | Why does response lag exposure? | Production/removal dynamics or unobserved maturation stages |
| Quantitative systems pharmacology (QSP) | How do connected biological processes shape an output? | Network structure, parameter recovery, feedback, and validation domain |

The table describes model roles, not a ranking of accuracy. Each implementation needs assumptions, identifiable inputs, and evaluation suited to its intended prediction.

PBPK connects compound properties with system physiology. Specify the population, compartments, binding basis, and transport assumptions used. A prediction for a different patient group needs a rationale for the physiological changes represented, and a tissue prediction needs evidence relevant to that tissue.

FDA’s 2018 PBPK format/content guidance explicitly does not establish methodological best practice or appropriateness for a particular product. Acceptance in place of clinical PK information is case-specific. (26) A simulation that falls within a familiar twofold interval is therefore not automatically acceptable for every intended use. Similarly, FDA’s September 1997 IVIVC guidance concerns oral extended-release products and specific development or change contexts. (27) Correlation for one formulation family does not establish the same relationship for a complex nonoral delivery system.

### Binding can change the exposure being explained

Mager and Jusko describe high-affinity target binding and receptor-mediated removal as a source of nonlinear PK. Their model distinguishes binding from elimination: in their account, apparent clearance decreases with dose when target binding contributes to drug removal. (28) Applying that explanation to a candidate requires evidence about the target and the relevant kinetic processes.

This coupling has practical consequences. If target burden changes between animals and patients, the same amount may not yield the same free-drug trajectory. Gibiansky and colleagues’ theoretical treatment distinguishes rapid quasi-equilibrium (QE) binding from a quasi-steady-state (QSS) approximation that also balances complex internalization. In their notation, \(K_D=k_{off}/k_{on}\), whereas \(K_{SS}=(k_{off}+k_{int})/k_{on}\). The constants approach one another when internalization is small relative to dissociation; they are not generally interchangeable. (29) This is a model-approximation result tested with simulated data, not empirical validation for every biologic. Candidate-specific timescales, observable species, and concentration range still need assessment.

Response can also outlast circulating drug. Dayneka, Garg, and Jusko use simulated indirect-response models to show how altered production or loss of a response variable can delay onset and return to baseline. The response maximum depends on the model and dose. (30) This provides a mechanistic reason to examine the observation window; it does not establish the time course of a new product without supporting data.

### Fitting is different from prediction

Different parameter combinations may fit the same observations. **Structural identifiability** concerns whether the model structure and observable mapping allow parameters to be distinguished; **practical identifiability** also depends on the amount and quality of data. Raue and colleagues’ sections 2.3–4 distinguish structural redundancy from practical non-identifiability, where a likelihood confidence region is unbounded in at least one direction despite a unique minimum. They construct a profile by fixing one parameter and reoptimizing the others. (31) Thus a wide finite interval and non-identifiability are not synonymous in their formulation. A precise-looking fitted estimate is not proof of parameter recovery or prediction beyond the observed setting.

Sensitivity asks how an output changes when inputs change. It does not prove that those inputs are identifiable, that the mechanism is causal, or that the chosen input distributions are appropriate. Uncertainty propagation describes consequences of the uncertainties actually represented; it cannot guarantee coverage of an omitted pathway or a different clinical population. These distinctions matter particularly in large QSP networks where many internal states are not observed.

For mechanistic medical-device simulations, FDA’s November 2023 guidance provides a risk-informed credibility framework for physics-based, mechanistic, or first-principles models. Its sections distinguish implementation verification, independent-data validation, and applicability to the stated context of use. They relate model risk to both the model’s influence on a decision and the consequences of an incorrect decision. Calibration against training observations is not validation under this framework. (32) These are scoped recommendations, not automatic acceptance of a purely data-trained classifier or proof that an experimentally fitted mechanism is causal.

A hypothetical example shows why the distinction changes an experiment. Suppose two candidate models fit plasma concentrations equally well. One predicts substantial target-tissue retention, while the other predicts rapid tissue loss; their efficacy predictions consequently differ. Repeating the same plasma schedule may narrow the fitted curves without separating the models. A well-justified tissue or engagement measurement could address the disputed link. This is a reasoning example, not a reported study or proof that one sampling method will succeed.

## Change the evidence question when the modality changes

A common framework is useful only if it leaves room for different products to act differently. Serum concentration, immune memory, microbial persistence, an edited allele, and mechanical support are not alternative units for one potency score.

### Proteins and conjugates need functional relevance

A pharmacologically relevant animal species needs more than sequence similarity. The S6(R1) text considers binding, expression, and functional activity, and its addendum addresses when one relevant species can be justified. It also explains why a homologous species-specific protein can be useful for hazard detection while differing from the clinical material in manufacturing, impurities, PK, and exact action. (18) A human-target mouse and a human-FcRn mouse address different questions: target pharmacology and IgG handling are not the same humanization.

Antibody architecture adds further variables. A multispecific’s individual arms and intact construct can behave differently. Fc-mediated depletion may be part of the intended mechanism for one product and an unwanted effect for another. Evaluate the intact product and its relevant immune functions.

An antibody–drug conjugate adds separate trajectories for antibody, linker-associated payload, and released cytotoxin. A mean drug-to-antibody ratio (**DAR**) can conceal a distribution of species. In Hamblett and colleagues’ cAC10–MMAE study, purified constructs with two, four, or eight payloads were compared in CD30-positive cell systems and mouse models. Four-loaded and eight-loaded constructs had comparable antitumor activity at equal antibody doses in the reported xenograft comparison, despite greater in vitro potency of the eight-loaded construct; the latter also cleared faster in SCID mice. (33) These are product-, model-, dose-, and schedule-specific findings. They do not identify a platform-independent optimal DAR or establish payload exposure from antibody measurements alone.

The measurement choice follows the question. Intact conjugate helps characterize delivery of the construct; total antibody describes a broader antibody-related pool; unconjugated payload addresses a different systemic exposure. Payload permeability may contribute to effects on neighboring antigen-negative cells, but a co-culture result would need concentrations, cell composition, denominators, and uncertainty before supporting a clinical bystander-effect comparison.

Radiopharmaceuticals add physical decay and dosimetry to the chemical story. Radioactivity per mass, radiochemical purity, tissue time–activity, and absorbed dose are different quantities. Construct stability and radionuclide redistribution can matter separately from target binding. A named dosimetry program does not establish a measured human organ dose or eliminate microdosimetry uncertainty.

### Vaccines separate immune response from protection

Binding antibodies, neutralization, tissue-resident responses, immune memory, reactogenicity, and protection are different endpoints. A high early antibody signal does not establish durable protection at every infection site, and a symptom after vaccination is not a measure of benefit.

WHO’s 2005 nonclinical vaccine guidance distinguishes biological potency from a demonstrated mechanism of human protection. Its sections 2.2 and 3 discuss relevant immune responses and conditional challenge/protection studies, emphasizing model relevance. Section 5.1 treats the antigen–adjuvant formulation and route as consequential; effects with one antigen cannot simply be assigned to another. (34) This historical WHO guidance is not a universal legal challenge-study mandate. No universal protective titer or required mucosal-adjuvant combination is inferred.

Ex vivo restimulation illustrates an important temporal distinction. A cytokine response measured after collected cells are stimulated describes behavior under those assay conditions. It does not, by itself, establish continuously elevated circulating cytokines or persistent acute reactogenicity in the donor. Keep specimen timing, stimulation conditions, and clinical observations separate.

### Anti-infectives connect susceptibility with changing local exposure

An inhibitory concentration measured in culture does not describe the entire infection. Pathogen state, anatomical compartment, host cells, biofilm structure, and the time course of exposure can alter response. Inherited resistance and transient tolerance are different explanations for survival. A carrier-associated tissue concentration is also different from free drug available to the organism.

The hollow-fiber system offers a more specific case. It permits changing drug profiles to be studied while retaining organisms, addressing killing and resistance over time without recreating the whole host. EMA’s 2015 qualification opinion is specifically for the tuberculosis system. Its conclusion describes a complementary tool for anti-TB dose selection and regimen design; it explicitly does not make the system mandatory, pivotal for authorization, or a replacement for other experiments and clinical trials. (35) That decision cannot establish all-pathogen qualification.

The opinion also records retrospective evidence and limitations in the underlying qualification assessment. Its existence should not be converted into universal prospective accuracy. A dynamic culture system, an animal infection, a lung barrier chip, and a clinical disease endpoint can each answer part of the problem; they do not share an interchangeable success metric.

### Living microbes add composition and containment

For a microbial product, identity, community composition, culturability, membrane integrity, stability, and therapeutic potency need separate observations. A colony-forming-unit count describes growth under the chosen culture conditions. A membrane-state-dependent PCR result does not automatically measure the same property, and neither alone establishes restoration of a metabolic or immune function.

FDA’s guidance on live biotherapeutic products (**LBPs**), issued in 2012 and updated in 2016, addresses chemistry, manufacturing, and control (**CMC**) information for early clinical trials under US investigational new drug (**IND**) applications. Its scope excludes products intended as gene-therapy vectors and oncolytic bacteria or viruses. (36) Product identity, manufacturing controls, and potency need to be assessed within the applicable development framework.

For an engineered microbial product, assess persistence, translocation, environmental dissemination, and possible genetic exchange as distinct questions. A containment design must be evaluated under relevant conditions; the design label alone cannot establish that failure is impossible.

## Follow persistence in gene and cell products

For nucleic-acid products, the delivery vehicle, payload, expressed product, and lasting genomic change can have different lifetimes. Disappearance of circulating delivery material does not establish disappearance of expression or an edited allele. Conversely, detection of a vector sequence does not prove integration, functional expression, or injury.

FDA’s final May 2023 S12 guidance specifically addresses gene-therapy biodistribution. Its scope includes products acting through expression of transferred genetic material and ex vivo genetically modified human cells. It is not a blanket framework for every unmodified cell product. (37) Use the final document and its stated scope when planning the biodistribution argument.

Biodistribution, shedding, integration, and transmission are different questions. S12 explicitly places nonclinical shedding evaluation, genomic integration, and germline integration outside its scope and points to separate guidance. (37) A biodistribution result should therefore be interpreted as a result for the measured material and compartment, rather than as a complete assessment of these other outcomes.

Genome editing introduces another separation. Intended sequence change, unintended small variants, larger structural changes, and clone behavior are distinct outcomes. A short-lived editor can leave a permanent change. The January 2024 FDA final guidance concerns human somatic-cell genome-editing products. Its safety section recommends complementary methods, including genome-wide analysis, to reduce off-target-site discovery bias, followed by sensitive verification in relevant cells and assessment of genomic integrity and biological consequences. (38) These are recommendations within the US IND development context, not proof that one assay excludes all damaging edits.

Avoidance of an intended double-strand break does not establish absence of every damaging repair outcome. A sequence-based candidate-site list, a cell-free assay, and confirmation in relevant cells interrogate different conditions; the FDA guidance supports using multiple approaches rather than one discovery route alone. (38) No read-count threshold is treated as a regulatory acceptance rule.

### Living cells change abundance after administration

A cell product can migrate, proliferate, differentiate, lose function, or be cleared. Administered cell number is therefore an input, rather than a complete measure of subsequent exposure. Tracking methods also have different biological objects: DNA-related signal, reporter-associated signal, radiolabel, and viable functional cells are not interchangeable.

Potency concerns activity related to the intended action. FDA’s January 2011 guidance emphasizes product-specific measurements; its assay-matrix discussion permits complementary assays correlated with relevant biological activity when one assay is inadequate. (39) A viable fraction, identity-marker result, and target-cell killing result should not collapse into one number. A matrix does not thereby become a validated clinical surrogate, and this source does not supply common assay choices or release thresholds for all products.

After thawing or a process change, ask whether the administered state preserves the activity relevant to the intended use. Select identity, viability, functional, and stability measurements accordingly. A common viable-percentage cutoff cannot replace a product-specific potency argument. (39)

The hazard assessment should distinguish unwanted persistence, proliferation, differentiation, and inflammatory effects. A marker assay addresses its defined target and detection limit; it cannot answer every tumorigenicity or tissue-formation question. Longer persistence is useful only if the intended activity and control of unwanted cells remain adequately characterized.

Cell-free extracellular vesicles need their own classification. MISEV2023, published in 2024, describes EVs as cell-released, lipid-bilayer-delimited particles that cannot replicate on their own. Its nomenclature section discourages biogenesis-specific labels such as “exosome” without suitable characterization. (40) Small EV and exosome are not synonyms. The May 2024 correction adds an omitted consortium member; it does not revise this nomenclature. These reporting recommendations establish neither efficacy nor safety of an EV product.

## Adapt the chain for devices and diagnostic systems

A physical device may support tissue, deliver a drug, move an instrument, or apply electrical energy. Its function needs engineering evidence under relevant loads, environmental stresses, and use conditions. Its material contact requires a different biological evaluation. Neither branch automatically supplies the other.

Bench tests should address defined failure modes under relevant conditions. Corrosion, fatigue, electrical behavior, and package integrity are different properties. State the test conditions, applicable standard edition, and relationship between the measured property and the proposed use. There is no common “safety margin” unit connecting every engineering result with a toxicological exposure ratio.

FDA’s September 2023 ISO 10993-1 guidance addresses biological evaluation of devices with direct or indirect body contact. Its risk-management passages consider material components, manufacturing, anatomical location, and frequency and duration of contact. (41) This is a contextual assessment, rather than proof of conformity or a mandate to run every test in a matrix. A noncontact software device does not acquire a tissue-contact test obligation from that matrix. A conformance claim requires assessment against the applicable full standard and regulatory framework.

ISO 10993-18:2020 distinguishes laboratory estimation of potential chemical release (**extractables**) from measurement under clinical-use conditions (**leachables**). (42) Exaggerated extraction is one possible approach, not the definition of every extractables study. Interpretation requires the material, extraction or use conditions, analytical method, and exposure scenario. Chemical characterization also leaves separate questions about local tissue response and mechanical performance.

A combination product retains these component questions. A prefilled injector requires evidence about delivered volume and user interaction alongside evidence about the delivered medicine. A cell–scaffold construct adds mechanical persistence and host tissue response to living-product potency and kinetics. Classification or lead-agency assignment does not make one component’s evidence answer the other’s safety question.

### Diagnostics require a measurement-to-decision argument

For an in vitro diagnostic, ask three separate questions: how well does the assay measure the intended quantity in the specimen; how well does the result identify the target condition in the intended population; and what are the consequences of using that result? A lower detection limit addresses only part of this chain. The evaluation must connect measurement performance with the proposed clinical decision.

Digital prediction adds dependence among data records and between settings. IMDRF’s final 2025 GMLP document addresses representative clinical-evaluation datasets, independence of training and test data, fit-for-purpose reference standards, and intended use. Its principles explicitly consider patient-, site-, and acquisition-related dependence and proportionate external validation. (43) These are guiding principles, not an approval of a specific model or a complete jurisdictional legal determination.

A hypothetical imaging example makes the dependence problem concrete. If several scans from one patient are divided between training and testing, apparent disease discrimination may partly reflect shared patient or acquisition features. Keeping that patient’s records together addresses this route of leakage, but still leaves the question of performance at another hospital or on other hardware. It is a conceptual example of the dependence principle, without a claimed performance penalty or benefit.

Human–AI interaction matters as well: IMDRF treats performance in the intended workflow as part of evaluation. (43) An isolated score is not the entire clinical system. Reference-label uncertainty, subgroup performance, and changes after deployment can alter what the output supports. The same observation-versus-inference discipline used for a drug concentration applies to a classifier probability.

## Build a clinical-entry rationale, then plan how it can change

A starting-dose calculation is one element of a clinical-entry argument. The proposed population, product, mechanism, route, duration, relevant species, exposure, and monitoring possibilities determine which calculation is meaningful.

FDA’s July 2005 healthy-adult-volunteer guidance describes deriving a human-equivalent dose (**HED**) from an appropriate animal NOAEL and applying a safety factor to estimate a maximum recommended starting dose (**MRSD**). The text gives 10 as a default factor that may be raised or lowered with justification. It distinguishes the most appropriate species from a default use of the most sensitive species when relevance information is absent. (44)

For the body-surface-area conversion,

\[
\mathrm{HED}\;(\mathrm{mg/kg})=
\mathrm{animal\ dose}\;(\mathrm{mg/kg})
\frac{K_{m,\mathrm{animal}}}{K_{m,\mathrm{human}}}.
\]

Table 1’s factors, based on a 60-kg adult human, include mouse 3, rat 6, dog 20, the listed monkeys 12, and adult human 37; \(K_m\) has units kg/m². The species, reference body weight, and guidance scope all matter. (44)

For illustration, a hypothetical animal NOAEL of 10 mg/kg would give an HED of approximately 5.4 mg/kg using the dog factor (20/37), or 3.2 mg/kg using the listed monkey factor (12/37). These are arithmetic examples before applying a justified safety factor. They are not proposed human starting doses. (44)

EMA’s first-in-human guideline, Revision 1 adopted in July 2017 and effective from February 2018, integrates NOAEL-associated exposure, pharmacological activity, and minimal anticipated biological effect level (**MABEL**) considerations. Its passages connect the choice and safety factors with human relevance, mechanism, duration or irreversibility, and uncertainty. (45) MABEL, intended pharmacological activity, and therapeutic exposure are related but different quantities; no fixed receptor-occupancy percentage is treated as a universally safe starting target.

Advanced cancer is a different benefit–risk context. FDA’s March 2010 S9 guidance concerns advanced disease with limited therapeutic options; its scope excludes cancer prevention, healthy volunteers, vaccines, cell/gene therapies, and radiopharmaceuticals, although some principles may be adaptable for the latter. Section 3.1 integrates PK, PD, and toxicity in starting-dose justification. Its Note 2 describes common small-molecule dose fractions, rather than a universal rule. (46) Cellular products do not acquire a valid starting amount by copying a small-molecule body-size formula.

### Learn from failures without claiming a solved cause

A retrospective mechanistic study can identify a plausible missing link without reconstructing an entire clinical event.

For BIA 10-2474, van Esbroeck and colleagues’ activity-based protein profiling identified off-target lipases and lipid perturbation, while explicitly leaving the cause of clinical neurotoxicity unknown. (47) The study supports an off-target hypothesis, not a completed causal reconstruction. Comparing the clinical event with animal findings would also require matched exposure, endpoints, and observation periods.

Fialuridine illustrates a different bounded observation. In Xu and colleagues’ retrospective humanized-liver TK-NOG comparison, the checked example used 2.5 mg/kg/day for 14 days and six animals per group. The paper described this as approximately ten times the human dose. (48) It does not establish exposure equivalence or general predictive validation of humanized-liver models. Clinical deaths and transplants reported as background in that paper are secondary clinical history, not newly reviewed trial records.

These cases identify different vulnerabilities: responding-cell relevance, off-target selectivity, tissue disposition, or sustained exposure. They have no common denominator from which to rank all models. Their strongest use is to make the next candidate’s relevance argument more specific.

### Align subsequent observation with the product’s persistence

Clinical evidence can revise a starting rationale. Exposure may be nonlinear, activity delayed, or a relevant response sustained after circulating material falls. The learning plan therefore needs to connect emerging PK, PD, and adverse events, rather than treat the first tolerated cohort as the end of translation.

For gene therapies, FDA’s January 2020 long-term follow-up (**LTFU**) guidance provides product-type recommendations within a broader risk assessment. The passage states fifteen years for integrating vectors such as gammaretroviral/lentiviral vectors and transposons, up to fifteen years for genome-editing products, and up to five years for AAV vectors. It also allows risk-based consideration and emphasizes product, disease, and patient characteristics. (49) These are clinical follow-up recommendations at that document’s scope, not animal-study durations or an unconditional AAV ceiling.

Dose-escalation design addresses a separate question: how will accumulating toxicity and activity information change the next decision? The plan should account for when relevant outcomes become observable, especially if activity or harm is delayed. A first tolerated cohort cannot establish the safety of a longer exposure or a higher dose.

## Write the decision at the level the evidence supports

A defensible conclusion is specific enough to be revised. “Ready for clinical development” should be accompanied by the proposed population and use, the evidence supporting that step, the uncertainty that remains, and the observations that would change the judgment.

| Field | Question to answer for the proposed next step |
| --- | --- |
| Product | Does the tested material represent the intended human formulation, process, delivery system, and biological state? |
| Relevant quantity | Which parent, metabolite, conjugate component, vector, cell state, physical property, or diagnostic output matters? |
| Achieved challenge | What exposure or use condition was actually tested, and what was only modeled? |
| Biological relevance | Which target, responding cells, tissues, developmental processes, and host interactions were represented? |
| Harm | Which functional, structural, genetic, immune, developmental, or delayed outcomes were assessed? |
| Negative evidence | What sensitivity, exposure, sampling window, and missing observations constrain an absence claim? |
| Prediction | Were implementation, fitting, parameter recovery, external testing, and extrapolation assessed separately? |
| Modality boundaries | Which product-specific persistence, component, containment, or engineering questions remain? |
| Clinical context | Why is the starting and observation rationale appropriate for this population, disease stage, route, and duration? |
| Source authority | Which exact publications or official versions support the statement and its applicability? |
| Learning | What new result would support advancement, require redesign, or invalidate the current rationale? |

This worksheet is an editorial reasoning aid, rather than a validated score. It makes the links visible without adding them into a numerical readiness total. A justified next step can coexist with uncertainty; the uncertainty must remain attached to the product, observation, and use it constrains.

## Terms used in the guide

| Term | Main explanatory home |
| --- | --- |
| ADME; PK; TK | [Exposure measurement](#establish-what-the-exposure-measurement-represents) and [ADME](#explain-why-dose-and-active-exposure-diverge) |
| ADA; CRS; ICANS | [Immune mechanisms](#separate-immune-suppression-immunogenicity-and-inflammatory-syndromes) |
| NOAEL; LOAEL; benchmark dose | [Adversity](#adversity-is-a-judgment-about-harm) |
| PBPK; IVIVC; TMDD; QSP | [Quantitative models](#use-quantitative-models-to-expose-the-missing-link) |
| DAR; EV | [Proteins and conjugates](#proteins-and-conjugates-need-functional-relevance) and [living cells](#living-cells-change-abundance-after-administration) |
| HED; MRSD; MABEL; LTFU | [Clinical entry](#build-a-clinical-entry-rationale-then-plan-how-it-can-change) |

## Scope and interpretation

This narrative guide explains how product identity, exposure, response, and relevance support a development argument. It is not an exhaustive modality catalog or a candidate-specific study plan. Hypothetical calculations illustrate reasoning rather than recommend doses. Regulatory guidance and professional recommendations apply within their stated product, jurisdiction, version, and context of use.

## Further Reading

- Morgan et al., 2012. [Can the flow of medicines be improved?](https://doi.org/10.1016/j.drudis.2011.12.020) Introduces the exposure–binding–function framework.
- FDA, 2022. [M10 bioanalytical method validation and study sample analysis](https://www.fda.gov/media/162903/download). Connects method validation, study-sample analysis, and authentic study specimens.
- Kerlin et al., 2016. [Recommended practices for determining and using adverse-effect data](https://doi.org/10.1177/0192623315623265). Explains why adversity and a study NOAEL need an integrated rationale.
- ICH, 2011. [S6(R1) preclinical safety evaluation of biotechnology-derived pharmaceuticals](https://database.ich.org/sites/default/files/S6_R1_Guideline_0.pdf). Develops pharmacological relevance and product-specific safety reasoning.
- Mager and Jusko, 2001. [General pharmacokinetic model for target-mediated drug disposition](https://doi.org/10.1023/A:1014414520282). A foundational model for coupling target binding and PK.
- Raue et al., 2009. [Structural and practical identifiability analysis](https://doi.org/10.1093/bioinformatics/btp358). Explains parameter-recovery questions and profile-likelihood analysis.
- FDA, 2022. [S1B(R1) carcinogenicity addendum](https://www.fda.gov/media/152777/download). Frames the added value of a two-year rat study through integrated evidence rather than a checklist alone.
- FDA, 2023. [S12 nonclinical biodistribution considerations for gene therapy products](https://www.fda.gov/media/167605/download). Defines the gene-therapy biodistribution framework; shedding and integration fall outside its scope.
- EMA, 2017. [First-in-human and early clinical-trial risk mitigation, Revision 1](https://www.ema.europa.eu/en/documents/scientific-guideline/guideline-strategies-identify-and-mitigate-risks-first-human-and-early-clinical-trials-investigational-medicinal-products-revision-1_en.pdf). Relates starting exposure and pharmacology to uncertainty in the proposed human use.
- IMDRF, 2025. [Good machine learning practice for medical device development](https://www.imdrf.org/documents/good-machine-learning-practice-medical-device-development-guiding-principles). Extends relevance and independent testing to data-trained devices and their clinical workflows.

## References

1. Morgan P, Van Der Graaf PH, Arrowsmith J, Feltner DE, Drummond KS, Wegner CD, et al. Can the flow of medicines be improved? Fundamental pharmacokinetic and pharmacological principles toward improving Phase II survival. Drug Discov Today. 2012;17(9-10):419-24. doi: [10.1016/j.drudis.2011.12.020](https://doi.org/10.1016/j.drudis.2011.12.020).
2. Food and Drug Administration. Q5E comparability of biotechnological/biological products subject to changes in their manufacturing process: guidance for industry [Internet]. Silver Spring (MD): FDA; 2005 Jun [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/q5e-comparability-biotechnologicalbiological-products-subject-changes-their-manufacturing-process).
3. Food and Drug Administration. S3A toxicokinetics: the assessment of systemic exposure in toxicity studies: guidance for industry [Internet]. Silver Spring (MD): FDA; 1995 Mar [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/s3a-toxicokinetics-assessment-systemic-exposure-toxicity-studies).
4. Food and Drug Administration. M10 bioanalytical method validation and study sample analysis: guidance for industry [Internet]. Silver Spring (MD): FDA; 2022 Nov [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/162903/download).
5. Nedelman JR, Gibiansky E, Lau DT. Applying Bailer's method for AUC confidence intervals to sparse sampling. Pharm Res. 1995;12(1):124-8. doi: [10.1023/A:1016255124336](https://doi.org/10.1023/A:1016255124336).
6. Rowland M, Benet LZ, Graham GG. Clearance concepts in pharmacokinetics. J Pharmacokinet Biopharm. 1973;1(2):123-36. doi: [10.1007/BF01059626](https://doi.org/10.1007/BF01059626).
7. Benet LZ. Clearance (née Rowland) concepts: a downdate and an update. J Pharmacokinet Pharmacodyn. 2010;37(6):529-39. doi: [10.1007/s10928-010-9187-8](https://doi.org/10.1007/s10928-010-9187-8).
8. Food and Drug Administration. Safety testing of drug metabolites. Revision 2: guidance for industry [Internet]. Silver Spring (MD): FDA; 2020 Mar [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/72279/download).
9. Food and Drug Administration. M12 drug interaction studies: guidance for industry [Internet]. Silver Spring (MD): FDA; 2024 Aug [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/m12-drug-interaction-studies).
10. Food and Drug Administration. M3(R2) nonclinical safety studies for the conduct of human clinical trials and marketing authorization for pharmaceuticals: guidance for industry [Internet]. Silver Spring (MD): FDA; 2010 Jan [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/m3r2-nonclinical-safety-studies-conduct-human-clinical-trials-and-marketing-authorization).
11. Kerlin R, Bolon B, Burkhardt J, Francke S, Greaves P, Meador V, et al. Scientific and Regulatory Policy Committee: recommended ("best") practices for determining, communicating, and using adverse effect data from nonclinical studies. Toxicol Pathol. 2016;44(2):147-62. doi: [10.1177/0192623315623265](https://doi.org/10.1177/0192623315623265).
12. Food and Drug Administration. About biomarkers and qualification [Internet]. Silver Spring (MD): FDA; [cited 2026 Oct 28]. Available from: [FDA](https://www.fda.gov/drugs/biomarker-qualification-program/about-biomarkers-and-qualification).
13. Food and Drug Administration. Review submission of the qualification of seven biomarkers of drug-induced nephrotoxicity in rats [Internet]. Silver Spring (MD): FDA; 2008 Apr 14 [cited 2026 Oct 28]. Available from: [Issued letter, recipient-hosted copy](https://c-path.org/wp-content/uploads/2014/09/PSTC-NWG-20080414-FDA-FinalConclusion.pdf).
14. Food and Drug Administration. Drug development tool qualification determination: DDT-BMQ-000050, serum glutamate dehydrogenase [Internet]. Silver Spring (MD): FDA; 2025 Nov 12 [cited 2026 Oct 28]. Available from: [Issued letter, recipient-hosted copy](https://media.c-path.org/wp-content/uploads/20251114184437/Qualification-Determination-Letter_DDT-BMQ-000050-FQP-2-VS.pdf).
15. Food and Drug Administration. S7A safety pharmacology studies for human pharmaceuticals: guidance for industry [Internet]. Silver Spring (MD): FDA; 2001 Jul [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/s7a-safety-pharmacology-studies-human-pharmaceuticals).
16. Food and Drug Administration. E14 and S7B clinical and nonclinical evaluation of QT/QTc interval prolongation and proarrhythmic potential: questions and answers (R1): guidance for industry [Internet]. Silver Spring (MD): FDA; 2026 Oct [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/161198/download).
17. Hoymann HG. Lung function measurements in rodents in safety pharmacology studies. Front Pharmacol. 2012;3:156. doi: [10.3389/fphar.2012.00156](https://doi.org/10.3389/fphar.2012.00156).
18. International Conference on Harmonisation. S6(R1): preclinical safety evaluation of biotechnology-derived pharmaceuticals [Internet]. ICH; 2011 Jun 12 [cited 2026 Nov 4]. Available from: [ICH](https://database.ich.org/sites/default/files/S6_R1_Guideline_0.pdf).
19. Food and Drug Administration. Immunogenicity testing of therapeutic protein products—developing and validating assays for anti-drug antibody detection: guidance for industry [Internet]. Silver Spring (MD): FDA; 2019 Jan [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/119788/download).
20. Eastwood D, Findlay L, Poole S, Bird C, Wadhwa M, Moore M, et al. Monoclonal antibody TGN1412 trial failure explained by species differences in CD28 expression on CD4+ effector memory T-cells. Br J Pharmacol. 2010;161(3):512-26. doi: [10.1111/j.1476-5381.2010.00922.x](https://doi.org/10.1111/j.1476-5381.2010.00922.x).
21. Food and Drug Administration. S2(R1) genotoxicity testing and data interpretation for pharmaceuticals intended for human use: guidance for industry [Internet]. Silver Spring (MD): FDA; 2012 Jun [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/s2r1-genotoxicity-testing-and-data-interpretation-pharmaceuticals-intended-human-use).
22. Food and Drug Administration. M7(R2) assessment and control of DNA reactive (mutagenic) impurities in pharmaceuticals to limit potential carcinogenic risk: guidance for industry [Internet]. Silver Spring (MD): FDA; 2023 Jul [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/guidance-industry-m7r2-assessment-and-control-dna-reactive-mutagenic-impurities-pharmaceuticals).
23. Food and Drug Administration. S1B(R1) addendum to S1B testing for carcinogenicity of pharmaceuticals: guidance for industry [Internet]. Silver Spring (MD): FDA; 2022 Nov [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/152777/download).
24. Food and Drug Administration. S5(R3) detection of reproductive and developmental toxicity for human pharmaceuticals: guidance for industry [Internet]. Silver Spring (MD): FDA; 2021 May [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/s5r3-detection-reproductive-and-developmental-toxicity-human-pharmaceuticals).
25. Food and Drug Administration. S11 nonclinical safety testing in support of development of pediatric pharmaceuticals: guidance for industry [Internet]. Silver Spring (MD): FDA; 2021 May [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/148478/download).
26. Food and Drug Administration. Physiologically based pharmacokinetic analyses: format and content: guidance for industry [Internet]. Silver Spring (MD): FDA; 2018 Aug [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/101469/download).
27. Food and Drug Administration. Extended release oral dosage forms: development, evaluation, and application of in vitro/in vivo correlations: guidance for industry [Internet]. Silver Spring (MD): FDA; 1997 Sep [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/extended-release-oral-dosage-forms-development-evaluation-and-application-vitroin-in-vivo-correlations).
28. Mager DE, Jusko WJ. General pharmacokinetic model for drugs exhibiting target-mediated drug disposition. J Pharmacokinet Pharmacodyn. 2001;28(6):507-32. doi: [10.1023/A:1014414520282](https://doi.org/10.1023/A:1014414520282).
29. Gibiansky L, Gibiansky E, Kakkar T, Ma P. Approximations of the target-mediated drug disposition model and identifiability of model parameters. J Pharmacokinet Pharmacodyn. 2008;35(5):573-91. doi: [10.1007/s10928-008-9102-8](https://doi.org/10.1007/s10928-008-9102-8).
30. Dayneka NL, Garg V, Jusko WJ. Comparison of four basic models of indirect pharmacodynamic responses. J Pharmacokinet Biopharm. 1993;21(4):457-78. doi: [10.1007/BF01061691](https://doi.org/10.1007/BF01061691).
31. Raue A, Kreutz C, Maiwald T, Bachmann J, Schilling M, Klingmüller U, et al. Structural and practical identifiability analysis of partially observed dynamical models by exploiting the profile likelihood. Bioinformatics. 2009;25(15):1923-9. doi: [10.1093/bioinformatics/btp358](https://doi.org/10.1093/bioinformatics/btp358).
32. Food and Drug Administration. Assessing the credibility of computational modeling and simulation in medical device submissions: guidance for industry [Internet]. Silver Spring (MD): FDA; 2023 Nov [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/assessing-credibility-computational-modeling-and-simulation-medical-device-submissions).
33. Hamblett KJ, Senter PD, Chace DF, Sun MMC, Lenox J, Cerveny CG, et al. Effects of drug loading on the antitumor activity of a monoclonal antibody drug conjugate. Clin Cancer Res. 2004;10(20):7063-70. doi: [10.1158/1078-0432.CCR-04-0789](https://doi.org/10.1158/1078-0432.CCR-04-0789).
34. World Health Organization. WHO guidelines on nonclinical evaluation of vaccines. In: WHO Expert Committee on Biological Standardization: fifty-fourth report. Geneva: WHO; 2005. Annex 1. WHO Technical Report Series; No. 927. Available from: [WHO](https://www.who.int/publications/m/item/nonclinical-evaluation-of-vaccines-annex-1-trs-no-927).
35. European Medicines Agency. Qualification opinion: in vitro hollow fibre system model of tuberculosis (HFS-TB) [Internet]. EMA/CHMP/SAWP/47290/2015 Corr. London: EMA; 2015 [cited 2026 Nov 4]. Available from: [EMA](https://www.ema.europa.eu/en/documents/regulatory-procedural-guideline/qualification-opinion-vitro-hollow-fibre-system-model-tuberculosis-hfs-tb_en.pdf).
36. Food and Drug Administration. Early clinical trials with live biotherapeutic products: chemistry, manufacturing, and control information: guidance for industry [Internet]. Silver Spring (MD): FDA; 2012 Feb [updated 2016 Jun] [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/early-clinical-trials-live-biotherapeutic-products-chemistry-manufacturing-and-control-information).
37. Food and Drug Administration. S12 nonclinical biodistribution considerations for gene therapy products: guidance for industry [Internet]. Silver Spring (MD): FDA; 2023 May [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/167605/download).
38. Food and Drug Administration. Human gene therapy products incorporating human genome editing: guidance for industry [Internet]. Silver Spring (MD): FDA; 2024 Jan [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/human-gene-therapy-products-incorporating-human-genome-editing).
39. Food and Drug Administration. Potency tests for cellular and gene therapy products: guidance for industry [Internet]. Silver Spring (MD): FDA; 2011 Jan [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/potency-tests-cellular-and-gene-therapy-products).
40. Welsh JA, Goberdhan DCI, O'Driscoll L, Buzas EI, Blenkiron C, Bussolati B, et al. Minimal information for studies of extracellular vesicles (MISEV2023): from basic to advanced approaches. J Extracell Vesicles. 2024;13(2):e12404. doi: [10.1002/jev2.12404](https://doi.org/10.1002/jev2.12404). Correction in: J Extracell Vesicles. 2024;13(5):e12451. doi: [10.1002/jev2.12451](https://doi.org/10.1002/jev2.12451).
41. Food and Drug Administration. Use of International Standard ISO 10993-1, biological evaluation of medical devices — Part 1: evaluation and testing within a risk management process: guidance for industry [Internet]. Silver Spring (MD): FDA; 2023 Sep [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/use-international-standard-iso-10993-1-biological-evaluation-medical-devices-part-1-evaluation-and).
42. International Organization for Standardization. ISO 10993-18:2020: biological evaluation of medical devices—Part 18: chemical characterization of medical device materials within a risk management process [Internet]. 2nd ed. Geneva: ISO; 2020 [cited 2026 Nov 4]. Available from: [ISO official abstract and amendment record](https://committee.iso.org/cms/live/live/en/sites/isoorg/contents/data/standard/06/47/64750.html).
43. International Medical Device Regulators Forum. Good machine learning practice for medical device development: guiding principles [Internet]. IMDRF/AIML WG/N88 FINAL:2025. IMDRF; 2025 Jan [cited 2026 Nov 4]. Available from: [IMDRF](https://www.imdrf.org/documents/good-machine-learning-practice-medical-device-development-guiding-principles).
44. Food and Drug Administration. Estimating the maximum safe starting dose in initial clinical trials for therapeutics in adult healthy volunteers: guidance for industry [Internet]. Silver Spring (MD): FDA; 2005 Jul [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/72309/download).
45. European Medicines Agency. Guideline on strategies to identify and mitigate risks for first-in-human and early clinical trials with investigational medicinal products. Revision 1 [Internet]. EMEA/CHMP/SWP/28367/07 Rev. 1. London: EMA; 2017 Jul 20 [cited 2026 Nov 4]. Available from: [EMA](https://www.ema.europa.eu/en/documents/scientific-guideline/guideline-strategies-identify-and-mitigate-risks-first-human-and-early-clinical-trials-investigational-medicinal-products-revision-1_en.pdf).
46. Food and Drug Administration. S9 nonclinical evaluation for anticancer pharmaceuticals: guidance for industry [Internet]. Silver Spring (MD): FDA; 2010 Mar [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/s9-nonclinical-evaluation-anticancer-pharmaceuticals).
47. van Esbroeck ACM, Janssen APA, Cognetta AB 3rd, Ogasawara D, Shpak G, van der Kroeg M, et al. Activity-based protein profiling reveals off-target proteins of the FAAH inhibitor BIA 10-2474. Science. 2017;356(6342):1084-7. doi: [10.1126/science.aaf7497](https://doi.org/10.1126/science.aaf7497).
48. Xu D, Nishimura T, Nishimura S, Zhang H, Zheng M, Guo YY, et al. Fialuridine induces acute liver failure in chimeric TK-NOG mice: a model for detecting hepatic drug toxicity prior to human testing. PLoS Med. 2014;11(4):e1001628. doi: [10.1371/journal.pmed.1001628](https://doi.org/10.1371/journal.pmed.1001628).
49. Food and Drug Administration. Long term follow-up after administration of human gene therapy products: guidance for industry [Internet]. Silver Spring (MD): FDA; 2020 Jan [cited 2026 Nov 4]. Available from: [FDA](https://www.fda.gov/media/113768/download).
