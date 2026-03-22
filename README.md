Chemises is a QSAR-based molecular prediction system built to compare two chemical compounds and estimate how compatible they are based on their molecular properties. It is designed as a web application where users can enter compounds by name, SMILES, or PubChem CID, and then the system fetches or loads descriptor data for analysis.

The project focuses on key molecular descriptors such as molecular weight, LogP, TPSA, hydrogen bond donors, hydrogen bond acceptors, rotatable bonds, heavy atom count, and aromatic ring count. After both molecules are loaded, Chemises compares their properties and combines them using different strategies such as average, weighted, sum, or synergistic methods. These combined values are then passed into a rule-based QSAR prediction model that generates a compatibility score and classifies the result as positive, moderate, or negative.

A major feature of Chemises is similarity analysis. The system creates simplified molecular fingerprints and uses Tanimoto similarity to find compounds in the database that are structurally close to the predicted outcome. This helps users understand which known molecules are most similar to the selected pair.

Chemises also includes interactive visual analytics. It displays radar charts for molecular comparison, bar charts for descriptor importance, and a prediction summary panel that explains the main factors affecting the result. These visualizations make the output easier to interpret for both learners and researchers.

The project has a built-in compound database containing common pharmaceutical and biochemical molecules such as aspirin, caffeine, ibuprofen, paracetamol, glucose, nicotine, morphine, cholesterol, vitamin C, and several antibiotics. This database makes it easy to test the system without manually entering complex molecular data.

Another important part of the system is prediction history. Chemises saves previous predictions so users can review past molecule pairs, strategies used, and outcomes. It also supports downloading a report of the prediction results for documentation or academic use.

Technically, the project is implemented using HTML, CSS, and JavaScript on the frontend, with PubChem REST API integration for molecular property retrieval and Chart.js for visualization. The UI is designed to be responsive, modern, and easy to navigate, with separate sections for introduction, database, prediction engine, property comparison, results, and history.

Overall, Chemises is a practical educational and research-oriented tool for exploring QSAR concepts, molecular similarity, and basic predictive chemistry in an interactive way. It demonstrates how molecular descriptors, similarity measures, and rule-based prediction logic can be combined into a useful cheminformatics application.
