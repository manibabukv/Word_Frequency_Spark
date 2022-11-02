## Data description
1. News articles for each day (Jan 1, 2012 – Dec 31, 2012) – total 291 files
2. Every file:
- All the articles published each day
- Each article is in a new line
- Each article is in json format
- Json Fields for each article:
  - 'city', 'code', 'title', 'text', 'source', ‘date'
 

## Problem:
1. Read the data (all the files in the ‘data’ directory) using the function textFile
2. Take only the “text” part of each article and count the frequency of all the words (convert the text into lowercase)
3. Remove (Filter) any word whose frequency is less than 10
4. Report the following:
  - The total size of the output data (after the filtering)
  - Frequency of the following words – congress, London, Washington, football
  - The word with maximum frequency for each month (hint: to read only a month’s articles you can use ‘*’. E.g. for February ‘2012-02*’ represents all    files starting with 2012-02,i.e. files belonging to Feb)
  - The list of words appeared on ‘2012-09-01’ but not on ‘2012-08-01’
  - Frequency of the word ‘monsoon’ for all months

