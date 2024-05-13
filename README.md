Module 12 Challenge

This repository contains data from the UK Food Standards Agency on restaurants and their hygiene ratings around the United Kingdom. The data is in the form of a json file that can be found in the Resources Folder. This file was then imported into a Mongo Database and using Pymongo the data was updated, cleaned, and analyzed. The code for this can be found in two Jupyter Notebook files, the first being the set up file where data is inserted as well as dataypes are changed. Then in the analysis file, queries are used to find certain aspects of the data and then the results are turned to pandas DataFrames. 

Chat GPT was utilized to help with the syntax to update the datatype using pymongo:

update = [
    {
        "$set": {
            "latitude": {"$toDouble": "$latitude"},
            "longitude": {"$toDouble": "$longitude"}
        }
    }
]


Then this forum from stack overflow was referenced on how to count rows of a dataframe: 

https://stackoverflow.com/questions/15943769/how-do-i-get-the-row-count-of-a-pandas-dataframe

