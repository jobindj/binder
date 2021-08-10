# MultiIndex Dataframe

> Provides hierarchical index in a [[DataFrame]]

## Add a new index to existing [[DataFrame]]

Using `pd.concat()` seems to be the easiest way to add a new index (for example, add a new dimension)

`multiindex_df = pd.concat ([df], keys=['label'], names=['nameOfIndex'], axis=1)`

Notes:

- `axis=0` add in rows direction and `axis=1` adds in the columns direction

## Combine MultiIndex [[DataFrame]]s

[[DataFrame]]s of similar dimensions can be combined using 

```newdf = pd.concat([df1,df2], axis=1)```