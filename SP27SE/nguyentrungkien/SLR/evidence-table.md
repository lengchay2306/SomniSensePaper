Paper	Tool/LLM	Dataset	Metric	Result	Code	Limitation
Association of Hypoxic Burden With Cardiovascular Events: A Risk Stratification Analysis of the Randomized Intervention With CPAP in Coronary Artery Disease and Sleep Apnea Cohort(2025) | Venue: CHEST | DOI: 10.1016/j.chest.2025.07.4081	"Statistical software (unspecified; analysis performed by Y. Peker, Y. Chen, and A. Azarbarzin)
.
Regression Framework: Multivariable Cox Proportional Hazards Regression Models to compute hazard ratios (HR) and 95% CIs for MACCEs
. Model I adjusted for age, sex, BMI, diabetes, former/type of revascularization, hypertension, smoking, atrial fibrillation, myocardial infarction, and CPAP allocation
. CPAP compliance hourly usage data was downloaded directly from patient CPAP devices
"	"Dataset: RICCADSA cohort (Randomized Intervention with CPAP in Coronary Artery Disease and Sleep Apnea)
.
Quantity: 368 patients with moderate-to-severe OSA and CAD available for HB analysis (262 untreated/nonadherent to CPAP and 106 adherent to CPAP)
.
Domain: Sleep apnea-specific hypoxemia and cardiovascular/cerebrovascular epidemiology."	"Hazard Ratio (HR) with 95% Confidence Interval (CI), p-value, and log-rank test"	"High vs. Low Hypoxic Burden (HB) associated with MACCEs in Model I (fully adjusted): Adjusted HR = 1.87 (95% CI: 1.17–2.98, p = 0.009)3.Baseline AHI $\ge$ 30 events/h: Not significantly associated with MACCEs (p = 0.366)13.Model comparing High HB & Low AHI vs. Low HB & Low AHI: Adjusted HR = 2.60 (95% CI: 1.15–5.90, p = 0.022)"		"The use of a single cutoff for HB and AHI may limit the study
.
Exclusion of individuals with baseline AHI < 15 events/h on HSAT per parent study design, potentially putting AHI at a disadvantage when predicting future risk in this specific sample
.
Potential unmeasured confounding factors that were not included in the model
.
The study focused strictly on risk stratification, not the therapeutic effect of CPAP for secondary prevention
"
Sex Differences in Obstructive Sleep Apnea after Stroke(2024) | Venue: The Canadian Journal of Neurological Sciences | DOI: https://doi.org/10.1017/cjn.2023.300	"P.A.S.W Statistics 25.0 (SPSS Inc., Chicago, IL).Regression Framework: Multivariable Linear Regression7.Multicollinearity Diagnostics: Variable Collinearity assessment utilizing the Tolerance Statistic with a strict cutoff threshold of $< 0.4$ to eliminate redundant covariates7.Model Diagnostics / Validation: Model assumption validation via Residual Plot analysis to check for homoscedasticity and linearity violations7.Hypothesis Testing: Chi-square tests (for categorical variables); Independent sample $t$-tests (for normally distributed continuous variables); Mann-Whitney $U$ test (for non-normally distributed continuous variables)"	"Dataset: Retrospective pool of data from three previously conducted studies
.
Quantity: 171 participants (117 males [68.4%] and 54 females [31.6%])
.
Domain: Post-stroke obstructive sleep apnea (OSA) neurology and sleep medicine."	"Linear regression coefficient ($\beta$), 95% Confidence Interval (CI), p-value"	"Functional impairment (Modified Rankin Scale - mRS): Female sex was an independent predictor for greater functional impairment: $\beta = 0.37$ (95% CI: 0.029–0.71, p = 0.03)10.Stroke severity (NIH Stroke Scale - NIHSS): Female sex predicted increased stroke severity: $\beta = 1.009$ (95% CI: 0.032–1.99, p = 0.04)10.Depressive symptoms (Center for Epidemiological Studies Depression Scale - CESD): Female sex predicted greater post-stroke depressive symptoms: $\beta = 3.73$ (95% CI: 0.16–7.29, p = 0.04)11.OSA severity (Apnea-Hypopnea Index - AHI): Female sex predicted lower AHI (milder OSA): $\beta = -5.93$ (95% CI: -11.21 to -0.66, p = 0.03)9.OSA Symptoms (Snoring, Tiredness, Observed Apneas): Sex was not a significant independent predictor (Snoring: p = 0.18; Tiredness: p = 0.19; Observed apneas: p = 0.89)"		"Relatively small sample size
.
Use of HSAT (level III portable monitor) for some participants instead of PSG (the gold standard), though the HSAT was validated
.
Exclusion of patients with significant physical impairment (who were generally unable to complete the study requirements), making results potentially less generalizable to patients with very severe strokes
.
Lack of a control group without OSA or control group of patients who had not sustained a cerebrovascular event"
Association between Obstructive Sleep Apnea and SYNTAX Score(2020) | Venue: Journal of Clinical Medicine | DOI: doi:10.3390/jcm9103314	"R software version 3.4.3 (R Core Team, Vienna, Austria).Regression Framework: Multivariable Stepwise Linear Regression3.Variable Transformation: Log-transformation of the skewed dependent variable: $\log(\text{SYNTAX score} + 0.1)$3.Stepwise Selection Criteria: $p < 0.05$ to enter and $p > 0.1$ to remove3.Subgroup / Interaction Analysis: Interaction testing between testing sequence (coronary angiogram first vs. polysomnography first) and moderate-to-severe OSA relative to the SYNTAX score3.Hypothesis Testing: $\chi^2$ test or Fisher's exact test (for categorical variables); Student's $t$-test or Mann-Whitney $U$-test (for continuous variables)"	"Dataset: Screening database of patients hospitalized at Toranomon Hospital (Tokyo, Japan)
.
Quantity: 98 patients (23 in no-to-mild OSA group, 75 in moderate-to-severe OSA group; mean age 58.3 years, 92% male)
.
Domain: Stable coronary artery disease (CAD) and obstructive sleep apnea (OSA)."	"Stepwise linear regression, partial correlation, p-value"	"SYNTAX score comparison: Significantly higher in patients with moderate-to-severe OSA than in those with no-to-mild OSA (median [IQR]: 4.0 [13.5] vs. 0
, respectively, p = 0.001)
.
Multivariable correlation: After adjustment for other cardiovascular risk factors, moderate-to-severe OSA significantly independently correlated with the SYNTAX score (log-transformed): partial correlation = 0.24, p = 0.039
."		"Single-center retrospective study of a small cohort, which could affect findings, and causal relationships between CAD and OSA severity could not be determined
.
Gender disproportion (over 90% of the patients were male)
.
Several unmeasured factors were not included in the model, such as echocardiography findings (systolic/diastolic function), NYHA functional classification, medication use, Epworth Sleepiness Scale, or SYNTAX II score
.
Did not evaluate the sequential effect of OSA severity on CAD over time or the effect of positive airway pressure treatment on CAD
"
Polysomnographic correlates of self-and caregiver-reported sleep problems in post-stroke patients(2025) | Venue: Frontiers in Neurology | DOI: 10.3389/fneur.2025.1587378	" STATA 12.0 & SOMNOmedics 14-channel system (manual scoring per AASM v2.6).Regression Framework: Univariate Analysis only (multivariate models omitted to prevent overfitting due to small sample size, $n = 41$).Hypothesis Testing: Kolmogorov-Smirnov (normality), Student’s $t$-test, Mann-Whitney U, Wilcoxon signed-rank, and Chi-square / Fisher’s exact tests."	"Dataset:
Name/Source: Post-stroke patients evaluated 1 month to 1 year post-onset at the All India Institute of Medical Sciences (AIIMS), New Delhi, India
.
Quantity: 103 patients enrolled; a subset of 41 patients completed full overnight PSG
.
Domain: Post-stroke sleep disorders (PSSD), neurological rehabilitation
."	"Pittsburgh Sleep Quality Index (PSQI), STOP-BANG Questionnaire, Hamilton Depression/Anxiety Rating Scales (HAM-D/HAM-A)
Modified Rankin Scale (mRS), Stroke-Specific Quality of Life Scale (SS-QoL)
Apnea-Hypopnea Index (AHI), Periodic Limb Movements in Sleep (PLMS), and Wakefulness After Sleep Onset (WASO)"	"Reporting Discrepancy (Table 1): Only 23.3% of patients and 11.7% of caregivers spontaneously reported sleep disturbances
. However, proactive, structured questioning revealed sleep symptoms in 60.2% of the cohort
.
Silent Burden: PSG confirmed OSA in 62.1% (18/29) and PLMS in 34.5% (10/29) of the stroke patients who completely denied having sleep problems
.
SDB Prevalence: 65.8% of the PSG subgroup had an objective AHI > 5
. High AHI (>5) did not show any statistically significant association with clinical stroke features or standard questionnaire scores
.
Sleep Quality (Supplementary Table S2): Only WASO > 120 minutes was significantly more common in the poor sleep quality group (PSQI > 5)
"		"The study had a small overall sample size, particularly for sub-analyses within the PSG-tested subgroup ($n = 41$)26.Polysomnography could not be performed on all 103 enrolled patients, which may have introduced selection bias (since patients experiencing sleep problems might have been more willing to undergo the test)2226.No clinical follow-up was conducted, preventing assessment of whether treating the sleep disorders improved recovery26.A potential first-night effect in the laboratory setting might have led to an overestimation/overdiagnosis of sleep fragmentation or insomnia26"
Screening for obstructive sleep apnea before coronary angiography.(2023) | Venue:The Clinical Respiratory Journal | DOI: 10.1111/crj.13556	IBM SPSS 20.0 & Alice NightOne (Level III HST).Regression Framework:Multivariate Logistic Regression to evaluate CHD risk factors (including AHI $\ge$ 20).Pearson’s Correlation to analyze the linear relationship between Gensini score and AHI.Hypothesis Testing: Student’s $t$-test (continuous variables) and Pearson Chi-squared ($\chi^2$) (categorical variables).	"Dataset:
Name/Source: Retrospective evaluation of suspected coronary heart disease (CHD) patients admitted to the Department of Geriatric Cardiology of Guangdong Provincial People’s Hospital, China
.
Quantity: 327 patients (211 with confirmed CHD and 116 without CHD)
.
Domain: Cardiorespiratory sleep medicine, interventional cardiology, early screening
.
"	Apnea-Hypopnea Index (AHI) and nighttime Oxygen Saturation ($SpO_2$)29Gensini Score (quantitative coronary artery stenosis severity)3135Multivariate Logistic Regression (Odds Ratio [OR] with 95% Confidence Interval [CI])	"High OSA Prevalence: 80.7% of the total cohort (264/327 patients) had OSA (AHI $\ge$ 5)32. The prevalence was significantly higher in the CHD group than in the non-CHD group (87.2% vs. 69.0%, p < 0.01)32.Severer Airway Obstruction: The CHD group had a significantly higher AHI (18.76 $\pm$ 14.94 vs. 11.56 $\pm$ 10.67, p < 0.01)32 and a higher rate of AHI $\ge$ 20 (34.6% vs. 16.4%, p < 0.01)37.Coronary Stenosis Severity (Table 2): The Gensini score was significantly higher in patients with severe OSA (38.18 $\pm$ 34.53) compared to the other groups (moderate OSA: 24.67 $\pm$ 20.41, mild OSA: 24.91 $\pm$ 23.09, no OSA: 26.15 $\pm$ 19.47, p = 0.022)38.CHD Risk Factors (Table 3 / Figure 1): Diabetes (OR = 2.046, p = 0.026), Age $\ge$ 60 years (OR = 2.475, p = 0.001), and AHI $\ge$ 20 (OR = 1.961, 95% CI: 1.065–3.608, p = 0.031) were independent risk factors for CHD3639."		"This was a retrospective, single-centre study
.
No follow-up was performed, meaning CPAP treatment adherence and post-coronary angiography clinical outcomes in patients with moderate-to-severe OSA were not tracked
.
Because OSA is a chronic disease, the exact time of onset and duration of exposure to nocturnal intermittent hypoxia could not be determined
.
The complete Epworth Sleepiness Scale (ESS) was not fully integrated to assess subjective daytime drowsiness"
Symptom and comorbidity burden in hypertensive patients with obstructive sleep apnea (2024) | Venue: Frontiers in Endocrinology | DOI: 10.3389/fendo.2024.1361466	"SPSS 26.0 & Alice 5 Polysomnographic System.Regression Framework: Binary Logistic Regression to identify independent risk factors for hypertension, adjusting for demographics, clinical symptoms, and PSG indices.Hypothesis Testing: Student’s $t$-test, One-way ANOVA, Mann-Whitney U, and Pearson Chi-squared ($\chi^2$) tests."	"Dataset:
Name/Source: Retrospective analysis of newly diagnosed adult OSA patients at Lihuili Hospital, Affiliated to Ningbo University, China, between January 2016 and December 2020
.
Quantity: 1108 patients (387 with hypertension, 721 without hypertension)
.
Domain: Metabolic and cardiovascular endocrinology, sleep-disordered breathing"	"Epworth Sleepiness Scale (ESS) score44, awake pulse oxygen saturation, and full-night PSG indicators (Awake $SaO_2$, Minimum $SaO_2$, Average $SaO_2$, Sleep latency, AHI, ODI, and T90)4449Incidence rates of clinical symptoms (nocturia, etc.) and comorbidities4750Binary Logistic Regression (Odds Ratio [OR] with 95% Confidence Interval [CI])"	"Demographic & Clinical Differences (Table 1): Hypertensive OSA patients were significantly older (50.31 $\pm$ 10.92 vs. 42.60 $\pm$ 11.03 years, p < 0.001) and more obese (BMI: 28.25 $\pm$ 3.56 vs. 26.62 $\pm$ 3.18 kg/m², p < 0.001)52.Symptom Burden (Table 2): Nocturia was significantly more common in the hypertensive OSA group compared to normotensive group (41.09% vs. 20.80%, p < 0.001)53.PSG Severity (Table 4): Hypertensive patients exhibited significantly lower minimum $SpO_2$ (70.19% $\pm$ 13.84% vs. 73.33% $\pm$ 12.46%, p < 0.001) and a much higher median AHI (48.20 vs. 37.30 events/h, p < 0.001)54.Independent Comorbidity Risk Factors (Table 5): In newly diagnosed OSA patients, hypertension was independently associated with age (OR = 1.06), BMI (OR = 1.17), and nocturia (OR = 1.64, p = 0.002)55, as well as major metabolic/cardiovascular comorbidities:Diabetes Mellitus: OR = 3.86 (95% CI: 2.31–6.45, p < 0.001)55Cardiovascular Disease: OR = 1.90 (95% CI: 1.15–3.16, p = 0.013)56Ischemic Stroke: OR = 3.69 (95% CI: 1.31–10.40, p = 0.014)"		"Ambulatory blood pressure monitoring was not conducted, meaning crucial data regarding nighttime blood pressure fluctuations (such as non-dipping or rising patterns) was unavailable
.
No subgroup analysis was performed regarding different severity levels/stages of hypertension
.
"
Obstructive sleep apnea is associated with cognitive impairment in minor ischemic stroke (2022) | Venue: Sleep and Breathing | DOI: 10.1007/s11325-022-02575-5	SPSS 23.0 & Alice 6 Diagnosis Platform.Regression Framework: Binary Logistic Regression ("Enter" method) to predict cognitive impairment (MoCA < 26) and OSA onset (AHI $\ge$ 5).Hypothesis Testing: One-way ANOVA and LSD post-hoc tests for multi-group clinical and cognitive comparisons.	"Dataset:
Name/Source: Consecutively enrolled patients with minor ischemic stroke admitted to the Neural Psychiatric Disorders and Mental Health Centre of Anhui Province
.
Quantity: 94 patients (35 No OSA, 32 Mild OSA, and 27 Moderate-to-Severe OSA)
.
Domain: Sleep medicine, respiratory physiology, post-stroke cognitive neurology
.
"	"Apnea-Hypopnea Index (AHI)1 and Lowest Oxygen Saturation ($SpO_2$)18Neuropsychological test scores: Montreal Cognitive Assessment (MoCA), Chinese version of the Auditory Verbal Learning Test (CAVLT)-Recognition, Digital Span Test (DST)-Backward, and Stroop Color and Word Test (SCWT)-Interference1Odds Ratio (OR) with 95% Confidence Interval (CI) and p-values for risk factors"	"OSA Prevalence: 63% (59/94 stroke survivors had an AHI $\ge$ 5)10.Cognitive Deficits (Table 4): The moderate-to-severe OSA group performed significantly worse than the No OSA group on MoCA (21.9 $\pm$ 2.4 vs. 26.5 $\pm$ 2.8, p < 0.001) and SCWT-Interference (58.2 $\pm$ 1.3 vs. 35.9 $\pm$ 1.9, p < 0.001)11.Regression Analysis (Table 5): Cognitive impairment (MoCA < 26) was independently predicted by AHI (OR = 1.42, 95% CI: 1.056–1.706, p = 0.041) and Lowest $SpO_2$ (OR = 1.37, 95% CI: 1.003–1.857, p = 0.048)312.Predictors of OSA Onset (Table 2): Gender (OR = 0.17, 95% CI: 0.04–0.74, p = 0.02), Hypertension (OR = 4.61, 95% CI: 1.45–14.69, p = 0.01), and Smoking (OR = 9.18, 95% CI: 2.32–36.28, p = 0.00)"		"The cross-sectional study design prevented the inference of a causal relationship between cognitive decline and OSA
.
The sample size was relatively small (94 patients), which might affect the generalizability of the conclusions
.
Significant differences in baseline prevalence of hypertension and smoking status among the study groups could have influenced the comparisons of polysomnography and neuropsychology assessments"
"Obstructive sleep apnea, coronary calcification and arterial stiffness in patients with diabetic kidney disease(2024) | Venue: Atherosclerosis | DOI: 10.1016/j.atherosclerosis.2023.06.076"	"STATA version 17.0, ApneaLink+ , SphygmoCor,SOMATOM Definition Force. Regression Framework: Multivariable Linear and Logistic Regression models adjusted for sex, age, BMI, UACR, and MAP
. Dominance Analysis was carried out to estimate the relative importance of cardiovascular risk factors
. Residuals of the regression models were examined with QQ-plots
.
Hypothesis Testing: Independent-sample t-test (for normally distributed continuous variables, verified by histograms and QQ-plots)
; Wilcoxon Rank-sum test (for skewed continuous variables); Chi-squared test (for categorical variables)"	"Dataset: Patients with type 2 diabetes, proteinuria, and reduced glomerular filtration rate recruited from clinics at Aarhus University Hospital, Denmark.
Quantity: 74 patients completed the full imaging and physiological protocol (39 No-OSA, 35 Moderate-to-Severe OSA).
Domain: Cardiorenal vascular pathology and diabetic nephropathy.
"	"Linear regression coefficient ($\beta$), Odds Ratio (OR) with 95% Confidence Interval (CI), and p-value."	"Crude Vascular Damage Differences (Fig 2 & Fig 3): ln-transformed Coronary Agatston Score (CAS) was significantly higher in OSA compared to No-OSA (6.6 ± 1.7 vs. 5.6 ± 2.4, p = 0.04), and PWV was also significantly higher (11.9 ± 2.7 vs. 10.5 ± 2.2 m/s, p = 0.02).Arterial Stiffness Association (Table S3A): Moderate-to-severe OSA remained independently associated with PWV in multivariable analysis ($\beta = 1.442$, 95% CI: 0.16–2.72, p = 0.02).Coronary Calcification Association (Table S2A): The independent association between OSA and CAS became insignificant ($\beta = 0.440$, 95% CI: -0.65 to 1.53, p > 0.05) once adjusted for age and male sex.Relative Predictor Rank (Dominance Analysis): OSA was ranked as the second most important factor contributing to PWV (15.5%) and the third most important factor contributing to CAS (15.1%)."		"The cross-sectional study design prevents establishing direct causal pathways.
Frail elderly patients with diabetic kidney disease had a high non-response rate, resulting in a relatively small sample size.
Potential residual confounding from unmeasured variables could still exist.
Sleep metrics were recorded using a simplified portable home device (ApneaLink+) instead of full-night laboratory polysomnography.
Exclusion of patients with prior revascularizations (CABG or PCI) limits the generalizability of coronary calcification findings to the broader, more severe DKD population."
Obstructive sleep apnea during REM sleep: effects on morning and evening blood pressure(2023) | Venue: Sleep | DOI: 10.1093/sleep/zsac259	"R version 4.1 & Sigmaplot version 12.3, Compumedics Grael Polysomnography System  .Regression Framework: Multivariable Logistic Regression models adjusted for age, gender, BMI, REM AHI, NREM AHI, alcohol use, total sleep time (TST), sleep time SpO2 <90% (T90%), and smoking status1415. Checks for collinearity confirmed variance inflation factors (VIF) were in the range of 1–214. REM AHI values above 65 were logit-transformed to equal 65 to handle effect saturation14.Hypothesis Testing: Non-parametric ANOVA on ranks with Dunn's post-hoc pairwise comparisons (as continuous sleep/demographic parameters failed normality testing); Chi-square ($\chi^2$) analysis for gender distributions and hypertensive proportions16."	"Dataset:Diagnostic in-laboratory sleep studies performed at Eastern Health (Melbourne, Australia) over a 16-month period (September 2018–December 2019).
Quantity: 797 adult patients (771 included in the evening BP regression model; 755 included in the morning BP regression model).
Domain: Cardiorespiratory sleep medicine and autonomic blood pressure regulation."	" Odds Ratio (OR) with 95% Confidence Interval (CI), p-values, and median with interquartile range (IQR).
"	"Morning Hypertensive Blood Pressure (Table 3): Significantly independently associated with REM AHI (OR = 1.016, 95% CI: 1.007–1.026, p < 0.001), Age (OR = 1.053, p < 0.001), and BMI (OR = 1.074, p < 0.001). NREM AHI had no significant independent association (OR = 1.002, p = 0.8).
Evening Hypertensive Blood Pressure (Table 2): Associated with Age (OR = 1.035, p < 0.001), Male sex (OR = 1.561, p = 0.012), BMI (OR = 1.093, p < 0.001), and Total Sleep Time (OR = 0.997, p = 0.032). REM AHI had no independent effect (OR = 1.009, p = 0.07).
Prevalence Indicators: 58% of participants exhibited evening hypertensive BP, and 52% exhibited morning hypertensive BP. Rates of both morning and evening hypertension increased significantly across increasing REM AHI intervals (p < 0.001).
"		"The clinical blood pressure protocol relied on a single sitting reading instead of an average of 2-3 consecutive measurements.
The study did not record the exact timing of antihypertensive medication intake, which may have blunted evening BP measurements.
Morning measurements could be confounded by the physiological ""morning blood pressure surge"" phenomenon.
Continuous intra-arterial or non-invasive blood pressure monitoring was not conducted throughout the polysomnography.
The exact duration of individual obstructive apnea/hypopnea events was not assessed.
Data collection was limited to a single clinical hospital site, restricting transferability"
"Severe obstructive sleep apnea phenotypes by cluster analysis based on multiple organs function(2025) | Venue: Scientific Reports | DOI: 10.1038/s41598-025-19062-y
"	"Python version 3.7.6 with scikit-learn 22.2 library, IBM SPSS version 21.0 ,PHILIPS HD7 Color Doppler Ultrasound, ALOKA F75 Doppler Ultrasound. Regression/Clustering Framework: Unsupervised K-medoids Clustering performed on 25 clinical, anthropometric, and multi-organ continuous variables
. Features standardisation was achieved using z-score transformation, and t-Distributed Stochastic Neighbor Embedding (t-SNE) was applied for dimensional reduction
. The optimal cluster count (k) was selected using the Elbow method
.
Hypothesis Testing: Student’s t-test or non-parametric Mann–Whitney U test (for continuous variables); Chi-square test (for categorical variables)
.
"	"Dataset: Adult patients diagnosed with severe OSA (AHI $\ge$ 30 events/hour) at the Affiliated Hospital of Guilin Medical University, China (September 2021–December 2023).Quantity: 503 severe OSA patients partitioned into two clusters: Cluster 1 (n = 136; female-predominant, 71.3%) and Cluster 2 (n = 367; male-predominant, 90.7%).Domain: Sleep medicine, metabolic endocrinology, and multi-organ physiological profiling (liver, kidney, lipid, and vascular metrics)."	"Mean $\pm$ Standard Deviation, proportions/percentages, and p-value."	"Cluster 1 (Female-predominant) vs. Cluster 2 (Male-predominant) Baseline comparison (Table 1):Cluster 2 displayed higher BMI (27.3 ± 2.8 vs. 25.2 ± 2.9 kg/m², p < 0.001) and AHI (55.0 ± 16.1 vs. 49.8 ± 13.2, p = 0.001).The Apnea Index (AI) was significantly higher in Cluster 2 (44.5 ± 16.9 vs. 34.3 ± 15.1, p < 0.001), but the Hypopnea Index (HI) was lower (10.5 ± 7.2 vs. 15.5 ± 12.4, p < 0.001).Multi-Organ Function Impairment (Table 2):Cluster 2 exhibited significantly worse renal markers, including higher Creatinine (85.05 ± 12.06 vs. 69.53 ± 13.07 $\mu$mol/L, p < 0.001) and blood urea nitrogen (BUN) levels.Cluster 2 showed higher liver transaminases (ALT: 25.95 ± 13.14 vs. 17.75 ± 9.31 U/L, p < 0.001; $\gamma$-GT: 52.81 ± 56.50 vs. 25.82 ± 14.22 U/L, p < 0.001).Comorbidities Prevalence (Table 2):Carotid Atherosclerosis (CAS) was significantly more prevalent in Cluster 2 (39.8% vs. 16.2%, p < 0.001).Nonalcoholic Fatty Liver Disease (NAFLD) was also significantly more prevalent in Cluster 2 (42.2% vs. 15.4%, p < 0.001)."		"The identified clusters are highly correlated with biological sex; further research incorporating hormone/endocrine profiling is required to establish the precise pathophysiological mechanisms.
The study cohort was restricted exclusively to severe OSA patients, meaning findings are not generalizable to patients with mild-to-moderate OSA.
Being a single-center hospital study, the generalizability of these organ-function-based phenotypes across different regions and ethnicities is limited.
Subjective sleepiness (such as the Epworth Sleepiness Scale) or therapeutic compliance metrics (CPAP use) were not integrated into the clustering variables."
Obstructive sleep apnea and genotype rs6843082 as a risk factor for cerebrovascular accident.(2024) | Venue: Scientific Reports | DOI: 10.1038/s41598-024-74782-x.	"SAS version 9.4 & PLINK, Affymetrix Axiom™ Genome-Wide Array Plate System.Regression Framework: Multivariate Unconditional Logistic Regression to calculate odds ratios (ORs) and 95% confidence intervals (CIs) for stroke risk, stratified by rs6843082 genotypes (GG vs. GA + AA) and hypertension status23.Hypothesis Testing: Chi-square ($\chi^2$) test (for categorical/discrete variables) and unpaired Student's $t$-test (for continuous variables)2. "	"Dataset:Linked retrospective cohort combining the Taiwan Biobank (TWB) (2008–2015 genotypic/lifestyle data) and the National Health Insurance Research Database (NHIRD) (1998–2015 clinical diagnoses).
Quantity: 17,915 participants (1,020 stroke patients and 16,895 control subjects).
Domain: Genomic epidemiology and clinical stroke history in the Taiwanese population."	"Odds Ratio (OR) with 95% Confidence Interval (CI), Chi-square ($\chi^2$) p-value, and Student's t-test."	"Stroke Risk Factors (Table 1): OSA (OR = 2.182, 95% CI: 1.634–2.914, p < 0.05); Hypertension (OR = 2.443, 95% CI: 2.096–2.848).
GG Genotype Subgroup (Table 4): OSA was a significant risk factor for stroke in both non-hypertensive (OR = 2.75, 95% CI: 1.36–5.57) and hypertensive patients (OR = 2.17, 95% CI: 1.41–3.34).
GA + AA Genotype Subgroup (Table 5): OSA was significantly associated with stroke only in hypertensive patients (OR = 2.57, 95% CI: 1.53–4.33). It was not associated with stroke in those without hypertension (OR = 0.53, 95% CI: 0.13–2.25).
Combined Interaction (Table 6): For GA+AA carriers, the co-existence of OSA and hypertension yielded the highest stroke risk (OR = 6.25, 95% CI: 3.63–10.76) compared to the non-OSA, non-hypertensive reference group."		"The study relies on retrospective observational data, which limits the ability to establish direct causation.
Due to the limited sample size of stroke patients, researchers could not investigate association with specific stroke subtypes (e.g., ischemic vs. hemorrhagic).
Due to the low frequency of the rs6843082 ""A"" allele in the population, the (G;A) and (A;A) genotypes had to be combined into a single group for statistical observation.
Potential residual confounding from unmeasured variables could still influence the adjusted risk ratios.
The analysis was restricted to Taiwanese individuals, meaning findings may not be generalizable to other ethnic groups with different genetic backgrounds."
"Sleep Apnea?Specific Hypoxic Burden, Symptom Subtypes, and Risk of Cardiovascular Events and All-Cause Mortality(2022) | Venue: American Journal of Respiratory and Critical Care Medicine | DOI: 10.1164/rccm.202105-1274OC"	"SAS 9.4 software & Latent Class Analysis (LCA)
.
Regression Framework: Cox Proportional Hazards Models adjusted for age, sex, smoking status, BMI, prevalent comorbidities (diabetes, COPD, hypertension), sleep study type/site, and medications (Model 1), plus CPAP treatment follow-up (Model 2)
.
Competing Risks: Fine and Gray Competing-Risk Regression used to evaluate nonfatal CV events against competing risk of death
."	"Dataset:
Name/Source: Pays de la Loire Sleep Cohort linked to health administrative data from the French National Health Insurance Information System (SNDS)
.
Quantity: 5,358 patients with newly diagnosed OSA and no overt cardiovascular disease at baseline
.
Domain: Clinical sleep medicine and cardiovascular epidemiology
"	"Hazard Ratio (HR) with 95% Confidence Interval (CI), log-rank p-value, and concordance index (C-index)"	"Symptom Subtypes Identified (Figure 2): Minimally symptomatic (22.0%), Disturbed sleep (17.5%), Excessively sleepy (49.8%), and Moderately sleepy (10.6%)20.MACE Incidence: 11.05% (592/5,358 patients) experienced MACE during a median follow-up of 78 months21.Predictive Performance of Hypoxic Burden (HB) (Model 2): HB was an independent predictor of MACE (HR = 1.21 per 1-SD increase; 95% CI: 1.07–1.38, p = 0.002)2122.Overall Nocturnal Hypoxemia ($T_{90}$): Significantly associated with MACE (HR = 1.34; 95% CI: 1.16–1.55, p < 0.0001)2122.Symptom Subtypes Predictive Value: Symptom subtypes showed significant differences in unadjusted models (minimally symptomatic had higher risk, HR = 1.33 vs. excessively sleepy) but were not independently associated with MACE after fully adjusting for traditional CV risk factors2223."		Sleep recordings were scored locally across different sleep sites without centralized inter-scorer reliability assessments24.Lack of pulmonary function test data means the potential confounding effects of underlying respiratory disorders (like COPD or obesity hypoventilation syndrome) on $T_{90}$ and MACE could not be fully ruled out25.
Screening for obstructive sleep apnea with novel hybrid acoustic smartphone app technology(2020) | Venue: Journal of Thoracic Disease | DOI: 10.21037/jtd-20-804	"Firefly"" App / C++ SDK, MATLAB, Python, and TensorFlow
.
Regression & Deep Learning Framework: Proprietary hybrid AI/ML platform
. Active sonar (using frequency sweeps at 18–20 or 20–22 kHz to track respiratory movement) processed using regularized logistic regression models (trained via 5-fold cross-validation with robust fitting of residuals)
."	"Dataset:
Name/Source: Advanced Sleep Research (ASR) clinical sleep lab database, Berlin, Germany
.
Quantity: 248 adult overnight recordings (128 for training, 120 for independent test set evaluation)
.
Domain: Clinical PSG synchronized with Apple iOS and Android smartphones"	"Area under the ROC curve (ROC AUC), Area under the Precision-Recall curve (PR AUC), Sensitivity (%), Specificity (%), Positive Predictive Value (PPV), Negative Predictive Value (NPV), and Pearson correlation coefficient ($r$)33more_horiz."	"Diagnostic Performance for AHI $\ge$ 15 threshold (Test Set) (Table 6): Sensitivity of 88.3%, Specificity of 80.0% (PPV = 81.5%, NPV = 87.3%, ROC AUC = 0.92, and PR AUC = 0.89).AHI Correlation (Figure 12): Strong Pearson correlation coefficient of r = 0.81 on the independent test set (r = 0.90 on the training set) compared to reference PSG AHI.Clinical Severity Agreement: 95% of cases were within $\pm$ 1 class of PSG-defined OSA severity (none, mild, moderate, or severe)37."		"Single-site sleep laboratory setting (ASR, Europe) may not capture the full range of sleep-disordered breathing variability or setup conditions encountered in home environments (e.g., shifting sheets, blankets covering microphone, sleeping partners)3743.Performance degradation was observed, with a 3.3% drop in accuracy between the training set and the independent test set37.High false positive rate (35% of all FPs) occurred in patients suffering from severe Periodic Limb Movements during Sleep (PLMS $\ge$ 15 events/h), which mimic shallow breathing movements44."
Associations of the Cardiometabolic Index with the Risk of Cardiovascular Disease in Patients with Hypertension and Obstructive Sleep Apnea: Results of a Longitudinal Cohort Study(2022) | Venue: Oxidative Medicine and Cellular Longevity | DOI: 10.1155/2022/4914791	"R software version 4.0.1
.
Regression Framework: Cox Proportional Hazards Regression Models to compute hazard ratios (HR) and 95% CIs
. Model 1 adjusted for age/sex; Model 2 adjusted for drinking, smoking, history of diabetes, SBP, DBP, and BMI; Model 3 adjusted for all noncollinear variables
. Collinearity was calculated using the Variance Inflation Factor (VIF) with a strict exclusion threshold of VIF > 5
."	"Dataset:
Name/Source: Urumqi Research on Sleep Apnea and Hypertension (UROSAH) study (single-center cohort at Xinjiang Uygur Autonomous Region People’s Hospital)
.
Quantity: 2,067 hypertensive patients with OSA (selected from 3,605 consecutive suspects; 744 excluded for AHI < 5, 276 lost to follow-up, 518 excluded for baseline CVD or missing values)
.
Domain: Clinical sleep medicine, cardiovascular outcomes, and metabolic markers
."	"Hazard Ratio (HR) with 95% Confidence Interval (CI), Area Under the ROC Curve (AUC), C-index, Net Reclassification Improvement (NRI), and Integrated Discrimination Index (IDI)
.
"	"Events Logged: During a median follow-up of 6.83 years, 326 incident CVD cases occurred (121 strokes and 205 CHD events)5865.Risk Associations per 1-SD increment in CMI (fully adjusted Model 3) (Table 2):New-onset CVD: HR = 1.31 (95% CI: 1.20–1.43).New-onset CHD: HR = 1.33 (95% CI: 1.20–1.48).New-onset Stroke: HR = 1.27 (95% CI: 1.10–1.47).Tertiary Analysis (Tertile 3 vs. Tertile 1) (Table 2): Hypertensive patients in the highest CMI tertile ($\ge$ 1.21) had a 1.68-fold higher risk of CVD, 1.81-fold higher risk of CHD, and 1.47-fold higher risk of stroke.Incremental Predictive Value (Table 3): Adding CMI to the baseline risk model significantly improved the C-index (p < 0.001), continuous NRI (p < 0.001), and IDI (p < 0.001). CMI was the strongest individual adiposity predictor of CVD (AUC = 0.617) compared to TG, HDL-C, FPG, or WHtR alone."		"Retrospective cohort study design prevents establishing a direct causal relationship
.
Missing details on exact lifestyle factors, ethnic specificities, or psychosocial variables that could act as residual confounders
.
Type, intensity, and variability of lipid-lowering and antiplatelet therapies were not controlled, although adjusting for their baseline use was done
.
Single-center setting limits generalizability to broader ethnic and regional populations
.
"
"Validation of a new, minimally-invasive, software smartphone device to predict sleep apnea and its severity: transversal study(2024) | Venue:Université Paris Cité & Bichat Hospital | Link: http://arxiv.org/abs/2406.16953v1"	"Apneal® version 0.1 & PyTorch
.
Regression & Deep Learning Framework: A sequential deep-learning model (CNN-RNN architecture) released internally at the end of 2022
. It processes raw positional and cardiorespiratory features extracted from 3D acceleration (100 Hz), 3D angular velocity (100 Hz), and audio signals (8000 Hz) recorded by a chest-attached smartphone (iPhone 12 mini)
."	"Dataset:
Name/Source: Sleep Center clinical cohort at Bichat Hospital (AP-HP), Paris, France
.
Quantity: 44 adult patients completed the protocol (out of 46 enrolled; 2 excluded due to recording/placement errors)
.
Domain: In-hospital polysomnography (Alice 6, Philips Respironics) compared against a chest-mounted smartphone
."	"Area under the ROC curve (AUC-ROC), Area under the Precision-Recall curve (AUC-PR), Sensitivity, Positive Predictive Value (PPV), Intraclass Correlation Coefficient (ICC), and Pearson correlation ($r$)5354."	"Automatic Scoring (Apneal® Deep Learning vs. PSG-second):
Threshold AHI > 15: Sensitivity = 100%, PPV = 90.0% (AUC-ROC = 0.85)
.
Threshold AHI > 30: Sensitivity = 95.0%, PPV = 69.0% (AUC-ROC = 0.87)
.
Correlation: ICC = 0.84 and Pearson r = 0.87 for global AHI estimation.
Manual Scoring (Acoustic/Motion graph scoring vs. PSG-first):
Threshold AHI > 15: Sensitivity = 91.0%, PPV = 89.0% (AUC-ROC = 0.95, AUC-PR = 0.94)
.
Threshold AHI > 30: Sensitivity = 85.0%, PPV = 94.0% (AUC-ROC = 0.95, AUC-PR = 0.93)
.
Correlation: ICC = 0.89 and Pearson r = 0.90.
Individual Event Segmentation (Table 3): Automatic scoring achieved an event-level PPV of 0.69 and Sensitivity of 0.77
."		"Very small sample size (44 patients)
.
Monocentric set-up in a specialized reference sleep clinic introduced selection bias by including patients with highly severe sleep complaints and high OSA pretest probabilities
.
The automatic scoring algorithm in its early version (v0.1) required manual correction and struggled with separating cardiac-induced seismocardiogram signals from heavy motion artifacts"
Fusion of Millimeter-wave Radar and Pulse Oximeter Data for Low-burden Diagnosis of Obstructive Sleep Apnea-Hypopnea Syndrome(2025) | Venue: IEEE Transactions and Journals | Link: http://arxiv.org/abs/2501.15264v1	"PyTorch, RASA R-CNN & RassNet (with LSTM, Attentional Feature Fusion [AFF], and CRF layers)
.
Regression & Deep Learning Framework: 1D temporal object detection paradigm (RASA R-CNN) for direct event-level temporal localization
; sequential sleep staging (RassNet) using ResNet18 + LSTM + skip-connections (AFF) + Conditional Random Field (CRF) layer
. Decision-level Soft-fusion strategy using a lightweight 3-layer fully connected network trained with cross-entropy loss
. Optimization via Adam with Cosine Annealing learning rate
."	"Dataset:
Name/Source: Real-world clinical dataset collected from the Shanghai JiaoTong University School of Medicine Affiliated Sixth People’s Hospital (Trial Registration No. NCT06038006)
.
Quantity: 100 subjects with overnight sleep recordings (>800 hours)
.
Domain: Clinical overnight polysomnography (PSG) synchronized with non-contact radar/oximeter monitoring
"	"Intraclass Correlation Coefficient (ICC), Area under the Precision-Recall curve (AP0.5), Sensitivity (Se), Specificity (Sp), Accuracy (Acc), and Cohen's Kappa ($\kappa$)110."	"AHI Agreement with PSG: ICC = 0.9870 (Pearson correlation r = 0.988)111.OSAHS Diagnostic Accuracy (Table V):At AHI $\ge$ 5 threshold: 90.00% (Se = 90.41%, Sp = 88.89%, $\kappa$ = 0.7576).At AHI $\ge$ 15 threshold: 96.00% (Se = 90.24%, Sp = 100.00%, $\kappa$ = 0.9161).At AHI $\ge$ 30 threshold: 98.00% (Se = 96.00%, Sp = 98.67%, $\kappa$ = 0.9467).SAE Detection Performance (Table V): RASA R-CNN alone achieved AP0.5 = 68.05%, which improved by 6.18% to 74.23% after soft fusion with oximeter data.Sleep Staging Performance (Table IV): Wake-Sleep (WS) accuracy of 94.4% ($\kappa$ = 0.859); Wake-REM-Light-Deep (WRLD) accuracy of 80.7% ($\kappa$ = 0.723)."		"The proposed fusion strategies primarily adjust the confidence of SAEs detected by RASA R-CNN, making it difficult to recall abnormal events entirely missed by the radar12.Reduced effectiveness in classifying specific types of SAEs (e.g., distinguishing Central Apnea [CA] vs. Obstructive Apnea [OA]) because the system lacks respiratory airflow and effort signals, which are traditionally required by PSG12.CA does not always result in oxygen desaturation (OD), making $\text{SpO}_2$-based fusion less effective or potentially misleading for CA or Mixed Apnea (MA) detection13."
