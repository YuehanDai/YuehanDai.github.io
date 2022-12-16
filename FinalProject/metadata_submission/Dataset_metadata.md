1. Name of Dataset
   * calendarific
2. Source url
   * https://calendarific.com/
3. publisher of dataset - example: USGS
   * calendarific
4. Publication date
   * This is an online API, unknow publication date.
5. Last update - if it has been updated since publication or is being updated regularly, when and how often. If not, same as original publication date.
   * 2022.9.19
6. Date/Time Range - the earliest and latest entries of your data, if all data have the same date, provide just 1.
7. Dimension 1: Count - how many entries
   * 648 entries for 2022 year
8. Dimension 2: Columns - how many properties per entry
   * the json data type is below 
```
{
    "meta": {
        "code": 200
    },
    "response": {
        "holidays": [
            {
                "name": "Name of holiday goes here",
                "description": "Description of holiday goes here",
                "date": {
                    "iso": "2018-12-31",
                    "datetime": {
                        "year": 2018,
                        "month": 12,
                        "day": 31
                    }
                },
                "type": [
                    "Type of Observance goes here"
                ]
            }
        ]
    }
}
```

9.  Dimension 3: Filter and verify - what properties are you interested in exploring from above. Check that these properties exist in all or a large portion of your dataset? Example: not all Current Population Surveys record reason for unemployment, so if you are interested in that topic you would have to work with only about 60% of the dataset. Check for null, undefined, or blank values in your data. You can use a text editor, excel, google docs or anything you are familiar with to do a quick scan of the data.
    * The location and the type of each holidays. 

10.  Background and other uses: A basic search of the dataset subject, keywords to see what other things it has been used for. 
    * time management

