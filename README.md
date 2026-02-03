![header image](/images/readme.png)

# Entrepreneurial Orientation Analysis: A Cross-Cultural Study

## Overview

What drives entrepreneurial success across different cultures? Is it intelligence, determination, or something more nuanced? This project explores these questions through a rigorous comparative analysis of entrepreneurial orientation (EO) between Western (Scotland) and Eastern (Malaysia) students.

## Research Focus

This analysis compares entrepreneurial orientation towards new venture creation between students from Scotland and Malaysia, examining whether cultural and geographical differences influence entrepreneurial mindsets and behaviors.

## Dataset

The study leverages comprehensive survey data from **359 participants** who completed a 65-item questionnaire:

### Survey Structure
- **50 items** measured on a 10-point Likert scale capturing latent dimensions of entrepreneurial orientation
- **15 demographic and supplementary questions**

### Participant Demographics
| Characteristic | Count | Percentage |
|----------------|-------|------------|
| **Female** | 236 | 65.7% |
| **Male** | 115 | 32.0% |
| **Undisclosed** | 8 | 2.3% |
| **Malaysia-based** | 252 | 70.2% |
| **Scotland-based** | 107 | 29.8% |

## Methodology

### Dimensionality Reduction with PCA

To avoid redundancy and enhance analytical efficiency, Principal Component Analysis (PCA) was applied exclusively to the 50 Likert-scale items. This approach identifies underlying patterns by consolidating related questions into coherent dimensions.

#### Example: How PCA Works

**Sample Survey Question:**
> *"How sure of yourself are you?"*  
> Students rate their response from 1-10

**Grouping Related Items:**  
PCA identifies questions that measure similar constructs. For instance:
- *"I tend to act boldly in situations where risk is involved"* (Q7)
- *"I like to take bold action by venturing into the unknown"* (Q32)

These correlated items are grouped into a single component, such as **Confidence**.

### Identified Components

Following rigorous statistical testing, **five core dimensions** emerged as the foundation for entrepreneurial orientation analysis:

1. **Self-Efficacy** – Belief in one's ability to succeed
2. **Risk-Taking** – Willingness to embrace uncertainty
3. **Autonomy** – Independence in decision-making
4. **Confidence** – Self-assurance and boldness
5. **Social Support** – Perception of external encouragement

## Getting Started

### Prerequisites

Install required R packages:

```r
install.packages(c("psych", "GPArotation", "paran", "maps", "dplyr", 
                   "ggcorrplot", "gridExtra", "car", "rstatix", "coin", 
                   "FSA", "shiny", "shinythemes", "ggplot2", "stringr"))
```

### Running the Analysis

1. Open `analyis.ipynb` in Jupyter or VS Code
2. Execute cells sequentially to reproduce the analysis
3. Explore visualizations and statistical results

### Shiny app

## Key Insights
**The Self-Efficacy and Autonomy Gap**: Scottish students consistently reported higher Self-Efficacy and Autonomy than Malaysian students, with moderate effect sizes. This is substantial because self-efficacy is a strong predictor of venture creation (Boyd and Vozikis, 1994; McGee et al., 2009).The gap suggests Western education fosters psychological readiness for entrepreneurship, whereas collectivist contexts may require additional confidence-building interventions. 

**The Age-Gender Interaction in Risk-Taking**: While no overall gender difference in risk-taking emerged, a notable pattern appeared in the 30-39 age group, where men exhibited substantially higher risk-taking than women. This indicates that social and family responsibilities at mid-career stages, rather than inherent traits, constrain women's entrepreneurial risk-taking. This is consistent with research showing that caregiving roles disproportionately affect women's trajectories during these years (Jennings and Brush, 2013; Thébaud, 2015). 

**Entrepreneurial Intention and Psychological Readiness**: Students intending to start businesses showed significantly higher Confidence and Risk-Taking, confirming that psychological orientation predicts entrepreneurial action (Krueger et al., 2000). However, moderate effect sizes suggest education can meaningfully influence students without strong entrepreneurial intentions. 

This analysis provides data-driven insights into how entrepreneurial orientation varies across cultures, offering valuable perspectives for:
- **Educators** designing entrepreneurship programs
- **Policy makers** fostering innovation ecosystems
- **Researchers** studying cross-cultural business behavior


