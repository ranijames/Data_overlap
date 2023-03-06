# Data_overlap

The Data Overlap has been developed to identify common elements between columns of a given dataframe. The columns of the dataframe may contain either string or numerical values. Data Overlap can compute intersections of categorical or string lists (e.g., genes) as well as numerical values. To use the Data Overlap tool, one should input a dataframe where the columns represent the lists to be compared for their intersection. Any number of columns can be included in the input. 

# Installation

```pip install ```

# Useage

```overlaps = Overlaps(df)```

### To view the output

```overlaps.get_the_overlaps(df)```

