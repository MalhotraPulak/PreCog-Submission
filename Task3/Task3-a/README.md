### Submission for Task 3-A

- Code:  Task3-a-FinalSubmission.ipynb
- Mongo-Db-Collection: mongo-dumps folder
<br/>
To run the code change the filepath to required file path in first cell and then run all the cells in the notebook
<br/>
The final table is stored as a 2d list in a collection in the mongodb database

Notes:
- I was able to extract tables from 3 of the pdfs well except the with name EICHERMOT.pdf 
- For EICHERMOT.pdf the result i got is combined table with data from all tables, this is due to the fact i was relying on vertical and horizontal lines for the tables but in this pdf there were not any
- I have used vertical and horizontal line detection from [here](https://towardsdatascience.com/a-table-detection-cell-recognition-and-text-extraction-algorithm-to-convert-tables-to-excel-files-902edcf289ec)
