# Study: Metabolic Bypass Effects of Cold Stimulation on Trauma-Related Emotions

This repository provides all materials related to the self-experimental study on oropharyngeal cold stimulation for emotion regulation.

## 🔗 Direct Link to Raw Data
The complete, raw dataset is permanently archived on Zenodo:  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11451400.svg)](https://doi.org/10.5281/zenodo.11451400)

## 🗂️ Project Overview & Analysis Transparency

This study was conceived and conducted by a researcher with a background in materials science and a deep personal interest in affective neuroscience. The analysis was performed iteratively with the assistance of AI tools (**DeepSeek-V3**) to navigate statistical methods beyond my primary field of study.

### **How to Understand and Reproduce the Analysis:**

1.  **Data Collection Protocol:**
    -   All physiological (HR, HRV) and subjective (Emotional Intensity 0-10) data were recorded manually in real-time during peak distress states.
    -   The data structure is presented in the `横向数据分析.xlsx` file on Zenodo, with each sheet representing a different experimental condition or day.

2.  **Statistical Reasoning and Steps:**
    -   The core analysis aimed to compare the effects of different interventions (Ice vs. Iced Glucose vs. No Intervention).
    -   **Key Comparison:** The paired t-test was selected to compare the average subjective emotional intensity score **before** and **~28 seconds after** the ingestion of pure ice.
    -   **Justification for Test Choice:** A paired design was used because each data point (post-intervention) was intrinsically linked to a baseline measurement (pre-intervention) from the same individual under the same emotional episode.
    -   **Result:** The analysis showed a statistically significant reduction in emotional intensity (p < 0.05) following ice ingestion.

3.  **My Role vs. AI Assistance:**
    -   **My Contribution:** I defined the hypothesis, designed the experiment, collected all data, formulated the clinical question ("Did the ice make a difference?"), and interpreted the results within a neurophysiological framework.
    -   **AI's Role:** I used DeepSeek-V3 to confirm the appropriate statistical test (paired t-test) for my experimental design and to perform the actual calculation based on the data I provided. This was a collaborative tool to overcome a methodological gap.

4.  **How to Re-run the Analysis:**
    -   The raw data for the key comparison is available in the Zenodo dataset.
    -   Any researcher can import this data into statistical software (e.g., SPSS, R, Python, or even online calculators) and perform a paired t-test to verify the significance of the mean difference in scores.

## 📄 License
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). This means you are free to share and adapt the material, as long as appropriate credit is given.
