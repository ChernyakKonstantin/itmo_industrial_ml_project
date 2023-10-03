Data directory contains zipped `selected_data.pickle`.

Selected data is 25% of all locations with significant number of records.

Data format is `{"points": points, "groups": groups}`. 
`points` is `List[str]` of point hashes, `groups` is `List[pd.Series]` of publications number per hour in the corresponding point.

