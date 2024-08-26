---
## Deep-Physio-Recon
---

### Young Adult


<div style="display: flex; gap: 10px; margin-top: 10px;">
    <a href="#" target="_blank" class="md-button md-button--primary" style="padding: 4px 8px; font-size: 0.85rem;">REPO</a>
</div>


### Life-Span


<div style="display: flex; gap: 10px; margin-top: 10px;">
    <a href="#" target="_blank" class="md-button md-button--primary" style="padding: 4px 8px; font-size: 0.85rem;">REPO</a>
</div>

---
## Quality Assesment (QA)
---

While traditionally regarded as noise, systemic physiological processes are frequently shown to be linked with cognitive processes and may contribute valuable information to fMRI studies. Recognizing this, neuroimaging research increasingly draws upon concurrent recordings of peripheral physiology to enhance fMRI analysis. However, usefulness of physiological data is contingent upon the quality of the recordings as well as expertise in data handling. Quality assessment is not only a tedious process, but the assessments vary significantly between raters. While there are manual and template-based tools assessing peak detection quality (physiopy’s peakdet, PhysIO, etc.), and automated exclusion criteria based on statistical summary metrics, currently there are no automated approaches that can provide a quick quality check.

<p align="left">
<img src="https://github.com/neurdylab/physai/blob/main/docs/assets/images/qa.png?raw=true" width="500">
</p>

### Manual QA

We are working on designing a manual quality assessment tool for physiological data. This application will offers a streamlined interface for visualizing and evaluating data quality across various physiological signals, including but not limited to respiration and cardiac measures. 

With this app, users will efficiently navigate through individual subject waveforms, review timeseries data, and apply standardized quality labels. The tool will also enable textual annotations, providing context and insights into the quality of the waveforms.

<div style="display: flex; gap: 10px; margin-top: 10px;">
    <a href="https://github.com/neurdylab/physio_QA_manual" target="_blank" class="md-button md-button--primary" style="padding: 4px 8px; font-size: 0.85rem;">REPO</a>
</div>

---

### Automated QA

As research practices generate increasingly large datasets, the need for efficient and scalable QA processes has become paramount. Manual QA, while thorough, is time-consuming and often subject to human error and variability. To address these challenges, we are motivated to develop automated QA solutions using deep learning (DL) techniques.

Automated QA systems, powered by DL, can rapidly and consistently assess the quality of physiological data across large datasets, identifying patterns and anomalies that might be overlooked in manual review. By leveraging the ability of DL models to learn from vast amounts of data, we can achieve more accurate and objective assessments, reduce the burden on researchers, and ensure that high-quality data is consistently used in analyses.

<div style="display: flex; gap: 10px; margin-top: 10px;">
    <a href="https://github.com/neurdylab/physio_QA_dl" target="_blank" class="md-button md-button--primary" style="padding: 4px 8px; font-size: 0.85rem;">REPO</a>
</div>