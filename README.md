<h1>TEMO Sunrooms Websites Chat Log Sentiment Analysis</h1>

<p>
  This project was created alongside <strong>Avi Herskowitz</strong>, a fellow Rutgers University student, and submitted as a final project for the <strong>Data Management for Data Science</strong> course at Rutgers University.
</p>

<h2>Overview</h2>

<p>
  In partnership with TEMO Sunrooms' Director of Sales, <strong>Robert Randall</strong>, this project aimed to analyze the sentiment of user interactions on the company's website chat logs. By conducting sentiment analysis, the objective was to gain deeper insights into the online user base, optimize customer service strategies, and drive business growth.
</p>

<h2>Defining the Problem</h2>

<p>
  TEMO Sunrooms, a leading U.S. manufacturer of sunrooms and outdoor living solutions, provided a dataset of approximately 2,000 chat logs. The key challenge was identifying trends in customer sentiment across variables like lead types, chat duration, and referral links. The project sought to offer actionable insights for improving customer experience and operational strategies.
</p>

<h2>Steps and Techniques</h2>

<p>
  The detailed steps for processing and analyzing the sentiment of chat logs are outlined in the document <code>Final Project Write Up.pdf</code>, included in the repository files. Major techniques and steps include:
</p>
<ul>
  <li><strong>Data Cleaning:</strong> Removal of irrelevant data, handling missing values, and formatting user input</li>
  <li><strong>Feature Engineering:</strong> Creation of meaningful features like chat duration and user engagement</li>
  <li><strong>Natural Language Processing (NLP):</strong> Tokenization, stemming, and lemmatization</li>
  <li><strong>Sentiment Analysis:</strong> Using the VADER sentiment analysis tool to classify text</li>
  <li><strong>Clustering:</strong> K-Means clustering to identify patterns in sentiment data</li>
  <li><strong>SQL Integration:</strong> Storing processed data in a structured database for querying and visualization</li>
  <li><strong>Visualization:</strong> Data visualization using Python libraries to uncover trends</li>
</ul>

<h2>Findings</h2>

<ul>
  <li>Sentiment scores were higher for TEMO website referrals compared to external referrals.</li>
  <li>Sales-related chats had the highest sentiment scores, suggesting effective targeting.</li>
  <li>Users engaging outside of normal business hours displayed specific sentiment trends, hinting at distinct user demographics.</li>
  <li>Providing personal information (name, email, phone, etc.) correlated with higher satisfaction.</li>
</ul>

<h2>Key Components</h2>

<ul>
  <li><strong>Dataset:</strong> Includes chat logs with attributes like timestamps, user location, lead types, and transcripts.</li>
  <li><strong>SQL Database:</strong> Six unique tables for efficient data management and analysis.</li>
  <li><strong>K-Means Clustering:</strong> Segmented user interactions into six clusters based on sentiment and other variables.</li>
</ul>

<h2>Important Disclaimer</h2>

<p>
  Due to the sensitive nature of the dataset, including personal user information, the data is not included in this repository. 
</p>

<p>
  For more information about the project and access to relevant insights, please contact:
</p>
<ul>
  <li>Email: <a href="mailto:mandryk.alexander@gmail.com">mandryk.alexander@gmail.com</a></li>
  <li>LinkedIn: <a href="https://www.linkedin.com/in/alexander-mandryk/">https://www.linkedin.com/in/alexander-mandryk/</a></li>
</ul>

<h2>Repository Structure</h2>

<ul>
  <li><strong>Final Project Write Up.pdf:</strong> Detailed documentation of the project's workflow and findings</li>
  <li><strong>CS210_Final_Project_Code:</strong> Python scripts for data cleaning, NLP, clustering, and visualization</li>
</ul>

<h2>Credits</h2>

<p>
  This project was a collaborative effort by <a href="https://github.com/aviherskow98">Avi Herskowitz</a> and Alexander Mandryk, with guidance from TEMO Sunrooms' Director of Sales, Robert Randall.
</p>

</body>
</html>
