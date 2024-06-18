Patent Analysis with BERTopic
This Jupyter notebook demonstrates the use of BERTopic for analyzing a large dataset of patents. The notebook provides an end-to-end workflow for extracting and visualizing topics from patent data.

Overview
The objective of this project is to apply topic modeling on a dataset of patents to uncover hidden themes and trends. The analysis leverages BERTopic, a state-of-the-art topic modeling tool, to generate interpretable topics.

Features
Data Loading and Preprocessing: Load a dataset of patents, including titles, abstracts, and other metadata.
Exploratory Data Analysis (EDA): Perform initial analysis to understand the structure and content of the dataset.
BERTopic Modeling: Apply BERTopic to extract topics from the patent abstracts.
Visualization: Visualize the topics and their distributions across the dataset.
Dataset
The dataset contains the following columns:

title: The title of the patent.
link: URL link to the patent.
abstract: The abstract of the patent.
application_number: The application number of the patent.
inventors: The inventors associated with the patent.
assignee: The assignee of the patent.
filing_date: The date the patent was filed.
publication_date: The date the patent was published.



Install dependencies:

pip install -r requirements.txt

Run the notebook:
Open the patent_big_data_bertopic.ipynb notebook in Jupyter and execute the cells.

Results
The notebook will generate the following outputs:

Topic distributions for the entire dataset.
Visualization of topics over time.
Examples of patents for each topic.
Dependencies
pandas
numpy
BERTopic
matplotlib
seaborn
scikit-learn
Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements.
