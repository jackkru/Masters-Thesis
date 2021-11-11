# Masters-Thesis

Master's Thesis for the Universty of Konstanz, done as a part of the Media Bias Group.

This thesis uses web-scraping and BERT Fine-Tuning to achieve close to 80% accuracy in classifying news headlines as biased or neutral. 

In the Scraping Folder, we find the R files used to scrape novel datasets from two popular news aggregator websites. We collected headlines and their respective labels using R Selenium, relying on political bias classifications as our labels.

In the Features Folder, you find the Python files where we carried out the entire classification process. Feature engineering, BERT fine tuning, along with several dataset comparison studies to increase the validity of our results.

In the Datasets Folder, all produced and used datasets are found, including those scraped from websites, those used for comparison purposes, and datasets of lexica used for feature engineering. 

For any questions about the datasets or classifiers, contact jackkru@gmail.com
