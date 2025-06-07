1. Required Libraries:
   - pandas
   - requests
   - beautifulsoup4
   - nltk
   - textblob
   - syllapy

2. To install dependencies:
   pip install pandas requests beautifulsoup4 nltk textblob syllapy

3. How to Run:
   - Ensure Input.xlsx is in the same directory.
   - Place stopword files in a folder named "StopWords/"
   - Place master dictionaries in "MasterDictionary/"
   - Run main.py:
       python main.py

4. Output:
   - Extracted articles are saved to "articles/{URL_ID}.txt"
   - Final analysis is saved as "Output.xlsx"
