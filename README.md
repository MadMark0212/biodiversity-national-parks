# Biodiversity in U.S. National Parks

## Project Overview
This project analyzes biodiversity data from U.S. National Parks to explore patterns in species conservation status across different park locations.

Using Python and pandas, the analysis focuses on identifying endangered species, understanding species distribution, and uncovering trends related to conservation concerns.

## Data Sources
- `species_info.csv`: Contains species names, categories, and conservation status
- `observations.csv`: Contains observation counts of species across national parks

## Tools & Technologies
- Python
- pandas
- matplotlib / seaborn
- Jupyter Notebook

## Key Questions
- Which categories of species are most at risk?
- How does conservation status vary across parks?
- Are certain parks hotspots for endangered species?

## Files in This Repository
- `Biodiversity.ipynb` – Full analysis notebook
- `species_info.csv` – Species metadata
- `observations.csv` – Observation data
- `slides/` – Presentation slides summarizing findings

## How to Run
1. Clone this repository
2. Open `Biodiversity.ipynb` in Jupyter Notebook
3. Run all cells from top to bottom

## Key Insights
- Mammals and birds show higher proportions of protected species
- Certain parks have significantly higher counts of endangered species
- Conservation efforts may need to be park-specific

## Next Steps
- Incorporate time-based trends
- Visualize geographic patterns
- Expand to include climate or human impact data

## Slide Deck Outline

1. **Title Slide**
   - Project title
   - Your name
   - Date
   - Tools used (Python, pandas, matplotlib)

2. **Project Overview**
   - Purpose of the analysis
   - Key research question:
     - Which categories of species are most at risk in U.S. National Parks?

3. **Data Sources**
   - species_info.csv
   - observations.csv
   - Data provided by the National Park Service
   - Brief description of each dataset

4. **Data Cleaning & Preparation**
   - Handling missing values
   - Merging datasets
   - Grouping by species category and conservation status

5. **Exploratory Data Analysis**
   - Distribution of species by conservation status
   - Breakdown by species category
   - Key visualizations created

6. **Key Findings**
   - Mammals show higher proportions of protected species
   - Birds and reptiles are mostly of least concern
   - Certain categories are disproportionately at risk

7. **Visual Insights**
   - Bar charts comparing conservation status
   - Species category comparisons
   - Explanation of trends seen in plots

8. **Limitations**
   - Observation counts may not represent true population sizes
   - Dataset limited to recorded park observations
   - Conservation status categories are broad

9. **Conclusion**
   - Summary of main insights
   - Why this analysis matters for conservation planning

10. **Next Steps**
    - Include population estimates
    - Analyze trends over time
    - Incorporate geographic visualization (maps)
