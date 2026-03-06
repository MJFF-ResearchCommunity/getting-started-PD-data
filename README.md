# Getting Started With Parkinson's Disease Data

A comprehensive web guide to accessing and using Parkinson's disease research datasets, created by the Data Community of Practice and powered by The Michael J. Fox Foundation for Parkinson's Research.

## Overview

This web book provides detailed information on four major Parkinson's disease datasets:

- **AMP PD** - Accelerating Medicines Partnership Parkinson's Disease
- **PPMI** - Parkinson's Progression Markers Initiative
- **GP2** - Global Parkinson's Genetics Program
- **FOX INSIGHT** - Online longitudinal clinical study

## What's Included

For each dataset, the guide covers:

- Study description and background
- Study data features (clinical, genomic, imaging, etc.)
- How to access data (step-by-step instructions)
- Intended data uses and research goals
- Dataset strengths and limitations
- Pre-existing documentation and FAQs
- Tips and practical considerations
- Update schedules

## Building the Book

### Requirements

- [Quarto](https://quarto.org/) (version 1.3 or higher recommended)

### Installation

1. Install Quarto from [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/)

2. Clone this repository:
   ```bash
   git clone https://github.com/MJFF-ResearchCommunity/getting-started-PD-data.git
   cd getting-started-PD-data
   ```

### Build Commands

**Preview the book locally:**
```bash
quarto preview
```

This will start a local web server and open the book in your browser. Changes to the source files will automatically reload.

**Render the book for production:**
```bash
quarto render
```

This will generate the static HTML files in the `_book/` directory.

**Clean build artifacts:**
```bash
quarto clean
```

## Project Structure

```
getting-started-PD-data/
├── _quarto.yml          # Main configuration file
├── index.qmd            # Landing page
├── overview.qmd         # Dataset comparison
├── amp-pd.qmd           # AMP PD chapter
├── ppmi.qmd             # PPMI chapter
├── gp2.qmd              # GP2 chapter
├── fox-insight.qmd      # FOX INSIGHT chapter
├── references.qmd       # Additional resources
├── styles.css           # Custom CSS styling
├── images/              # Image assets
├── README.md            # This file
├── LICENSE              # License information
└── .gitignore           # Git ignore rules
```

## Contributing

We welcome contributions to keep this guide current and comprehensive!

### How to Contribute

If you would like to:
- Add information about a new dataset
- Update existing content
- Correct errors or outdated information
- Suggest improvements to the guide

Please contact: [researchcommunity@michaeljfox.org](mailto:researchcommunity@michaeljfox.org)

### Contribution Guidelines

1. **Accuracy**: Ensure all information is accurate and up-to-date
2. **Citations**: Provide sources for data and statistics
3. **Clarity**: Write clear, concise descriptions accessible to researchers
4. **Consistency**: Follow the existing structure and style
5. **Links**: Verify all hyperlinks are functional

## Authors

- Michael Alosco, Boston University Chobanian & Avedisian School of Medicine
- Elizabeth Hutchins, TGen/DataTecnica/NIH CARD
- Paula Saffie Awad, CETRAM/Clínica Santa María
- Victoria Dardov, Technome
- Joshua Gottesman, The Michael J. Fox Foundation
- Hirotaka Iwaki, NIH CARD/NIA/DataTecnica
- Paula Reyes-Perez, UNAM
- Daniel Teixeira dos Santos, Hospital de Clínicas de Porto Alegre
- Maya Sanghvi, The Center for Scientific Collaboration and Community Engagement

## License

This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

See [LICENSE](LICENSE) file for details.

## Citation

If you use this guide in your research or reference it in publications, please cite as:

> Alosco, M., Hutchins, E., Saffie Awad, P., Dardov, V., Gottesman, J., Iwaki, H., Reyes-Perez, P., Teixeira dos Santos, D., & Sanghvi, M. (2024). *Getting Started With Parkinson's Disease Data* (Version 1.0). Data Community of Practice, The Michael J. Fox Foundation for Parkinson's Research.

## Acknowledgements

This guide is created by the Data Community of Practice and powered by The Michael J. Fox Foundation for Parkinson's Research.

We thank all the researchers, clinicians, and participants who contribute to these valuable datasets and make Parkinson's disease research possible.

## Support

For questions or feedback about this guide, please contact:
- **Email**: [researchcommunity@michaeljfox.org](mailto:researchcommunity@michaeljfox.org)

For dataset-specific questions, please refer to the contact information provided in each chapter.

---

**Version 1.0** | May 2024
