# Using TF-IDF Score to Detect the Source of the Text: Human-Written vs. AI-Generated

The advent of Large Language Models (LLMs) like ChatGPT has revolutionized natural language processing, particularly in academic contexts. However, concerns arise regarding the dis-cernibility between human and AI-generated essays, necessi-tating effective detection mechanisms. This study employs Term Frequency-Inverse Document Frequency (TF-IDF) analy-sis to differentiate between human-written and AI-generated essays. Using a dataset from Kaggle and a Support Vector Ma-chine (SVM) model, the research achieves an accuracy of 99% in classifying essays. Morphological analysis reveals nuanced differences, such as AI's preference for academic language and humans' tendency towards personalized narratives. While TF-IDF proves effective, limitations exist, including dataset di-versity and TF-IDF's inability to capture word relationships comprehensively. Future work entails exploring diverse da-tasets, incorporating linguistic features, and refining classifica-tion models to enhance accuracy and applicability in distin-guishing human from AI-generated content. This study con-tributes to understanding AI's impact on writing styles and aids in developing robust detection methods for educational and cybersecurity purposes.

# Research Questions
For this research project, I aim to investigate and address the following two research questions:
1.	Can TF-IDF effectively train a Support Vector Ma-chine (SVM) model to differentiate between human-written essays and AI-generated essays?
2.	Are there discernible differences in the words used in human-written essays compared to AI-generated es-says based on the coefficients obtained from the SVM model trained in the first research question?

# Data
Data Source:  
Kaggle: [LLM - Detect AI Generated Text Dataset
LLM - Detect AI Generated Text Training Essay Dataset](https://www.kaggle.com/datasets/sunilthite/llm-detect-ai-generated-text-dataset)
## Limitations of this dataset
The dataset I'm using has several limitations that need to be addressed: 
1.	It lacks detailed descriptions regarding its collection methods and the individuals involved in the collec-tion process.
2.	The dataset does not include prompts for the provid-ed texts.
3.	Information about which generative models were used is missing.
4.	The dataset comprises a small portion of data from the Learning Agency Lab Kaggle competition, while another part is a random Kaggle user-generated.

While acknowledging the limitations of this dataset, it can still be effectively utilized despite the lack of detailed infor-mation about its collection process and origin. Here are my reasons:
1.	I attempted to find a better dataset to replace the one I currently use, specifically one provided by Scott from the Learning Agency Lab. However, upon exam-ining Scott's data, I discovered that the training data had extremely unbalanced labels for human and AI. Out of a total of 1376 rows, only 1 was labeled as AI-generated. In contrast, the dataset I am currently using is quite balanced, with a substantial amount of data available for analysis. While having more bal-anced data is preferable, the superior source does not align with the specific goals of my class assignment. Hence, I opted to use the current dataset.
2.	I have always been intrigued by the topic of distin-guishing between AI and human-generated text, espe-cially since ChatGPT gained popularity. Education serves a vital purpose, and without a supervised sys-tem to identify AI-generated text, students might in-advertently rely too heavily on AI without critical thinking. Therefore, my intention is rooted in a desire to contribute positively by applying what I have learned in this class.
3.	I discussed my concerns about using this dataset, given its lack of clear information, with Scott twice and Jess once. Both reviewed the data and the results from my initial data assignment, and they assured me that it was acceptable to use this dataset. As a result, I have decided to proceed with utilizing it.

# Support
For any issues, please email jiaying.liang@vanderbilt.edu or open an issue in this Github repo.
