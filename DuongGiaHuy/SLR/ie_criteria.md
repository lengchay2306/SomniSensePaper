# Inclusion and Exclusion Criteria

| Code | Description |
| :--- | :--- |
| **IC-L** | Paper written in English |
| **IC-T** | Published in a conference or journal (excluding blogs, theses) |
| **IC-E** | Contains at least one quantitative/numerical result in a Table or Figure |
| **IC-A** | Adults aged between 18 and 70 years old |
| **IC-P** | Places the smartphone correctly on the mattress near the pillow as instructed |
| **IC-I** | Environmental interference (sleeps with a partner, pets, or loud background) |
| **IC-MOD** | Studies utilizing built-in smartphone sensors (passive microphone or 3-axis accelerometer) placed beside the subject or on the mattress |
| **IC-ALG** | Papers clearly presenting signal processing algorithms (e.g., FFT, MFCC, spectrograms) or machine learning models to detect/classify breathing patterns or apnea events |
| **IC-VAL** | Studies that validate their mobile sensor algorithms against clinical ground truth (e.g., standard Polysomnography - PSG, Type III Home Sleep Apnea Testing - HSAT, or expert-annotated clinical datasets) |
| **IC-AHI** | Quantifies Apnea-Hypopnea Index (AHI) or classifies clinical OSA severity grades |
| **IC-ENV** | Real overnight sleeping environment (non-laboratory simulated snoring) |
| **IC-MET** | Reports standard quantitative metrics (Sensitivity, Specificity, AUC, or AHI MAE) |
| **IC-DUR** | Continuous overnight recording duration of at least 4 hours per subject |
| **IC-CUT** | Reports diagnostic metrics at clinical cutoff thresholds ($\text{AHI} \ge 5, 15, \text{ or } 30 \text{ events/hour}$) |
| **EC-D** | Duplicate of an existing/already included paper |
| **EC-A** | Full-text is unavailable / inaccessible |
| **EC-S** | Under 4 pages (extended abstract, poster) |
| **EC-N** | No experiments / non-empirical (vision paper, tutorial) |
| **EC-M** | Diagnosed with severe respiratory or cardiovascular diseases (e.g., COPD) |
| **EC-DIS** | Suffers from severe sleep disorders (e.g., chronic insomnia, shift work) |
| **EC-EXT** | Requires external, dedicated peripheral sensors (e.g., finger-clip pulse oximeters $\text{SpO}_2$, EEG, chest straps, pressure mats) |
| **EC-SUR** | Screening methods relying solely on self-reported clinical questionnaires (e.g., STOP-Bang, Epworth Sleepiness Scale, Berlin Questionnaire) |
| **EC-SYN** | Evaluated solely on synthetic audio or non-sleep ambient sound datasets |
| **EC-PROP** | Black-box evaluations of closed-source commercial apps with undisclosed algorithms |
| **EC-PED** | Pediatric, infant, or child populations |
| **EC-CAM** | Video-based, infrared, optical, or thermal computer vision camera monitoring |
| **EC-BED** | Specialized under-mattress smart sheets, piezoelectric films, force sensors, or load cells |
| **EC-STAGE** | Classifies sleep stages (REM/NREM) only without apnea event detection or AHI calculation |
| **EC-CSA** | Targets Central Sleep Apnea (CSA) or Cheyne-Stokes breathing exclusively |
| **EC-SIMUL** | Uses awake simulated apnea, breath-holding, or nap tests under 2 hours |
| **EC-PRO-MIC** | Uses external studio condenser microphones or dedicated sound cards |
| **EC-SYS** | Focuses solely on system performance (battery drain, latency, UI) without clinical metrics |
| **EC-BENCH** | Evaluated solely on public clinical benchmark databases (e.g., PhysioNet, UCD Sleep Apnea Database, SHHS, MESA) without primary smartphone data collection |
| **EC-REV** | Literature surveys, systematic reviews, scoping reviews, or meta-analyses lacking primary software experiments |
| **EC-GATE** | Smartphone functions merely as a Bluetooth data gateway, receiver, or UI display for external hardware |
| **EC-EPOCH** | Restricts classification to isolated short audio frames/epochs (snore detection) without computing full-night hourly AHI |
| **EC-CLINIC** | Clinical drug trials (e.g., Tirzepatide), surgical therapies (MMA, implants), dental appliances (MAD), CPAP compliance, or secondary OSA comorbidity studies (COVID-19, stroke, Parkinson, Alzheimer, heart failure) |
| **EC-EAR-BED** | Utilizes smart earbuds/earables, smart pillows, under-mattress smart sheets, BCG/seismography, or RF/WiFi/UWB radar |
| **EC-NO-ABS** | Missing abstract metadata and the title is non-explicit regarding smartphone apnea sensing |
