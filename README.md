# nosql-challenge

update = [
    {
        "$set": {
            "latitude": {"$toDouble": "$latitude"},
            "longitude": {"$toDouble": "$longitude"}
        }
    }
]

https://stackoverflow.com/questions/15943769/how-do-i-get-the-row-count-of-a-pandas-dataframe

df.shape[0]
