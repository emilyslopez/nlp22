# Annotation Project

For our annotation project, we are aiming to build a classifier that can analyze the level of compassion news articles in the U.S. have towards U.S. immigrants. Determining the level of “compassion” an article has towards a group of people is a subjective process and can depend on a variety of different elements such as level of empathy and altruism. We decided to focus our project on the topic of immigration because the current political climate is highly polarized around this conversation. Immigration policy and reform has been continuously evolving and contested throughout history. To help us annotate our dataset in a consistent manner, we’ve identified 4 metrics to assess the level of compassion an article has:
* Does the article recognize the suffering?
* Does the reader feel moved by the person suffering and emotionally connect with their distress?
* Does the reader feel motivated to help alleviate that suffering?
* Does the article use derogatory terms?

For a given article, an annotator should score the above metrics from a 4 point Likert scale. Scores will then be averaged across all three segments to produce a float variable label.

The dataset that we will be utilizing is Crowd Counting Consortium’s data collection on political crowds in the US, which includes marches, protests, rallies, demonstrations, strikes, and similar actions. This dataset includes articles from news sources of all political leanings and consequently has articles that show a wide range of compassion levels towards immigrants.The CCC is collecting this data in the public interest and to further scholarly research, and is not formally affiliated with any other efforts to collect data on demonstrations. This github link ( https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5315311/ ) provides access to the dataset as well as its data dictionary.This dataset is neither private nor copyright and can be freely shared with others. Anyone who conducts research using the data is fully responsible for any necessary contact with their own Institutional Review Boards. The citation “Crowd Counting Consortium” should be included when using this dataset.

## In this Folder:
* AP4 pdf: PDF of the Jupyter Notebook with our Classifier/ Modeling and Performance
* Adjudicated.txt: Labeled data that has been adjudicated and will be used in our analysis
* Guidelines: Outline/guideline that an annotator should follow when annotating our data
* Individual annotations: Annotations for the data by an individual annotator before the annotations had been adjudicated
* Train test: Jupyter Notebook with our Classifier/ Modeling and Performance
