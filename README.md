# fetch_exercise_public
This repository contains all the files created while working on the exercise for the Data Analyst position at Fetch. Below are the steps of the exercise and files associated:

1. **Review Existing Unstructured Data and Diagram a New Structured Relational Data Model**
    * Files given (compressed json.gz): [brands.json.gz](https://github.com/bmbailey411/fetch_exercise_public/files/9668622/brands.json.gz), [receipts.json.gz](https://github.com/bmbailey411/fetch_exercise_public/files/9668626/receipts.json.gz), [users.json.gz](https://github.com/bmbailey411/fetch_exercise_public/files/9668632/users.json.gz)
    * R Code to decompress to JSON: [gz_unzip_r_code.txt](https://github.com/bmbailey411/fetch_exercise_public/files/9668639/gz_unzip_r_code.txt)
    * JSON files resulting from R Code output: *brands.json*, *receipts.json*, *users.json*
    * Data Model: [Data Model.pdf](https://github.com/bmbailey411/fetch_exercise_public/files/9668648/Data.Model.pdf)
         - As noted in the file, the data model I proposed breaks the receipt item list into its own table, which can then be joined/related to the brands table

2. **Write a query that directly answers a predetermined question from a business stakeholder**
    * Query: [top_brand_query.txt](https://github.com/bmbailey411/fetch_exercise_public/files/9670807/top_brand_query.txt)
    * Questions answered:
        - What are the top 5 brands by receipts scanned for most recent month?
        - How does the ranking of the top 5 brands by receipts scanned for the recent month compare to the ranking for the previous month?

3. **Evaluate Data Quality Issues in the Data Provided**
    * Bullet
    * Bullet

4. **Communicate with Stakeholders**
    * Bullet
    * Bullet
