Data directory contains zipped `selected_data.pickle`.

Selected data is 25% of all locations with significant number of records.

Data format is:

```
data = {
    "train": {
        "points": train_points,
        "groups": train_groups,
    },
    "val": {
        "points": val_points,
        "groups": val_groups,
    },
}
```

`points` is `List[str]` of point hashes, `groups` is `List[pd.Series]` of publications number per hour in the corresponding point.
