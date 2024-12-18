Visual Analysis of the Ocean Microbiome
An interactive dashboard for exploring microbiome abundance data from oceanic samples collected during the Tara Oceans expedition. This tool employs multiple coordinated views to provide insights into microbial diversity and abundance patterns in relation to contextual metadata.
Background
The oceans, the largest cohesive ecosystem on Earth, are critical to understanding the evolution of life and preserving the planet. This project focuses on the visualization of heterogeneous and multivariate data related to the ocean microbiome, helping researchers and domain experts analyze microbial diversity, abundance, and relationships to environmental and geographic factors.
The project is designed with microbiologists and bioscience experts in mind, enabling exploration of questions such as:
•	Which microbes are most abundant overall or in specific ocean regions?
•	How do microbe abundance levels vary with geographic and environmental factors?
•	What patterns emerge at different taxonomic levels in relation to sampling metadata?
Aims of the Visualization
1.	Understand Overall Abundance Patterns: Highlight diversity and identify the most abundant microbial Classes.
2.	Contextualize Abundance Patterns: Correlate abundance profiles with metadata like geographic region, sampling depth, and marine biome.
3.	Facilitate Exploration: Provide both overview and detailed views of microbial abundance and diversity.
Features
•	Interactive Dashboard:
o	At least three coordinated views displaying different aspects of the data.
o	Linked interactivity for cross-filtering and detailed exploration.
o	Accessible design to accommodate diverse user needs.
•	Heterogeneous Data Support:
o	Contextual metadata such as latitude, longitude, sampling depth, and marine provinces.
o	Detection levels of 31 microbial Classes (aggregated from OTUs).
•	Exportable Visualization:
o	A standalone HTML file containing all visualizations, suitable for offline use.
________________________________________
Data
Dataset Overview
The dataset contains 135 samples with:
•	Metadata: Sample ID, location, depth, marine biome, and oceanic regions.
•	Microbial Detection Levels: Relative abundance for 31 microbial Classes.
Column	Description
SampleID	Unique identifier for each sample
Latitude, Longitude	Geographic coordinates of the sample
SamplingDepth	Depth of the ocean sample
MarinePelagicBiome	Biome classification of the sampling site
Microbial Classes	31 columns containing relative abundance data
________________________________________
Installation
Requirements
•	Python 3.7+
•	Libraries: Altair, Pandas, Vega Datasets, numpy
Setup
1.	Clone the repository: https://github.com/your_username/Ocean_Microbiome_Visualization.git
cd Ocean_Microbiome_Visualization
2.	Install dependencies:
pip install -r requirements.txt
3.	Load the dataset (TaraOcean_merged.csv) into the working directory.
4.	Run the Python script to generate visualizations:
python microbiome_dashboard.py
________________________________________
Usage
1.	Interactive Dashboard:
o	Open the standalone HTML file ocean_microbiome_visualization.html in any modern web browser.
o	Use coordinated views to:
	Select specific microbial Classes or oceanic regions.
	Investigate relationships between sampling metadata and microbial abundance.
	Compare abundance across geographic locations and depths.
2.	Customization:
o	Modify the Python code to add or remove views.
o	Update data or visualization properties to suit specific research needs.
________________________________________
Visualization Design
Views Implemented
1.	Geographic Distribution View:
o	Map of sampling locations with selectable marine regions.
2.	Abundance Overview:
o	Bar chart or stacked area chart showing the relative abundance of microbial Classes.
3.	Metadata Correlation View:
o	Scatterplot or parallel coordinates plot highlighting relationships between depth, region, and abundance.
Interactivity
•	Brushing and Linking: Select data in one view to highlight related data in other views.
•	Filters: Dynamic filtering by metadata (e.g., depth, biome).
________________________________________
Submission
The project deliverables include:
1.	Interactive Visualization: ocean_microbiome_visualization.html (standalone HTML).
2.	Source Code: Python script used to create the visualization.
3.	Report: A PDF document with:
o	Submission table justifying visualization design choices.
o	References for sources and design principles.
________________________________________
References
•	Tara Oceans Consortium: Tara Expedition Overview
•	Visualization Design Principles: "Visualization Analysis and Design" by Tamara Munzner.
•	Biological Taxonomy: Wikipedia: Taxonomy (biology)
