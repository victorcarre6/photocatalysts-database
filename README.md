# Photocompounds Database

An open-source database for photochemical compounds, giving various physicochemical properties about photocatalysts, dyes, natural products, and commun organic compounds.

This project aims to support researchers, chemists, and companies working in various fields such as photochemistry, materials science, and pharmaceutical development by providing a structured, data-rich resource for compound discovery, characterization, and analysis.

---

## Project Objectives

- **Data Collection** – Gather and organize information on chemical compounds from scientific literature and open databases (see sources.txt for details).
- **Chemical Characterization** – Document chemical structures and physicochemical properties for each compound.
- **Easy Access** – Provide an accessible, searchable database for chemical compounds and related materials with an API.

- **Data-Driven Insights** – Use this database for [Photocompounds Properties Predictor](https://github.com/victorcarre6/photocompounds-properties-predictor) : to predict compound properties, interaction mechanisms, and potential applications via machine learning.

---

## Current Status

Done:
- **Project Structure** – Initial project structure created (data, src, notebooks, docs, examples, sources).
- **Basic Data Set** – Sample data file added (data/sample_data.csv) as a starting point.

---

Ongoing:
- **Data Collection Scripts** – Initial Python scripts for data collection and management are being developed.
- **Cheminformatics Tools** – Basic tools for compound manipulation and analysis using RDKit and PubChemPy are implemented.

---

Planned:
- **Data Visualization** – Develop data visualization tools to highlight trends and insights, such as structural relationships and physicochemical property distributions.
- **Prediction Models** – Develop machine learning models for predicting compound behaviors, properties, and applications based on historical data. Starting point of [Photocompounds Properties Predictor](https://github.com/victorcarre6/photocompounds-properties-predictor).

---

## Getting Started

To run the code locally, you'll need the following packages (see requirements.txt for details):

    rdkit

    pubchempy

    pandas

    numpy

    scikit-learn

    matplotlib

    seaborn

    jupyter

---

### Installation

Clone the repository:

	```
	git clone https://github.com/votre-utilisateur/photocompounds-database.git
	cd photocompounds-database
	```

Install dependencies using pip:

	```
 	pip install -r requirements.txt
	```

---

### Usage

Load the dataset into a Python script or Jupyter notebook:

    import pandas as pd
    data = pd.read_csv("data/sample_data.csv")

Start exploring the data and using the cheminformatics tools available in the src folder.
Run scripts for data collection, cleaning, and visualization from the src folder.

### Running Jupyter Notebooks

Install Jupyter if not already installed:

	```
	pip install jupyter
	```

Run Jupyter notebook:
	```
   	jupyter notebook
	```

Open the relevant notebook and start experimenting with data and tools ! 😄

---

## Contributing

Feel free to contribute by submitting issues, making suggestions, or creating pull requests with improvements to the data structure, scripts, or any other aspect of the project.

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.
