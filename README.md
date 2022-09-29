# fetch_exercise_public
This repository contains all the files created while working on the exercise for the Data Analyst position at Fetch. Below are the steps of the exercise and files associated:

1. **Review Existing Unstructured Data and Diagram a New Structured Relational Data Model**
    * Files given (compressed json.gz): [brands.json.gz](https://github.com/bmbailey411/fetch_exercise_public/files/9668622/brands.json.gz), [receipts.json.gz](https://github.com/bmbailey411/fetch_exercise_public/files/9668626/receipts.json.gz), [users.json.gz](https://github.com/bmbailey411/fetch_exercise_public/files/9668632/users.json.gz)
    * R Code to decompress to JSON: [gz_unzip_r_code.txt](https://github.com/bmbailey411/fetch_exercise_public/files/9668639/gz_unzip_r_code.txt)
    * JSON files resulting from R Code output: *brands.json*, *receipts.json*, *users.json*
         - Note, JSON files could not be embedded direcfly in the README.md file, but they are in the repository
    * Data Model: [Data Model.pdf](https://github.com/bmbailey411/fetch_exercise_public/files/9668648/Data.Model.pdf)
         - As noted in the file, the data model I proposed breaks the receipt item list into its own table, which can then be joined/related to the brands table

2. **Write a query that directly answers a predetermined question from a business stakeholder**
    * Query: [top_brand_query.txt](https://github.com/bmbailey411/fetch_exercise_public/files/9670807/top_brand_query.txt)
    * Questions answered:
        - What are the top 5 brands by receipts scanned for most recent month?
        - How does the ranking of the top 5 brands by receipts scanned for the recent month compare to the ranking for the previous month?

3. **Evaluate Data Quality Issues in the Data Provided**
    * To evaluate the data, I brought the JSON files directly into Tableau
    * Tableau was able to parse out the Receipt Item List from the receipts.json file so that I could work with it in a similar manner as if I were pulling from the proposed data model above
    * The biggest issue I found was that more than half (58%) of the items on the receipts had null values for the barcodes
    * With the barcode being the link to our brands data, this has a large impact of doing any analysis by brand
    * PDF summarizing findings: [Data Issues.pdf](https://github.com/bmbailey411/fetch_exercise_public/files/9671057/Data.Issues.pdf)
    * The packaged Tableau workbook that I made to produce the pdf is in the repository

4. **Communicate with Stakeholders**
    * My assumption when reading the instructions for this section was that the email should answer all of the questions listed. 
    * For the sake of context, I am emailing a Product leader by the made up name of Elizabeth
    * Email Draft: [Email.pdf](https://github.com/bmbailey411/fetch_exercise_public/files/9671409/Email.pdf)

