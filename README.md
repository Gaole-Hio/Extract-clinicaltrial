# Extract-clinicaltrial

## Overview

**Extract-clinicaltrial** is a program designed to scrape, process, and analyze clinical trial data from [clinicaltrials.gov](https://clinicaltrials.gov/). This repository focuses on extracting information specific to Phase 1 and Phase 3 trials. The program provide a structured approach to data extraction and manipulation, suitable for researchers, data scientists, and professionals in the pharmaceutical and biotechnology industries.

## Features

- **Automated Data Extraction**: Use of Python and APIs to pull data from clinicaltrials.gov.
- **Phase-Specific Analysis**: Dedicated notebooks for Phase 1 and Phase 3 clinical trials, making it easy to focus on specific stages of drug development.
- **Advanced Filtering**: Advanced filtering to identify detailed information after Phase 1/3 extraction.

## Requirements

To run these notebooks, you'll need the following Python packages:

- `pandas`
- `requests`
- `json`
- `numpy`
- `matplotlib`
- `scipy`

You can install the necessary packages using `pip`:

\`\`\`bash
pip install pandas requests json numpy matplotlib scipy
\`\`\`

## Contents

This repository contains the following key notebooks:

- **`phase1_extract.ipynb`**: Extracts and processes data specific to Phase 1 clinical trials.
- **`phase3_extract.ipynb`**: Extracts and processes data specific to Phase 3 clinical trials.
- **`filter_intervention_after_phase3.ipynb`**: Filters and processes intervention data post-Phase 3, providing insights into successful or unsuccessful interventions.
