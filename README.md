# Natural_Language_Processing-NLP-
Implementation of VideoIntelligence API and working with NLP ,Yake and Summa methodologies to find out dominant words from the video after converting them to Transcripts. 

# Advertisement Categorization Project

## Goal
The primary objective of this project is to develop and train a model capable of detecting categories within a given dataset of advertisement videos. The dataset, totaling 28GB, is hosted on the Google Cloud platform, and the Video Intelligence API is employed for local authentication and video analysis.

## Workflow
1. **Data Access:**
   - A massive video dataset is uploaded to the Google Cloud platform.

2. **Authentication and Video Analysis:**
   - The Video Intelligence API is utilized for local authentication and analysis of each video in the dataset.

3. **Category Detection Approach:**
   - To achieve the goal of categorization, a unique approach is taken. Instead of relying solely on traditional methods like logo and label detection (which proved to be inefficient), the project focuses on video transcripts.

4. **Transcript Analysis:**
   - Videos are converted into transcripts, and NLP techniques, specifically YAKE and SUMMA, are employed to extract dominant words. These words serve as key indicators of the content and category of the advertisement.

5. **Model Training:**
   - Leveraging the insights obtained from transcript analysis, a comprehensive Excel sheet is created. This sheet becomes the foundation for training machine learning models.

6. **Machine Learning Models:**
   - Different models, including Naviese Baise, decision tree, and Random Forest, are implemented and evaluated to determine the most effective approach for categorization.


## Acknowledgments
- This project makes use of the Google Cloud Video Intelligence API.
- NLP methods YAKE and SUMMA enhance transcript analysis.

## Contributors
- Saibhargav CHintakindi
- Nilesh, Siddharth, Jabili, Manvitha, Sarthak, Diana

