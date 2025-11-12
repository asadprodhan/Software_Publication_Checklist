<h1 align="center">Software Publication Checklist</h1>


<h3 align="center"> Asad Prodhan<sup>*</sup> </h3>


<div align="center"><b> School of Biological Sciences, The University of Western Australia </b></div>


<div align="center"><b> 35 Stirling Highway, Perth, WA 6009, Australia. <sup>*</sup>Correspondence: prodhan82@gmail.com </b></div>


<br />


<p align="center">
  <a href="https://github.com/asadprodhan/AI-Powered_Microlearning/tree/main?tab=GPL-3.0-1-ov-file#readme"><img src="https://img.shields.io/badge/License-GPL%203.0-yellow.svg" alt="License GPL 3.0" style="display: inline-block;"></a>
  <a href="https://orcid.org/0000-0002-1320-3486"><img src="https://img.shields.io/badge/ORCID-green?style=flat-square&logo=ORCID&logoColor=white" alt="ORCID" style="display: inline-block;"></a>
</p>


<br />


### For releasing and indexing your next research software package  


This checklist summarises the full workflow that achieves maximum visibility, reproducibility, and citation credit.

---

## 1. Before Publishing

### Prepare Repository
- [ ] Finalise codebase and **tag a release** (`v1.0.0` or later)
- [ ] Include essential files:  
  `README.md`, `LICENSE`, `CITATION.cff`, `setup.py` or `pyproject.toml`
- [ ] Add a concise summary in GitHub’s **About** box  
  *(e.g., “Automated workflow for customised BLASTn databases”)*
- [ ] Verify author information and ORCID in `CITATION.cff`
- [ ] Add key badges (License, ORCID, DOI, Python version)

### Metadata Consistency
- [ ] Use the **same author name and email** across GitHub, Zenodo, and ORCID
- [ ] Maintain **consistent version numbers** (`v1.0.0`, `v1.1.0`, etc.)
- [ ] Select and declare a **license** (e.g., GPL-3.0, MIT) in both GitHub and Zenodo

---

## 2. Zenodo Integration

### Link and Release
- [ ] Connect your **GitHub account to Zenodo** (via *Zenodo → GitHub Integration*)
- [ ] Create a **tagged release** on GitHub; Zenodo will automatically archive and mint a DOI
- [ ] Update `CITATION.cff` and README with your **concept DOI badge**

```html
<a href="https://doi.org/10.5281/zenodo.xxxxxxxx">
  <img src="https://img.shields.io/badge/DOI-10.5281%2Fzenodo.xxxxxxxx-blue?style=flat-square&logo=Zenodo&logoColor=white"
       alt="DOI: 10.5281/zenodo.xxxxxxxx" style="display:inline-block;">
</a>

```

### If Uploading Manually
- [ ] Add a **clear title** and a concise description.  
- [ ] Include structured sections: **Abstract**, **Introduction**, **Implementation**, **Features**.  
- [ ] Choose an appropriate resource type: **Journal article** or **Software**.  
- [ ] Add relevant keywords: *bioinformatics, genomics, diagnostics, automation*, etc.

---

## 3. Visibility and Indexing

### ORCID
- [ ] Add the DOI under **Works → Add DOI → 10.5281/zenodo.xxxxxxxx**.  
- [ ] Assign contribution roles such as *Software, Methodology, Validation, Writing*.

### Google Scholar
- [ ] Manually add a new entry with the following metadata:  
  **Title**, **Author**, **Year**, **Publisher** = Zenodo, **DOI link**, **Type** = Software / Technical Note.  
- [ ] (Optional) Wait **2–6 weeks** for automatic indexing.

### GitHub
- [ ] Pin the **DOI badge** in the `README.md` file (immediately under the title).  
- [ ] Keep **release tags** and **Zenodo versions** synchronised.

---

## 4. Communication and Outreach

### Announce the Release
- [ ] Share the DOI and Zenodo link on **LinkedIn**, **X (Twitter)**, or **ResearchGate**.  
- [ ] Include your **institutional affiliation**.  
- [ ] Use simple visuals.  
- [ ] Mention the software in **presentations**, **seminars**, and **workshops**.

---

## 5. Maintenance and Citation Tracking

### After Release
- [ ] Confirm metadata consistency across **Zenodo ↔ ORCID ↔ GitHub**.  
- [ ] After 2–4 weeks, check visibility using the following search:  

- [ ] Monitor **citations** in Google Scholar.  
- [ ] For major updates, tag a new version (`v2.0.0`); Zenodo will automatically assign a `.v2` DOI.

---

## Summary

| Step | Purpose |
|------|----------|
| **GitHub → Zenodo** | Mint and archive DOI |
| **Zenodo → ORCID** | Establish authorship credit |
| **Zenodo → Scholar** | Ensure discoverability |
| **Scholar → Users** | Capture citations and impact |
