## Generative-AI-for-Data-Generation-and-Augmentation 


**Source:** Coursera — [Hands-on Lab: Generative AI for Data Generation and Augmentation](https://www.coursera.org/learn/generative-ai-elevate-your-data-science-career/ungradedWidget/WZuAD/hands-on-lab-generative-ai-for-data-generation-and-augmentation)

**GenAI tool:** [**ilovecsv**](https://ilovecsv.net/)

## Learning objectives

By the end of this lab, you will be able to understand and apply key concepts of synthetic data generation using generative AI tools in practical scenarios.

- Understand the concept of synthetic data generation using generative AI
- Use tools such as **Tonic Fabricate** and **ilovecsv** to create synthetic data samples
- Augment an existing CSV dataset while maintaining its statistical characteristics
- Explore how generative AI can enhance datasets for analysis, modeling, and other downstream tasks

## Insurance dataset overview

The dataset used in this lab includes insurance records.

This dataset is a cleaned version of the original dataset, meaning the data has been processed to remove errors, handle missing values, and ensure consistency.

The original dataset, [**Medical Insurance Price Prediction**](https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction?resource=download "Medical Insurance Price Prediction"), contains raw, unprocessed data and is available on [**Kaggle**](https://www.kaggle.com/ "Kaggle") under the [**CC0 1.0 Universal License**](https://creativecommons.org/publicdomain/zero/1.0/legalcode "CC0 1.0 Universal License"), which allows free use and distribution.

You can download the cleaned dataset file directly from the link provided here: [**Insurance Dataset**](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-AI0271EN-SkillsNetwork/labs/v1/m1/data/insurance_dataset.csv "Insurance Dataset")

### Option 1: ilovecsv Tool

The **ilovecsv** tool is a simple, GUI-based tool. You will now explore how to use it.

#### 1. Open the website

Click this [**ilovecsv**](https://ilovecsv.net/) link to open the website and interface.


#### 2. Create an account

You can create an account on this website free of charge, or you can simply log in using your Gmail ID. After you log in, you'll see the following interface:

#### 3. Upload the dataset

- Click on the **`Upload`** button given at the top of the page, and upload the CSV file of the data set to the interface.

- After uploading the dataset, you will be able to see the **insurance_dataset** file listed in the uploaded files section.

#### 4. Access the Data Augmentation tool

- You are on the main dashboard page. Scroll down through the available sections until you locate the **AI and Machine Learning** section, or use the left-hand navigation panel to quickly navigate to it directly.

- Within the AI and Machine Learning section, locate the **Data Augmentation Tool** from the available options and click on it to open the tool interface.

#### 5. Augment the data

Statistical augmentation in the ilovecsv tool involves generating synthetic rows from your existing dataset while preserving its statistical properties.

You can use the **Augmentation factor** to adjust the **density (number of rows)** of the synthetic dataset as required.

Once you have adjusted the augmentation factor **(for example, 1x)**, click the **`Execute Augmentation`** button.

#### 6. Download the synthetic data

After processing completes, you will see a notification that the operation is complete.

- Click the **`See Results`** hyperlink to open and view the final results in the editor.

- Close the results window and return to the previous page. Then click **`Download`** to save the output file to your local machine.

- In the final result, you will get 2,676 rows, which is double the original file since you selected a 1× augmentation factor. You can now use this synthetic data set for data science operations, or you can also augment the original data set with these samples.


