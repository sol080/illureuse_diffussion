# Diffusion of Botanical Illustrations

This repository contains the code and report for a side project extended from a group collective work ’Enlightening Illustrations: Analyzing the Role of Images in Early Modern Scientific Publications.’ in the [Helsinki Digital Humanities Hackathon 2023 (DHH23)](https://www.helsinki.fi/en/digital-humanities/helsinki-digital-humanities-hackathon-2023-dhh23). I reviewed data enrichment, particularly image similarity detection, for downstream analysis of botanical illustration diffusion. The enriched data is then used to examine The Diffusion of Innovations Theory by Everett Rogers (1962), which prompts discussion on limitations in data enrichment along with potential future topics.


### Pipeline
**1. Review illustration classification results:**
   - Using classification results from two models to collect botanical illustrations with higher certainty
**2. Revisit image similarity detection by resnet50 model:**
   - How does it perform on illustrations of different botanical works?
   - Selecting an image reuse detection scheme
**3. Examining the diffusion curves of botanical illustrations:**
   - Do they fit Roger's S-shaped diffusion model?

### Data
Data used in the analysis largely overlaps with the standardized dataset [here](https://github.com/dhh23/early_modern_data#early_modern_data).
Classification results by another CLIP model can be shared upon request.

### Report
The report is available [here](https://github.com/sol080/illureuse_diffussion/blob/main/report.pdf).
