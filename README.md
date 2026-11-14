# Responsible AI — Companion Python Laboratory Notebooks

**A collection of 159 hands-on Jupyter/Google Colab notebooks, provided as 15 chapter ZIP archives, accompanying the textbook *Responsible AI*.**

**Repository:** [https://github.com/ParthaPRay/Responsible-AI-Codebook](https://github.com/ParthaPRay/Responsible-AI-Codebook)

**Creator and copyright holder:** **Partha Pratim Ray**  
**Coverage:** 15 chapters · **159 notebooks** · Python 3 · Google Colab / Jupyter Notebook  
**Primary purpose:** Academic teaching, guided laboratory exercises, reproducible demonstrations, and independent student practice.

> **Important:** The notebooks demonstrate concepts and methods; they do not certify that any AI system is fair, safe, secure, privacy-preserving, legally compliant, or ethically acceptable. Simulated results should never be reported as findings about real individuals or institutions.

## About this repository

This repository contains practical programming exercises that complement the concepts, equations, examples, and governance considerations developed across the 15 chapters of *Responsible AI*. It moves from the foundations of AI and ethical reasoning to data governance, bias and fairness, explainability, privacy, security, safety, accountability, risk management, global law and governance, and generative/agentic AI.

The material is designed so that a student can run **one notebook at a time**, inspect numerical outputs, tables, and figures, change assumptions, and explain what the results do—and do **not**—establish. Exercises frequently include synthetic or hypothetical scenarios, alongside self-contained examples based on datasets bundled with standard Python packages.

### Notebook design

Every notebook follows a consistent **two-cell format**:

1. **Markdown cell:** Chapter/laboratory title, creator credit, objective, short procedure, student exercise, and relevant cautions.
2. **Python code cell:** A complete, self-contained experiment that can be executed independently.

Where applicable, the code produces **600-DPI PNG visualisations**, evaluation tables, CSV records, and JSON summaries. Output files are generated **when the notebooks are run**; they need not be stored in the repository.

## Chapter index

| Chapter | Subject | Labs | Download ZIP |
|---:|---|---:|---|
| 1 | Artificial Intelligence as a Socio-Technical System | 10 | [`Chapter_1_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_1_Notebooks.zip) |
| 2 | Ethics, Human Rights and Moral Reasoning | 10 | [`Chapter_2_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_2_Notebooks.zip) |
| 3 | Human Values, Power and Responsible Design | 10 | [`Chapter_3_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_3_Notebooks.zip) |
| 4 | Responsible Data and Dataset Governance | 11 | [`Chapter_4_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_4_Notebooks.zip) |
| 5 | Bias and Harm | 11 | [`Chapter_5_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_5_Notebooks.zip) |
| 6 | Fairness in Machine Learning | 11 | [`Chapter_6_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_6_Notebooks.zip) |
| 7 | Transparency, Interpretability and Explainable AI | 11 | [`Chapter_7_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_7_Notebooks.zip) |
| 8 | Privacy and Privacy-Preserving AI | 10 | [`Chapter_8_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_8_Notebooks.zip) |
| 9 | AI Security, Robustness and Reliability | 11 | [`Chapter_9_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_9_Notebooks.zip) |
| 10 | AI Safety, Human Oversight and Control | 11 | [`Chapter_10_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_10_Notebooks.zip) |
| 11 | Accountability, Documentation and AI Auditing | 11 | [`Chapter_11_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_11_Notebooks.zip) |
| 12 | AI Risk Management, Impact Assessment and Assurance | 11 | [`Chapter_12_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_12_Notebooks.zip) |
| 13 | Global AI Governance and Law | 10 | [`Chapter_13_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_13_Notebooks.zip) |
| 14 | Responsible Generative AI, Foundation Models and Agentic AI | 10 | [`Chapter_14_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_14_Notebooks.zip) |
| 15 | International AI Governance: Political Economy, Geopolitics and Public Narratives | 11 | [`Chapter_15_Notebooks.zip`](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_15_Notebooks.zip) |

## Get started

### Option A — Google Colab (recommended for classes)

1. Click the **Download ZIP** link in the chapter index for the chapter you want.
2. **Extract** `Chapter_N_Notebooks.zip` on your computer to obtain the `.ipynb` notebooks and chapter README. GitHub cannot directly open individual notebooks that are still inside a ZIP archive.
3. Visit [Google Colab](https://colab.research.google.com/), select **File → Upload notebook**, and upload the desired extracted `.ipynb` file.
4. Read the Markdown introduction cell and run the Python cell with **Runtime → Run all** (or the cell's play icon).
5. Examine tables, figures and exported files, change the experiment parameters, and answer the notebook's student exercise.

> **Note:** The GitHub repository stores chapter ZIPs, not extracted notebook folders. To preview an individual notebook on GitHub or use a direct *Open in Colab* link, it would first need to be uploaded outside its ZIP to the repository.

### Option B — Local Jupyter

Requires **Python 3** and common scientific-Python packages. A typical setup is:

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS / Linux: source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install jupyter numpy pandas matplotlib scipy scikit-learn
jupyter notebook
```

After downloading and extracting a chapter ZIP, navigate to the extracted notebook directory, open an `.ipynb` file, and run its code cell. Some notebooks import only a subset of these libraries. **No external model weights, paid API credentials, or proprietary datasets are needed.** The bundled examples are intended to work without fetching online data after dependencies are installed.

### Typical outputs

- Numerical analyses, confusion matrices, subgroup comparisons, and sensitivity studies.
- Visualisations exported as high-resolution PNG files (600 DPI where specified).
- Illustrative audit logs, registers, model cards, impact records, or evidence summaries in CSV/JSON form.

The output subfolder and file names vary by experiment. High-resolution exports may use additional memory and disk space; reduce the `dpi` value temporarily when iterating, then rerun at the original resolution for final figures.

## Complete notebook catalogue

Expand a chapter to view the **159 notebook filenames** and their corresponding experiments. The `.ipynb` files are contained **inside the ZIP archives** rather than directly in the GitHub file tree. Download and extract the associated archive to access an individual notebook. The filenames in this catalogue are references, not separate GitHub links.

<details>
<summary><strong>Chapter 1: Artificial Intelligence as a Socio-Technical System</strong> — 10 notebooks</summary>

**[Download Chapter 1 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_1_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch1_01_symbolic_statistical_hybrid.ipynb` | Symbolic, Statistical and Hybrid AI |
| `ch1_02_learning_generalisation.ipynb` | Learning, Generalisation and Overfitting |
| `ch1_03_class_imbalance.ipynb` | Why Accuracy Alone Is Insufficient |
| `ch1_04_group_representation.ipynb` | Group Representation and Unequal Errors |
| `ch1_05_threshold_values.ipynb` | Decision Thresholds Encode Value Choices |
| `ch1_06_human_oversight.ipynb` | From Predictive AI to Human Review |
| `ch1_07_feedback_loops.ipynb` | Socio-Technical Feedback Loops |
| `ch1_08_data_leakage.ipynb` | Lifecycle Data Preparation and Leakage |
| `ch1_09_lifecycle_governance.ipynb` | AI Lifecycle Gates and Evidence |
| `ch1_10_integrated_readiness.ipynb` | Integrated Socio-Technical Deployment Review |

</details>

<details>
<summary><strong>Chapter 2: Ethics, Human Rights and Moral Reasoning</strong> — 10 notebooks</summary>

**[Download Chapter 2 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_2_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch2_01_facts_assumptions_value_judgements.ipynb` | Facts, Assumptions and Value Judgements |
| `ch2_02_ethical_theories_tradeoffs.ipynb` | Comparing Ethical Theories on Alternative AI Designs |
| `ch2_03_distributional_justice.ipynb` | Distributional Justice: Equality, Equity and Need |
| `ch2_04_intersectional_errors.ipynb` | Intersectional Error Analysis and Evidence Limits |
| `ch2_05_privacy_utility_frontier.ipynb` | Privacy–Utility Choices and Ethical Constraints |
| `ch2_06_human_rights_remedy.ipynb` | Human Rights, Appeals and Access to Remedy |
| `ch2_07_stakeholder_map.ipynb` | Stakeholder Mapping, Power and Unheard Voices |
| `ch2_08_ethics_of_care_capabilities.ipynb` | Ethics of Care and Real Capabilities |
| `ch2_09_disagreement_sensitivity.ipynb` | Ethical Disagreement and Sensitivity Analysis |
| `ch2_10_documented_ethical_assessment.ipynb` | Integrated Ethical Assessment and Evidence Register |

</details>

<details>
<summary><strong>Chapter 3: Human Values, Power and Responsible Design</strong> — 10 notebooks</summary>

**[Download Chapter 3 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_3_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch3_01_values_in_objective_functions.ipynb` | Chapter 3 — Values Embedded in Objective Functions |
| `ch3_02_representation_and_labels.ipynb` | Chapter 3 — Dataset Representation and Classification Power |
| `ch3_03_stakeholder_power_map.ipynb` | Chapter 3 — Stakeholder Influence, Impact and Representation |
| `ch3_04_benefits_burdens.ipynb` | Chapter 3 — Distribution of Benefits and Burdens |
| `ch3_05_agency_automation_bias.ipynb` | Chapter 3 — Human Agency and Automation Bias |
| `ch3_06_dark_patterns_choice.ipynb` | Chapter 3 — Informed Choice and Dark-Pattern Scenarios |
| `ch3_07_accessibility_and_inclusion.ipynb` | Chapter 3 — Inclusive and Accessible AI Service Evaluation |
| `ch3_08_participatory_codesign.ipynb` | Chapter 3 — Participatory Design and Stakeholder Feedback |
| `ch3_09_value_sensitive_design.ipynb` | Chapter 3 — Value-Sensitive Design Trade-Off Workshop |
| `ch3_10_stakeholder_design_audit.ipynb` | Chapter 3 — Chapter Laboratory: Stakeholder, Power and Value-Impact Audit |

</details>

<details>
<summary><strong>Chapter 4: Responsible Data and Dataset Governance</strong> — 11 notebooks</summary>

**[Download Chapter 4 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_4_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch4_01_data_types_and_quality.ipynb` | Chapter 4 — Data Types, Quality Rules, and Fitness for Purpose |
| `ch4_02_train_validation_test.ipynb` | Chapter 4 — Train, Validation, Test and Pipeline Boundaries |
| `ch4_03_population_sampling.ipynb` | Chapter 4 — Population, Sampling Frames, and Representativeness |
| `ch4_04_missingness.ipynb` | Chapter 4 — MCAR, MAR, MNAR and Imputation Sensitivity |
| `ch4_05_class_imbalance.ipynb` | Chapter 4 — Class Imbalance, Accuracy and Minority Recall |
| `ch4_06_entity_and_target_leakage.ipynb` | Chapter 4 — Target Leakage and Entity Overlap |
| `ch4_07_correlation_confounding.ipynb` | Chapter 4 — Correlation, Confounding and Causal Interpretation |
| `ch4_08_distribution_concept_shift.ipynb` | Chapter 4 — Distribution Shift versus Concept Shift |
| `ch4_09_quantitative_audit.ipynb` | Chapter 4 — Quantitative Dataset Audit and Complete-Record Bounds |
| `ch4_10_annotation_agreement.ipynb` | Chapter 4 — Annotation Quality, Ambiguity and Disagreement |
| `ch4_11_documentation_governance.ipynb` | Chapter 4 — Dataset Documentation, Lineage, Access and Retention Audit |

</details>

<details>
<summary><strong>Chapter 5: Bias and Harm</strong> — 11 notebooks</summary>

**[Download Chapter 5 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_5_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch5_01_statistical_bias.ipynb` | Statistical Estimator Bias Versus Social Discrimination |
| `ch5_02_sampling_representation.ipynb` | Sampling and Representation Bias |
| `ch5_03_measurement_label.ipynb` | Measurement and Labelling Bias |
| `ch5_04_historical_proxy.ipynb` | Historical Bias and Proxy Variables |
| `ch5_05_selection_error.ipynb` | Selection Rates and Error Disparities |
| `ch5_06_intersectionality.ipynb` | Intersectional Group Evaluation |
| `ch5_07_aggregation_learning.ipynb` | Aggregation and Learning Bias |
| `ch5_08_feedback_language.ipynb` | Exposure-Driven Recommendation Feedback |
| `ch5_09_harms_taxonomy.ipynb` | Allocative, Representational and Service-Quality Harms |
| `ch5_10_bounded_harm.ipynb` | Expected Affected Counts and Bounded Harm |
| `ch5_11_integrated_audit.ipynb` | Integrated Bias, Harm, and Remedy Audit |

</details>

<details>
<summary><strong>Chapter 6: Fairness in Machine Learning</strong> — 11 notebooks</summary>

**[Download Chapter 6 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_6_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch6_01_01_equality_equity.ipynb` | Equality, Equity, Procedural and Group Fairness |
| `ch6_02_02_group_performance.ipynb` | Group Confusion Matrices and Predictive Performance |
| `ch6_03_03_group_fairness.ipynb` | Demographic Parity, Equal Opportunity, Equalised Odds and Disparate Impact |
| `ch6_04_04_calibration.ipynb` | Calibration Within Groups and Probability Reliability |
| `ch6_05_05_uncertainty.ipynb` | Fairness Estimates and Wilson Confidence Intervals |
| `ch6_06_06_intersectional.ipynb` | Intersectional Fairness and Small-Cell Suppression |
| `ch6_07_07_individual_counterfactual.ipynb` | Individual Similarity and Counterfactual Sensitivity |
| `ch6_08_08_impossibility.ipynb` | Fairness Trade-offs with Unequal Base Rates |
| `ch6_09_09_preprocessing.ipynb` | Pre-processing Mitigation through Group Reweighting |
| `ch6_10_10_postprocessing.ipynb` | Post-processing Group Thresholds with Separate Validation |
| `ch6_11_11_integrated_audit.ipynb` | Integrated Fairness Audit and Monitoring Register |

</details>

<details>
<summary><strong>Chapter 7: Transparency, Interpretability and Explainable AI</strong> — 11 notebooks</summary>

**[Download Chapter 7 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_7_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch7_01_linear_logistic.ipynb` | Chapter 7 — Linear and Logistic Models: Exact Contributions |
| `ch7_02_tree_rules.ipynb` | Chapter 7 — Decision Trees and Ordered Rules |
| `ch7_03_permutation_importance.ipynb` | Chapter 7 — Global Permutation Importance |
| `ch7_04_pdp_ale.ipynb` | Chapter 7 — Partial Dependence and Accumulated Local Effects |
| `ch7_05_lime_local.ipynb` | Chapter 7 — LIME-Style Local Surrogate |
| `ch7_06_shapley_exact.ipynb` | Chapter 7 — Exact Shapley Attribution for a Two-Feature Model |
| `ch7_07_counterfactual.ipynb` | Chapter 7 — Counterfactual Explanations and Feasible Recourse |
| `ch7_08_examples_prototypes.ipynb` | Chapter 7 — Example-Based Explanations and Similarity |
| `ch7_09_global_surrogate.ipynb` | Chapter 7 — Global Surrogate Fidelity and Complexity |
| `ch7_10_modality_explanations.ipynb` | Chapter 7 — Saliency and Temporal Perturbation Explanations |
| `ch7_11_explanation_audit.ipynb` | Chapter 7 — Explanation Quality, Stability and Contestability Audit |

</details>

<details>
<summary><strong>Chapter 8: Privacy and Privacy-Preserving AI</strong> — 10 notebooks</summary>

**[Download Chapter 8 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_8_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch8_01_reidentification_linkage.ipynb` | Re-identification and Quasi-Identifier Linkage |
| `ch8_02_membership_inference_metrics.ipynb` | Membership Inference: Confusion Matrix and Prevalence |
| `ch8_03_attribute_inference_uplift.ipynb` | Attribute Inference: Auxiliary Baseline and Model-Access Uplift |
| `ch8_04_data_minimisation.ipynb` | Data Minimisation and Predictive Utility |
| `ch8_05_k_anonymity_aggregation.ipynb` | k-Anonymity, Equivalence Classes and Aggregate Differencing |
| `ch8_06_differential_privacy_laplace.ipynb` | Differential Privacy: Laplace Noise and Utility |
| `ch8_07_privacy_composition.ipynb` | Differential Privacy Composition and Release Budget |
| `ch8_08_federated_learning_simulation.ipynb` | Federated Learning: FedAvg on Partitioned Data |
| `ch8_09_synthetic_data_audit.ipynb` | Synthetic Data: Fidelity, Utility, and Nearest-Neighbour Audits |
| `ch8_10_agentic_privacy_permissions.ipynb` | Agentic AI: Retrieval Permissions and Data-Loss Prevention |

</details>

<details>
<summary><strong>Chapter 9: AI Security, Robustness and Reliability</strong> — 11 notebooks</summary>

**[Download Chapter 9 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_9_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch9_01_Digits_Noise_Robustness.ipynb` | Image Noise and Model Robustness |
| `ch9_02_Label_Poisoning.ipynb` | Training-Label Poisoning and Performance |
| `ch9_03_Triggered_Backdoor_Simulation.ipynb` | Trigger-Dependent Misclassification Simulation |
| `ch9_04_Black_Box_Model_Extraction.ipynb` | Black-Box Model Behaviour Approximation |
| `ch9_05_Prompt_Injection_Trust_Boundaries.ipynb` | Indirect Prompt Injection and Tool Authorization |
| `ch9_06_Domain_Shift.ipynb` | Domain Shift and Importance-Weighted Error |
| `ch9_07_OOD_Detection.ipynb` | Out-of-Distribution Detection with Mahalanobis Distance |
| `ch9_08_Probability_Calibration.ipynb` | Predictive Probability Calibration and Brier Score |
| `ch9_09_Selective_Prediction.ipynb` | Selective Prediction: Coverage and Abstention |
| `ch9_10_Conformal_Prediction.ipynb` | Split Conformal Prediction Sets |
| `ch9_11_Reliability_and_Fallback.ipynb` | Service Reliability, Timeouts, and Graceful Degradation |

</details>

<details>
<summary><strong>Chapter 10: AI Safety, Human Oversight and Control</strong> — 11 notebooks</summary>

**[Download Chapter 10 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_10_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch10_01_goal_misspecification.ipynb` | Goal Misspecification and Proxy-Reward Gaming |
| `ch10_02_human_oversight.ipynb` | Human-in-the-Loop and Automation Bias |
| `ch10_03_intervention_timing.ipynb` | Human Intervention Time and Emergency Shutdown |
| `ch10_04_fault_tree.ipynb` | Fault-Tree Analysis and Common-Cause Failures |
| `ch10_05_fmea.ipynb` | Failure Modes and Effects Analysis (FMEA) |
| `ch10_06_safety_constraints.ipynb` | Agent Safety Constraints and Budget Enforcement |
| `ch10_07_operational_boundaries.ipynb` | Operational Design Domain and Safe Fallback |
| `ch10_08_safety_evaluation.ipynb` | Safety Evaluation, Capability and Failure Rates |
| `ch10_09_acceptance_bounds.ipynb` | Pre-Deployment Safety Acceptance Using Confidence Bounds |
| `ch10_10_monitoring_case_mix.ipynb` | Post-Deployment Monitoring and Case-Mix Standardisation |
| `ch10_11_incident_response.ipynb` | Incident Response, Containment and Recovery Verification |

</details>

<details>
<summary><strong>Chapter 11: Accountability, Documentation and AI Auditing</strong> — 11 notebooks</summary>

**[Download Chapter 11 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_11_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch11_01_responsibility_raci.ipynb` | Responsibility Mapping and RACI Gaps |
| `ch11_02_evidence_completeness.ipynb` | Audit Evidence Completeness and Missing Evidence |
| `ch11_03_traceability_weighted.ipynb` | Decision Traceability and Consequence-Weighted Coverage |
| `ch11_04_model_card.ipynb` | Model Card with Reproducible Subgroup Metrics |
| `ch11_05_audit_trail.ipynb` | Audit Trail, Decision Reconstruction and Version Lineage |
| `ch11_06_technical_audit.ipynb` | Technical AI Audit: Accuracy, Group Error and Evidence |
| `ch11_07_audit_sampling.ipynb` | Audit Sampling and Rare-Issue Detection |
| `ch11_08_contestability.ipynb` | Contestability, Human Review and Remedy Metrics |
| `ch11_09_remediation.ipynb` | Audit Findings, Corrective Actions and Verified Closure |
| `ch11_10_audit_checklist.ipynb` | AI Audit Checklist and Evidence-Gap Register |
| `ch11_11_change_control.ipynb` | Model Version Changes and Audit Revalidation |

</details>

<details>
<summary><strong>Chapter 12: AI Risk Management, Impact Assessment and Assurance</strong> — 11 notebooks</summary>

**[Download Chapter 12 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_12_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch12_01_risk_exposure.ipynb` | Risk, Likelihood, Severity and Exposure |
| `ch12_02_risk_matrix.ipynb` | Risk Matrix and Sensitivity Analysis |
| `ch12_03_risk_register.ipynb` | Operational Risk Register and Control Matrix |
| `ch12_04_bias_impact.ipynb` | Algorithmic Impact Assessment: Subgroup Evidence |
| `ch12_05_controls.ipynb` | Control Effectiveness and Residual-Risk Sensitivity |
| `ch12_06_assurance.ipynb` | Assurance Claims, Evidence and Verification |
| `ch12_07_monitoring.ipynb` | Key Risk Indicators and Monitoring Triggers |
| `ch12_08_framework_mapping.ipynb` | AI Risk Framework Mapping and Coverage Gaps |
| `ch12_09_environment.ipynb` | Environmental Impact: Energy, Carbon and Workload |
| `ch12_10_stakeholder.ipynb` | Impact Assessment: Stakeholder and Rights Coverage |
| `ch12_11_assurance_release.ipynb` | Integrated Risk and Assurance Release Gate |

</details>

<details>
<summary><strong>Chapter 13: Global AI Governance and Law</strong> — 10 notebooks</summary>

**[Download Chapter 13 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_13_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch13_01_Governance_Models_Matrix.ipynb` | Chapter 13 \| Experiment 01: Governance Models: Comparative Decision Matrix |
| `ch13_02_Risk_Based_Controls.ipynb` | Chapter 13 \| Experiment 02: Risk-Based Governance and Proportionate Controls |
| `ch13_03_International_Instruments.ipynb` | Chapter 13 \| Experiment 03: International Instruments: Status and Coverage |
| `ch13_04_India_Governance_Layers.ipynb` | Chapter 13 \| Experiment 04: India: Distributed Governance Responsibilities |
| `ch13_05_Obligation_Traceability.ipynb` | Chapter 13 \| Experiment 05: Legal-Obligation Traceability and Evidence Gaps |
| `ch13_06_Synthetic_Content_Provenance.ipynb` | Chapter 13 \| Experiment 06: Synthetic Content: Labelling and Provenance Tests |
| `ch13_07_Value_Chain_RACI.ipynb` | Chapter 13 \| Experiment 07: Foundation Model Value Chain: Responsibility and RACI |
| `ch13_08_Cross_Border_Data_Flows.ipynb` | Chapter 13 \| Experiment 08: Cross-Border AI: Data Flow and Governance Checklist |
| `ch13_09_Regulatory_Change_Control.ipynb` | Chapter 13 \| Experiment 09: Regulatory Change Management and Reassessment |
| `ch13_10_Governance_Audit_Summary.ipynb` | Chapter 13 \| Experiment 10: Integrated Governance Audit: Controls, Evidence and Remedy |

</details>

<details>
<summary><strong>Chapter 14: Responsible Generative AI, Foundation Models and Agentic AI</strong> — 10 notebooks</summary>

**[Download Chapter 14 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_14_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch14_01_Discriminative_vs_Generative_Digits.ipynb` | Discriminative and Generative Modelling on Handwritten Digits |
| `ch14_02_Next_Token_Sampling.ipynb` | Autoregressive Next-Token Generation and Sampling |
| `ch14_03_Attention_And_Context.ipynb` | Scaled Dot-Product Attention and Context Sensitivity |
| `ch14_04_Generative_Fidelity_Privacy.ipynb` | Synthetic Data Fidelity, Utility and Memorisation Checks |
| `ch14_05_Grounding_And_Citation_Verification.ipynb` | Retrieval Grounding, Source Support and Abstention |
| `ch14_06_Hallucination_Claim_Audit.ipynb` | Claim-Level Verification and Hallucination Audit |
| `ch14_07_Agent_Permissions_And_Human_Gates.ipynb` | Agentic Tool Permissions, Human Approval and Audit Trails |
| `ch14_08_Memory_Provenance_And_Retention.ipynb` | Persistent Agent Memory, Provenance and Retention |
| `ch14_09_Multi_Agent_Cascade_And_Budgets.ipynb` | Multi-Agent Delegation, Verification and Cascading Failures |
| `ch14_10_Integrated_Responsibility_Audit.ipynb` | Generative and Agentic AI Responsibility Audit |

</details>

<details>
<summary><strong>Chapter 15: International AI Governance: Political Economy, Geopolitics and Public Narratives</strong> — 11 notebooks</summary>

**[Download Chapter 15 ZIP](https://github.com/ParthaPRay/Responsible-AI-Codebook/raw/refs/heads/main/Chapter_15_Notebooks.zip)**

| Notebook | Practical experiment |
|---|---|
| `ch15_01_distributional_benefits_burdens.ipynb` | Chapter 15 Lab 01: Stakeholder Distribution of Benefits and Burdens |
| `ch15_02_supplier_concentration_hhi.ipynb` | Chapter 15 Lab 02: Supplier Concentration and Shared Upstream Dependencies |
| `ch15_03_cloud_access_capacity.ipynb` | Chapter 15 Lab 03: Nominal versus Usable AI Compute Capacity |
| `ch15_04_lifecycle_cost_migration.ipynb` | Chapter 15 Lab 04: Three-Year Procurement, Switching and Migration Costs |
| `ch15_05_dependency_recovery_horizons.ipynb` | Chapter 15 Lab 05: Time-Indexed Dependency and Bottleneck Indicators |
| `ch15_06_cross_border_service_mapping.ipynb` | Chapter 15 Lab 06: Cross-Border Data Flows, Control Rights and Evidence Gaps |
| `ch15_07_consultation_representation.ipynb` | Chapter 15 Lab 07: Consultation Representation and Substantive Influence |
| `ch15_08_public_claim_evidence.ipynb` | Chapter 15 Lab 08: Public-Narrative Claims and Evidence Audits |
| `ch15_09_cooperation_game.ipynb` | Chapter 15 Lab 09: Geopolitical Cooperation and Repeated Incentives |
| `ch15_10_policy_multi_criteria.ipynb` | Chapter 15 Lab 10: Cross-Border Procurement: Constraints, Sensitivity and Policy Choice |
| `ch15_11_sovereignty_control_test.ipynb` | Chapter 15 Lab 11: Operational Sovereignty: Formal Rights versus Tested Capacity |

</details>

## Teaching and learning workflow

A useful laboratory sequence is: **(1)** study the corresponding textbook section, **(2)** read the notebook's assumptions and objectives, **(3)** run its Python cell, **(4)** verify one or two values independently, **(5)** modify an input, threshold, sample composition, or policy assumption, **(6)** interpret the numerical changes and limitations, and **(7)** record a justified recommendation or further evidence requirement.

### Suggested student submission

For each assigned notebook, submit a short report containing the objective; input assumptions and data origin; chosen parameters; numerical results and one relevant figure; explanation of the result; at least two limitations; and a brief reflection on which stakeholder, ethical, or governance questions remain unresolved. Include code changes or outputs only when permitted by the course instructor and applicable repository permissions.

## Responsible use, reproducibility, and limitations

- **Educational simulations:** Fictional people, organisations, demographic categories, policy scores, probabilities, incidents, and examples are not empirical evidence of actual harms or compliance.
- **No single metric is a verdict:** Predictive accuracy, fairness statistics, audit indices, risk matrices, attributions, and explanation scores require contextual interpretation. A good result on one metric does not establish responsible deployment.
- **Correlation is not causation:** Feature importance, regression coefficients, explanations, and observed group differences must not be presented as causal findings without a suitable design and assumptions.
- **Reference labels and group definitions matter:** Evaluation outcomes depend on measurement quality, affected populations, and sample size. Small subgroups may yield uncertain estimates.
- **Safety and security:** Adversarial, agentic, and intervention examples are bounded classroom demonstrations, not penetration-test instructions or safety certifications.
- **Legal and policy context:** Any references to regulations, rights, policy instruments, or standards must be checked against the applicable jurisdiction and current official texts before operational use. Notebook scenarios are not legal advice.
- **Human oversight:** Actual deployment in high-impact settings requires suitable human expertise, lawful data practices, independent evaluation, effective remedy, and continuing oversight.
- **Privacy and cultural context:** Do not replace fictional or public demonstration data with identifiable student, patient, employee, or community records without proper authorisation, safeguards, and ethical review.
- **Reproducibility:** Results may vary slightly with Python/package versions or random seeds. For publication-quality comparisons, document the environment and execute the full procedure independently.

## Repository organisation

The `main` branch currently hosts **15 ZIP files** at repository root; notebooks are distributed inside their respective ZIP archives.

```text
Responsible-AI-Codebook/
├── README.md
├── LICENSE
├── Chapter_1_Notebooks.zip
├── Chapter_2_Notebooks.zip
├── Chapter_3_Notebooks.zip
├── Chapter_4_Notebooks.zip
├── Chapter_5_Notebooks.zip
├── Chapter_6_Notebooks.zip
├── Chapter_7_Notebooks.zip
├── Chapter_8_Notebooks.zip
├── Chapter_9_Notebooks.zip
├── Chapter_10_Notebooks.zip
├── Chapter_11_Notebooks.zip
├── Chapter_12_Notebooks.zip
├── Chapter_13_Notebooks.zip
├── Chapter_14_Notebooks.zip
└── Chapter_15_Notebooks.zip
```

The notebook names in the expandable catalogue refer to files **inside** these archives. No extracted chapter folders are assumed to exist in the GitHub repository.

## Authorship, copyright, and licence

**Copyright © 2026 Partha Pratim Ray.** The creator retains copyright in original materials. Attribution is requested in academic uses, and the repository's licence notice must be preserved in distributions covered by that licence.

**Current repository licence: [MIT License](https://github.com/ParthaPRay/Responsible-AI-Codebook/blob/main/LICENSE).** The repository presently contains an MIT `LICENSE` file, which allows use, copying, modification, redistribution, sublicensing, and sale of the covered software, including commercial uses, subject to preserving the copyright and permission notice. The repository materials are provided *as is*, without warranty, under the MIT terms.

Third-party packages, source material and datasets retain their own licence and attribution obligations. Citation of the book and these notebooks is encouraged for academic integrity but is distinct from the MIT licence's conditions.

> **Licence-policy note for the owner:** An MIT licence does **not** require prior written approval or monetary payment for commercial use. If your intention is to require commercial permission and fees, consult appropriate legal advice before adopting new terms. Merely editing this README would not override MIT rights already granted for previously published versions.

## How to cite

If these notebooks inform a teaching resource, research paper, presentation, course, thesis, adaptation, or technical report, **credit the creator and identify the relevant notebook(s)**. When reusing code, also comply with the repository licence and relevant third-party terms.

**Suggested repository citation:**

> Ray, Partha Pratim. *Responsible AI: Companion Python Laboratory Notebooks*. GitHub repository, 2026. Repository URL: `https://github.com/ParthaPRay/Responsible-AI-Codebook` (accessed `[access date]`).

**BibTeX template:**

```bibtex
@misc{ray_responsible_ai_notebooks_2026,
  author       = {Ray, Partha Pratim},
  title        = {Responsible AI: A Textbook on Ethics, Fairness, Safety and
	Governance},
  year         = {2026},
  howpublished = {GitHub repository},
  url          = {https://github.com/ParthaPRay/Responsible-AI-Codebook},
  note         = {Companion Jupyter/Colab codebook; accessed on the date of use}
}
```

For a publication based on a particular exercise, also identify its **chapter number and exact `.ipynb` filename**, and cite the textbook separately using the bibliographic details of the published edition when available.

## Feedback and corrections

Bug reports, reproducibility issues, and suggestions for improving pedagogical clarity can be submitted through GitHub Issues if the repository owner enables them. Please include the chapter and notebook filename, relevant package versions, a minimal description of the issue, and a non-sensitive error message. **Do not include personal data, confidential datasets, or API credentials in issue reports.**

---

**Created by Partha Pratim Ray** · *Responsible AI* textbook companion · **15 chapters / 159 laboratory notebooks**
