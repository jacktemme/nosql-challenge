# nosql-challenge

update = [
    {
        "$set": {
            "latitude": {"$toDouble": "$latitude"},
            "longitude": {"$toDouble": "$longitude"}
        }
    }
]
